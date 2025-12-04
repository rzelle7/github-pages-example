<!DOCTYPE html>
<html>
  <head>
    <title>YouTube.com Clone</title>

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="styles/general.css">
    <link rel="stylesheet" href="styles/header.css">
    <link rel="stylesheet" href="styles/video.css">
    <link rel="stylesheet" href="styles/sidebar.css">
  </head>
  <body>
    <header class="header">
      <div class="left-section">
        <img class="hamburger-menu" src="icons/hamburger-menu.svg">
        <img class="youtube-logo" src="icons/youtube-logo.svg">
      </div>
      <div class="middle-section">
        <input class="search-bar" type="text" placeholder="Search">
        <button class="search-button">
          <img class="search-icon" src="icons/search.svg">
          <div class="tooltip">Search</div>
        </button>
        <!-- Put position absolute inside position relative -->
        <button class="voice-search-button">
          <img class="voice-search-icon" src="icons/voice-search-icon.svg">
          <div class="tooltip">Search with your voice</div>
        </button>
      </div>
      <div class="right-section">
        <div class="upload-icon-container">
          <img class="upload-icon" src="icons/upload.svg">
          <div class="tooltip">Create</div>
        </div>
        <div class="youtube-apps-icon-container">
          <img class="youtube-apps-icon" src="icons/youtube-apps.svg">
          <div class="tooltip">YouTube Apps</div>
        </div>
        <div class="notifications-icon-container">
          <img class="notifications-icon" src="icons/notifications.svg">
          <div class="notifications-count">3</div>
          <div class="tooltip">Notifications</div>
        </div>
        <img class="current-user-picture" src="channel-pictures/my-channel.jpeg">
      </div>
    </header>

    <nav class="sidebar">
      <div class="sidebar-link">
        <img src="icons/home.svg">
        <div>Home</div>
      </div>
      <div class="sidebar-link">
        <img src="icons/explore.svg">
        <div>Explore</div>
      </div>
      <div class="sidebar-link">
        <img src="icons/subscriptions.svg">
        <div>Subscriptions</div>
      </div>
      <div class="sidebar-link">
        <img src="icons/originals.svg">
        <div>Originals</div>
      </div>
      <div class="sidebar-link">
        <img src="icons/youtube-music.svg">
        <div>YouTube Music</div>
      </div>
      <div class="sidebar-link">
        <img src="icons/library.svg">
        <div>Library</div>
      </div>
    </nav>

    <main>
      <section class="video-grid">
        <div class="video-preview">
          <div class="thumbnail-row">
            <img class="thumbnail" src="thumbnails/thumbnail-1.webp">
            <div class="video-time">14:20</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <img class="profile-picture" src="channel-pictures/channel-1.jpeg">
            </div>
            <div class="video-info">
              <p class="video-title">
                Talking Tech and AI with Google CEO Sundar Pichai!
              </p>
              <p class="video-author">
                Marques Brownlee
              </p>
              <p class="video-stats">
                3.4M views &#183; 6 months ago
              </p>
            </div>
          </div>
        </div>

        <div class="video-preview">
          <div class="thumbnail-row">
            <img class="thumbnail" src="thumbnails/thumbnail-2.webp">
            <div class="video-time">8:22</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <img class="profile-picture" src="channel-pictures/channel-2.jpeg">
            </div>
            <div class="video-info">
              <p class="video-title">
                Try Not To Laugh Challenge #9
              </p>
              <p class="video-author">
                Markiplier
              </p>
              <p class="video-stats">
                19M views &#183; 4 years ago
              </p>
            </div>
          </div>
        </div>

        <div class="video-preview">
          <div class="thumbnail-row">
            <img class="thumbnail" src="thumbnails/thumbnail-3.webp">
            <div class="video-time">9:13</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <img class="profile-picture" src="channel-pictures/channel-3.jpeg">
            </div>
            <div class="video-info">
              <p class="video-title">
                Crazy Tik Toks Taken Moments Before DISASTER
              </p>
              <p class="video-author">
                SSSniperWolf
              </p>
              <p class="video-stats">
                12M views &#183; 1 year ago
              </p>
            </div>
          </div>
        </div>

        <div class="video-preview">
          <div class="thumbnail-row">
            <img class="thumbnail" src="thumbnails/thumbnail-4.webp">
            <div class="video-time">22:09</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <img class="profile-picture" src="channel-pictures/channel-4.jpeg">
            </div>
            <div class="video-info">
              <p class="video-title">
                The Simplest Math Problem No One Can Solve - Collatz Conjecture
              </p>
              <p class="video-author">
                Veritasium
              </p>
              <p class="video-stats">
                18M views &#183; 4 months ago
              </p>
            </div>
          </div>
        </div>

        <div class="video-preview">
          <div class="thumbnail-row">
            <img class="thumbnail" src="thumbnails/thumbnail-5.webp">
            <div class="video-time">11:17</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <img class="profile-picture" src="channel-pictures/channel-5.jpeg">
            </div>
            <div class="video-info">
              <p class="video-title">
                Kadane's Algorithm to Maximum Sum Subarray Problem
              </p>
              <p class="video-author">
                CS Dojo
              </p>
              <p class="video-stats">
                519K views &#183; 5 years ago
              </p>
            </div>
          </div>
        </div>

        <div class="video-preview">
          <div class="thumbnail-row">
            <img class="thumbnail" src="thumbnails/thumbnail-6.webp">
            <div class="video-time">19:59</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <img class="profile-picture" src="channel-pictures/channel-6.jpeg">
            </div>
            <div class="video-info">
              <p class="video-title">
                Anything You Can Fit In The Circle I’ll Pay For
              </p>
              <p class="video-author">
                MrBeast
              </p>
              <p class="video-stats">
                141M views &#183; 1 year ago
              </p>
            </div>
          </div>
        </div>

        <div class="video-preview">
          <div class="thumbnail-row">
            <img class="thumbnail" src="thumbnails/thumbnail-7.webp">
            <div class="video-time">10:13</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <img class="profile-picture" src="channel-pictures/channel-7.jpeg">
            </div>
            <div class="video-info">
              <p class="video-title">
                Why Planes Don't Fly Over Tibet
              </p>
              <p class="video-author">
                RealLifeLore
              </p>
              <p class="video-stats">
                6.6M views &#183; 1 year ago
              </p>
            </div>
          </div>
        </div>

        <div class="video-preview">
          <div class="thumbnail-row">
            <img class="thumbnail" src="thumbnails/thumbnail-8.webp">
            <div class="video-time">7:12</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <img class="profile-picture" src="channel-pictures/channel-8.jpeg">
            </div>
            <div class="video-info">
              <p class="video-title">
                Inside The World's Biggest Passenger Plane
              </p>
              <p class="video-author">
                Tech Vision
              </p>
              <p class="video-stats">
                3.7M views &#183; 10 months ago
              </p>
            </div>
          </div>
        </div>

        <div class="video-preview">
          <div class="thumbnail-row">
            <img class="thumbnail" src="thumbnails/thumbnail-9.webp">
            <div class="video-time">13:17</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <img class="profile-picture" src="channel-pictures/channel-9.jpeg">
            </div>
            <div class="video-info">
              <p class="video-title">
                The SECRET to Super Human STRENGTH
              </p>
              <p class="video-author">
                ThenX
              </p>
              <p class="video-stats">
                20M views &#183; 3 years ago
              </p>
            </div>
          </div>
        </div>

        <div class="video-preview">
          <div class="thumbnail-row">
            <img class="thumbnail" src="thumbnails/thumbnail-10.webp">
            <div class="video-time">7:53</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <img class="profile-picture" src="channel-pictures/channel-10.jpeg">
            </div>
            <div class="video-info">
              <p class="video-title">
                How The World's Largest Cruise Ship Makes 30,000 Meals Every Day
              </p>
              <p class="video-author">
                Business Insider
              </p>
              <p class="video-stats">
                14M views &#183; 1 year ago
              </p>
            </div>
          </div>
        </div>

        <div class="video-preview">
          <div class="thumbnail-row">
            <img class="thumbnail" src="thumbnails/thumbnail-11.webp">
            <div class="video-time">4:10</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <img class="profile-picture" src="channel-pictures/channel-11.jpeg">
            </div>
            <div class="video-info">
              <p class="video-title">
                Dubai's Crazy Underwater Train and Other Things #Only in Dubai
              </p>
              <p class="video-author">
                Destination Tips
              </p>
              <p class="video-stats">
                3M views &#183; 1 year ago
              </p>
            </div>
          </div>
        </div>

        <div class="video-preview">
          <div class="thumbnail-row">
            <img class="thumbnail" src="thumbnails/thumbnail-12.webp">
            <div class="video-time">4:51</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <img class="profile-picture" src="channel-pictures/channel-12.jpeg">
            </div>
            <div class="video-info">
              <p class="video-title">
                What would happen if you didn’t drink water? - Mia Nacamulli
              </p>
              <p class="video-author">
                TED-Ed
              </p>
              <p class="video-stats">
                12M views &#183; 5 years ago
              </p>
            </div>
          </div>
        </div>
      </section>
    </main>
  </body>
