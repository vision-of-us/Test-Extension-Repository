# Extension-Repository
Extension Repository is a web application for browsing and downloading of extensions for popular software development tools.
The public part (home page) lists all approved extensions, together with "Featured", "New" and "Popular":

Featured extensions are those selected by site administrators.
New extensions are the extensions that have been updated most recently.
Popular extensions are those that have been downloaded the most.

There is a registration form for new users and, of course, a login form too.
When logged in the user can add a new extension, list and browse all extensions; they can be downloaded too.
When a new extension is created, it is in pending state and need to be manually approved by a site admin.
The extensions are also assigned different tags, like e.g. "Java", "Intellij-Idea", "Plugin", etc.
Clicking on one tag leads you to a list of all extensions that share the respective tag.

Extension fields number of open issues, number of pull requests and last commit date are fetched from GitHub. 
The admins can disable or delete users and approve or delete all extensions, not only those created (owned) by them.
When a user is disabled he is not allowed to login, but his user data is still kept.

The used technologies are Spring MVC/Spring Security, Hibernate, JPA, Thymeleaf and Bootstrap 