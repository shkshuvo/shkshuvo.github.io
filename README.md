# Sayed Hossain Khan — Personal Portfolio

This repository contains my personal GitHub Pages portfolio.

## Live Website

After GitHub Pages is enabled, the site will be available at:

```text
https://shkshuvo.github.io/
```

## Important Repository Name

The repository **must be named exactly**:

```text
shkshuvo.github.io
```

A repository named only `shkshuvo` is a project repository, so GitHub Pages publishes it under:

```text
https://shkshuvo.github.io/shkshuvo/
```

The special user-site repository `shkshuvo.github.io` publishes directly at:

```text
https://shkshuvo.github.io/
```

## Repository Structure

```text
shkshuvo.github.io/
├── _config.yml
├── _data/
│   └── navigation.yml
├── _layouts/
│   └── default.html
├── _pages/
│   ├── experience.md
│   ├── projects.md
│   ├── skills.md
│   ├── education.md
│   ├── publication.md
│   └── cv.md
├── assets/
│   └── css/
│       └── style.css
├── files/
│   └── cv.pdf
├── images/
│   └── profile.jpg
├── index.md
├── 404.html
├── Gemfile
├── .gitignore
└── README.md
```

## 1. Create the Correct Repository

Create a new **public** GitHub repository named:

```text
shkshuvo.github.io
```

The repository URL should be:

```text
https://github.com/shkshuvo/shkshuvo.github.io
```

You can keep your existing `shkshuvo` repository separately for your GitHub profile README.

## 2. Upload This Package

Extract the ZIP file first, then upload **all files and folders inside it** to the root of `shkshuvo.github.io`.

Correct:

```text
shkshuvo.github.io/
├── _config.yml
├── index.md
├── _pages/
├── _layouts/
├── assets/
└── ...
```

Incorrect:

```text
shkshuvo.github.io/
└── shkshuvo.github.io/
    ├── _config.yml
    ├── index.md
    └── ...
```

Do not upload only the ZIP file.

## 3. Add Your Profile Photo

Add your professional photo as:

```text
images/profile.jpg
```

A square photo of at least 500 × 500 pixels is recommended. If the file is missing, the website displays an `SK` fallback avatar.

## 4. Enable GitHub Pages

Open the `shkshuvo.github.io` repository and go to:

```text
Settings → Pages
```

Under **Build and deployment**, choose:

```text
Source: Deploy from a branch
Branch: main
Folder: / (root)
```

Click **Save**. GitHub may take a few minutes to publish the first deployment.

## 5. Confirm the Root-Site Configuration

`_config.yml` is already configured as:

```yaml
url: "https://shkshuvo.github.io"
baseurl: ""
```

Do **not** set:

```yaml
baseurl: "/shkshuvo"
```

That would be for a project site rather than your personal root site.

## Pages

- Home: `index.md`
- Experience: `_pages/experience.md`
- Projects: `_pages/projects.md`
- Skills: `_pages/skills.md`
- Education: `_pages/education.md`
- Publication: `_pages/publication.md`
- CV: `_pages/cv.md`
- Styling: `assets/css/style.css`

## Update Your CV

Your supplied CV is already included as:

```text
files/cv.pdf
```

When you update it later, replace that file while keeping the filename `cv.pdf`.

## Privacy and Banking Confidentiality

The public webpages intentionally do not repeat your full home address, phone numbers, or reference contact details. Banking project descriptions are also kept high-level.

Do not publish customer information, credentials, internal API URLs, production configuration, restricted architecture diagrams, proprietary source code, or confidential banking documents.

## Contact

**Sayed Hossain Khan**

- GitHub: https://github.com/shkshuvo
- LinkedIn: https://www.linkedin.com/in/sayed-hossain-khan-236906162/
- Email: sayedhossainkhan36@gmail.com