</html>
<!DOCTYPE html>
<html>
  <head>
    <title>Position Practice</title>
  </head>
  <body style="
    height: 3000px;
    padding-top: 60px;
    padding-left: 80px;
  ">
    <div style="
      background-color: black;
      color: white;
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      height: 50px;
      z-index: 100;
    ">header</div>

    <div style="
      background-color: green;
      color: white;
      position: fixed;
      left: 0;
      bottom: 0;
      top: 50px;
      width: 72px;
    ">
      sidebar
      <div style="
        position: absolute;
        background-color: red;
        color: white;
        top: 0;
        right: 0;
      ">
        X
      </div>
    </div>

    <div style="
      position: absolute;
      background-color: red;
      color: white;
      top: 60px;
      right: 10px;
    ">
      absolute
    </div>

    <div style="
      background-color: lightblue;
      height: 200px;
      width: 200px;
      position: static;
    ">div 1</div>
    <div style="
      background-color: lightpink;
      height: 200px;
      width: 200px;
      position: relative;
    ">
      div 2
      <div style="
        position: absolute;
        background-color: black;
        color: white;
        bottom: 10px;
        right: 10px;
      ">
        5:00
      </div>
    </div>

  </body>
</html>
<!DOCTYPE html>
<html>
  <head>
    <title>Grid Practice</title>
  </head>
  <body style="padding-bottom: 1000px;">
    <div style="
      display: grid;
      grid-template-columns: 100px 100px;
    ">
      <div style="background-color: lightblue;">div 1</div>
      <div style="background-color: lightpink;">div 2<p>text</p></div>
    </div>

    <div style="
      margin-top: 30px;
      display: grid;
      grid-template-columns: 100px 100px 200px;
    ">
      <div style="background-color: lightblue;">100px</div>
      <div style="background-color: lightpink;">100px<p>text</p></div>
      <div style="background-color: lightblue;">200px</div>
      <div style="background-color: lightpink;">100px</div>
    </div>

    <div style="
      margin-top: 30px;
      display: grid;
      grid-template-columns: 100px 1fr;
    ">
      <div style="background-color: lightblue;">100px</div>
      <div style="background-color: lightpink;">1fr</div>
    </div>

    <div style="
      margin-top: 30px;
      display: grid;
      grid-template-columns: 100px 1fr 2fr;
    ">
      <div style="background-color: lightblue;">100px</div>
      <div style="background-color: lightpink;">1fr</div>
      <div style="background-color: lightblue;">2fr</div>
    </div>

    <div style="
      margin-top: 30px;
      display: grid;
      grid-template-columns: 1fr 1fr 1fr;
      column-gap: 20px;
      row-gap: 40px;
    ">
      <div style="background-color: lightblue; height: 200px;">1fr</div>
      <div style="background-color: lightpink; height: 200px;">1fr</div>
      <div style="background-color: lightblue; height: 200px;">1fr</div>
      <div style="background-color: lightpink; height: 200px;">1fr</div>
      <div style="background-color: lightblue; height: 200px;">1fr</div>
      <div style="background-color: lightpink; height: 200px;">1fr</div>
    </div>
  </body>
