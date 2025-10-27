# TODO: Implement Nested Routes with React Router

- [x] Update src/routes.js: Import App, restructure routes with App as parent, children for Home (with nested UserProfile), About, Login, errorElement on parent.
- [x] Update src/App.js: Add NavBar in header, import Outlet, fetch users in useEffect, pass users to Outlet context.
- [x] Update src/pages/Home.js: Remove NavBar and header, import Outlet and useOutletContext, get users from context, render Outlet above userList.
- [x] Update src/pages/UserProfile.js: Remove fetch logic, use useOutletContext to get users, find user by id.
- [x] Update src/components/UserCard.js: Add useOutletContext to log users for demo.
- [x] Run the app to test nested routing and data passing.
- [x] Verify user profiles display on the same page as user list (app running at http://localhost:3000, json-server at http://localhost:4000).
