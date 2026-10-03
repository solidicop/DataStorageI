# Stay Smart SQL

A mobile-first, static teaching companion for the 90-period **Storing Data I** syllabus. It includes a complete curriculum roadmap, teacher-only guidance, assessment materials, one consistent year-long academy database, and a browser SQL practice lab.

## Run locally

Open `index.html` directly, or serve the folder with any static web server. The SQL engine is bundled, so the lab does not depend on a CDN.

## Publish with GitHub Pages

1. Create a GitHub repository and place the contents of this folder at its root.
2. In **Settings → Pages**, choose **Deploy from a branch**.
3. Select the branch and `/ (root)`, then save.

No build command or server is required.

## Teacher mode

The classroom password is configured in `app.js`. Since GitHub Pages is static, this is a convenience lock—not secure authentication. Do not put private student information or confidential exam material in the public repository.

## SQL dialect note

The browser lab uses AlaSQL for fast, device-local practice. It covers the beginner DDL, DML and query patterns in this course. SQL Server-specific behavior and administration exercises should be demonstrated in SQL Server Management Studio.