</html>
<!DOCTYPE html>
<html>
  <head>
    <title>Flexbox Practice</title>
  </head>
  <body style="padding-bottom: 1000px;">
    <div style="
      display: flex;
      flex-direction: row;
    ">
      <div style="background-color: lightblue;">div 1 text</div>
      <div style="background-color: lightpink;">div 2 <p>text</p></div>
    </div>

    <div style="
      margin-top: 30px;
      display: flex;
      flex-direction: row;
    ">
      <div style="
        background-color: lightblue;
        width: 100px;
      ">100px</div>
      <div style="
        background-color: lightpink;
        flex: 1;
      ">flex: 1</div>
    </div>

    <div style="
      margin-top: 30px;
      display: flex;
      flex-direction: row;
    ">
      <div style="
        background-color: lightblue;
        flex: 1;
      ">flex: 1</div>
      <div style="
        background-color: lightpink;
        width: 100px;
      ">100px</div>
      <div style="
        background-color: lightblue;
        flex: 2;
      ">flex: 2</div>
    </div>

    <div style="
      margin-top: 30px;
      height: 70px;
      border-width: 1px;
      border-style: solid;
      border-color: gray;

      display: flex;
      flex-direction: row;
      justify-content: center;
    ">
      <div style="
        background-color: lightblue;
        width: 100px;
      ">100px</div>
      <div style="
        background-color: lightpink;
        width: 100px;
      ">100px</div>
      <div style="
        background-color: lightblue;
        width: 100px;
      ">100px</div>
    </div>

    <div style="
      margin-top: 30px;
      height: 70px;
      border-width: 1px;
      border-style: solid;
      border-color: gray;

      display: flex;
      flex-direction: row;
      justify-content: space-between;
    ">
      <div style="
        background-color: lightblue;
        width: 100px;
      ">100px</div>
      <div style="
        background-color: lightpink;
        width: 100px;
      ">100px</div>
      <div style="
        background-color: lightblue;
        width: 100px;
      ">100px</div>
    </div>

    <div style="
      margin-top: 30px;
      height: 70px;
      border-width: 1px;
      border-style: solid;
      border-color: gray;

      display: flex;
      flex-direction: row;
      justify-content: space-between;
      align-items: center;
    ">
      <div style="
        background-color: lightblue;
        width: 100px;
      ">100px</div>
      <div style="
        background-color: lightpink;
        width: 100px;
      ">100px</div>
      <div style="
        background-color: lightblue;
        width: 100px;
      ">100px</div>
    </div>
  </body>
</html>

