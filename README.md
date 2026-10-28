# CQB Shoot House Planner

A browser-based planner for close-quarters training. Lay out a structure on a 3 ft grid, give each shooter a route and a sequence of actions (looks, signals, gates, doors, flashbangs), and play it back on the plan, in 3D, or from a drone camera. Scenarios can be shared as links, codes, files, or videos.

**Open it:** https://swheel17-a11y.github.io/cqb-planner/

The whole planner is the single file `index.html`. Scenarios people make are saved in their own browser, not in this repository.

## Accounts (Firebase)

Sign-in and online scenarios use the Firebase project `cqb-planner` (Authentication + Cloud Firestore).
The database rules are in `firestore.rules`; paste them into Firebase console → Firestore Database → Rules → Publish.
