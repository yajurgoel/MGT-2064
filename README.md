# FreshBristle 3D website

This website contains the interactive FreshBristle product assembly, its colors, and its texture labels. The model and textures are embedded in `index.html`. No packages, build commands, API keys, or separate model downloads are needed.

## Upload to GitHub

1. Create a repository on GitHub (for example, `freshbristle`). Use a public repository for the simplest GitHub Pages setup.
2. Open the repository and choose **Add file → Upload files**. An empty repository also offers an **uploading an existing file** link.
3. Open this folder on your computer and drag its **contents** into the upload area: `index.html` and `README.md`.
4. Choose **Commit changes**.

**Important:** `index.html` must be at the top level of the repository. Upload the files inside this folder, not the enclosing folder or the ZIP file.

## Enable the website

1. In the repository, open **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Select the branch containing your uploaded files (usually **main**) and **/(root)**.
4. Click **Save**.
5. After deployment finishes, return to this Pages screen and open the website link shown there.

The usual address is `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.

Official setup instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Using the viewer

- Drag the model to rotate it.
- Scroll to zoom.
- Move **Separate parts** to see the exploded assembly.
- Click **Show interior** to hide the housing.
- Click **Hide toothbrush** to inspect the cleaner alone.
- Click **Reset view** to restore the starting view.

You can also open `index.html` locally in a browser before uploading. A browser with WebGL support is required. This is a visual product concept, not a functioning cleaning device.

## Updating the site

Upload a replacement `index.html` to the same repository and commit the change. GitHub Pages will publish the updated file.
