# colorstackatutrgv-github-io.vercel.app

[![Discord](https://img.shields.io/badge/ColorStack%20@%20UW--Madison-7289DA?style=for-the-badge&logo=discord&logoColor=white&style=flat-square)](https://discord.gg/CSAPytsdNv)
[![LinkedIn](https://img.shields.io/badge/ColorStack%20at%20UW--Madison-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&style=flat-square)](https://www.linkedin.com/company/colorstack-utrgv/)
[![Instagram](https://img.shields.io/badge/colorstackatuw-E4405F?style=for-the-badge&logo=instagram&logoColor=white&style=flat-square)](https://www.instagram.com/utrgvcolorstack)
[![Linktree](https://img.shields.io/badge/colorstackatuw-39E09B?style=for-the-badge&logo=linktree&logoColor=white&style=flat-square)](https://linktr.ee/UTRGVColorStack)

This repository contains the source files for the ColorStack at UTRGV website, hosted at [https://colorstackatutrgv-github-io.vercel.app/](https://colorstackatutrgv-github-io.vercel.app/).

> [!NOTE]
> The following information is primarily intended for internal use by ColorStack at UW-Madison. Please be aware that your site may be deployed in a different manner than ours.

## Editing The Site

To make changes to the website, place your files in the `public` folder within this Git repository.

> [!WARNING]
> Do not remove `index.html` or `error.html`, as they are required by the CDN.

## Deployment

Once changes are pushed to the repository:

- The changes automatically propagate to the live website.
- The CDN distribution may take between 1 and 5 minutes to redeploy. Please wait for this duration to see your changes live.

## Notes
- The default root object for the root and subfolders is `index.html`.
- The custom error document (e.g., for 404 errors) is named `error.html` and located at the root directory. Please customize this file as needed.
