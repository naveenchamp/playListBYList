## 🎵 Playlist – *Ed Sheeran*


### 🎬 **Demo**

<div align="center">
  <video width="80%" autoplay loop muted controls style="border-radius:10px;box-shadow:0 2.8px 2.2px rgba(0,0,0,0.15)">
    <source src="https://assets.ccbp.in/frontend/content/react-js/music-playlist-output.mp4" type="video/mp4">
  </video>
</div>

---
### Design Files

<details>
<summary>Click to view</summary>

- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Music Playlist](https://assets.ccbp.in/frontend/content/react-js/music-playlist-lg-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - No Songs Found View](https://assets.ccbp.in/frontend/content/react-js/music-playlist-no-songs-found-lg-ouput.png)

</details>

### Completion Instructions

<details>
<summary>Functionality to be added</summary>
<br/>

The app must have the following functionalities

- Initially, the list of given track items should be displayed with a delete button for each track item
- When a non-empty value with key `name` from the `initialTracksList` provided in the search input then display the track items which includes the search input irrespective of case
- When the delete button of a track item is clicked, the respective track item should be deleted from the list of track items
- When a non-empty value is provided in the search input element, and no track item includes the value given in the search input, then [No Songs Found View](https://assets.ccbp.in/frontend/content/react-js/music-playlist-no-songs-found-lg-ouput.png) should be displayed
- When all track items are deleted, then [No Songs Found View](https://assets.ccbp.in/frontend/content/react-js/music-playlist-no-songs-found-lg-ouput.png) should be displayed

- The App is provided with `initialTracksList`. It consists of a list of trackItem objects with the following properties in each trackItem object

  |   Key    | Data Type |
  | :------: | :-------: |
  |    id    |  String   |
  | imageUrl |  String   |
  |   name   |  String   |
  |  genre   |  String   |
  | duration |  String   |

  </details>

### Important Note

<details>
<summary>Click to view</summary>

<br/>

**The following instructions are required for the tests to pass**

- The `imageUrl` in each track item should have alt as **track**
- The delete button in the track item should have the `data-testid` as **delete**

</details>

### Resources

<details>
<summary>Image URLs</summary>

- [https://assets.ccbp.in/frontend/react-js/music-playlist/music-playlist-Edsheeran-bg.png](https://assets.ccbp.in/frontend/react-js/music-playlist/music-playlist-Edsheeran-bg.png) background-image URL

</details>

<details>
<summary>Colors</summary>

<br/>

<div style="background-color: #152850; width: 150px; padding: 10px; color: white">Hex: #152850</div>
<div style="background-color: #cbd5e1; width: 150px; padding: 10px; color: black">Hex: #cbd5e1</div>
<div style="background-color: #ffffff; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>
<div style="background-color: #3b82f6; width: 150px; padding: 10px; color: black">Hex: #3b82f6</div>
<br/>

</details>

<details>
<summary>Font-families</summary>

- Roboto

</details>
<!-- Uploading "screencapture-naveenreddytippasanincnxhrjsce7hlq1-drops-nxtwave-tech-2025-11-18-17_24_57.png"... -->



### ⚙️ **Setup Instructions**

<details>
<summary>Click to view</summary>

```bash
# 1️⃣ Clone this repository
git clone https://github.com/<your-username>/playList-EdShereen.git
cd playList-EdShereen

# 2️⃣ Install dependencies
npm install

# 3️⃣ Run the app
npm start
