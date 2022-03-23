## Disney Clone with GraphCMS

This repo is in support to the video tutorial on how to build a Disney Clone with GraphCMS.
In this project is build a disney clone using ReactJS and CMS for backend. In the main page we have a banner and cards with movies categories.  By clicking in the card we are redirected for a trailer for the movie.

<div align="center">
    <img src="https://user-images.githubusercontent.com/70040371/159704454-2a0d71d5-b7e9-449c-88ef-ceeee1353a12.png" width="600px">
</div>

<div align="center">
    <img src="https://user-images.githubusercontent.com/70040371/159704460-9ca9dbcd-864b-41a8-8f73-8b3c0505672e.png" width="600px">
</div>

### add assets

First, you need to create your GraphCMS Account and add assets to it as per the [video](https://youtu.be/u1ovHJXkPBY) tutorial.

### add a `.env` file

After the assets are loaded, add a `.env` file with the following:

```
GRAPH_CMS_TOKEN={your_token}
ENDPOINT={your_endpoint}
```

### `npm i`

Run the command above to install the packages.

### run

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
