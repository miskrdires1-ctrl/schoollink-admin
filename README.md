# SchoolLink admin console

Static build of the SchoolLink administrator console (approvals, people, classes,
attendance, absence requests, announcements, audit log, school settings).

The console talks to the SchoolLink Supabase project directly with the public
(publishable) key. Only administrators can sign in, and every new account has to
be approved from the Approvals page before it can read school data.

Source and database schema live in the private SchoolLink project.
