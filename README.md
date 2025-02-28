&nbsp;

# Goals/Outcomes ✨

- To test knowledge of consuming APIs and handling responses
- Loading state and knowing where and how to make multiple API calls efficiently
- Feel free to modify the base source code and styles as you like.
- Feel free to add packages (i.e. Redux, Recoil, React Query, etc.)

&nbsp;

# Pre-requisites ✅

- Node 16
- Add your Spotify client ID & secret to a `.env` file in root using the environment variables
- https://developer.spotify.com/documentation/web-api/quick-start/

`REACT_APP_SPOTIFY_CLIENT_ID` and `REACT_APP_SPOTIFY_CLIENT_SECRET`

- Note. **Never add this type of config to version control. This would usually come from your build server.**

&nbsp;

# Requirements 📖

- Fetch and display _Released This Week_ songs
  - Display `new-releases` on homepage (i.e. Discover)
- Fetch and display _User's Playlists_
  - Display 10 `playlists` on homepage
  - Display all `playlists` on `/playlists` page
- Create _Search_ page
  - UI Navigation `/search` for results
  - General search
  - Pagination
- Loading state/UI _(optional, current UX is already clean)_
- README file describing your approach, roadblocks, and things you would like to do if you had more time.

&nbsp;

# Think about 💡

- Taking a look at the Spotify API documentation
- Do you resolve each API request one after the other or in parallel?
- Where do you make the API requests?
- How much logic do you offload out of the UI components?

&nbsp;

# What's Already Been Done 🏁

- UI/UX for all elements, including previews (mobile responsive)

&nbsp;

# Screenshots 🌄

&nbsp;
![screenshot-desktop](https://puu.sh/GwPLE/3be580156a.png)
<img alt="screenshot-mobile" width=400 src="https://puu.sh/GwPLS/0bcb566d23.png" />
