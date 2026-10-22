# How to post on the blog

Posts are Markdown files in the `_posts` folder. GitHub builds the site and the post goes live about a minute after you save.

## Write a post on github.com

1. Open the `_posts` folder in this repository and click **Add file → Create new file**.
2. Name the file `YYYY-MM-DD-short-title.md`, for example `2026-10-21-my-first-post.md`. The date in the name is the date shown on the post.
3. Copy everything from `_templates/post.md` into the file and replace it with your writing.
4. Click **Commit changes**. Your post appears at `/blog/` and on the home page under "Latest from the blog".

## Add a picture

Upload it to `assets/images/` (**Add file → Upload files**), then add `![description](/assets/images/file-name.png)` in your post.

## Drafts

Files in `_drafts` are not published. Move a file into `_posts` and add the date to its name when it's ready.

## Edit or remove a post

Open the file in `_posts` and click the pencil icon to edit, or the three-dot menu to delete. Commit to publish the change.

## Share a post on LinkedIn

Every post has a **Share on LinkedIn** button at the bottom. LinkedIn shows the post's title, its `description` and a preview image. The image defaults to your share card (`assets/images/share-card.jpg`); to use a different one for a post, add `image: /assets/images/your-cover.jpg` to its front matter (1200 x 630 pixels works best).

If LinkedIn shows an old preview after you change a post, paste the post's link into https://www.linkedin.com/post-inspector/ to refresh it.

## Update your CV

The site always links to `assets/files/Ntiyiso-Wayne-Ndhlovu-CV.pdf`. To replace it:

1. Save your new CV as a PDF and rename it to exactly `Ntiyiso-Wayne-Ndhlovu-CV.pdf`.
2. Open the `assets/files` folder in this repository and click **Add file → Upload files**.
3. Drag in the PDF and click **Commit changes**. GitHub replaces the old file because the name is the same.

The new CV is live about a minute later. Every "Download CV" button and the short link **ntiyisondhlovu.github.io/cv** point to it, so nothing else needs changing.

Before uploading, remove anything you don't want public, such as references' phone numbers.
