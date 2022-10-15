# Frontend-Challenges

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">

  <title>Frontend Mentor | Notifications page</title>

  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>
    @font-face {
      font-family: fontFirst;
      src: url(../notifications-page-main/assets/fonts/PlusJakartaSans-VariableFont_wght.ttf);
    }

    @font-face {
      font-family: fontBold;
      src: url(../notifications-page-main/assets/fonts/static/PlusJakartaSans-ExtraBold.ttf);
    }

    @font-face {
      font-family: fontSecond;
      src: url(../notifications-page-main/assets/fonts/static/PlusJakartaSans-Medium.ttf);
    }


    body {
      font-family: fontSecond;
      margin: 0;
      min-height: 100vh;
      position: absolute;
      background: hsl(211, 68%, 94%);
      font-size: 16px;
      padding-left: 225px;
      padding-right: 225px;
      padding-top: 50px;
      padding-bottom: 70px;

    }

    .notifications-container {
      align-items: center;
      display: flex;
      justify-content: space-between;
      

    }

    .container-notpos {
      padding-top: 15px;
      background-color: hsl(0, 0%, 100%);
      

    }

    .notifications-right {
      display: flex;
      padding-right: 15px;
      color: hsl(219, 12%, 42%);

    }

    .notifications {
      display: flex;
      align-items: center;
      font-family: fontBold;
      font-size: 20px;


    }

    .notifications>* {
      margin: 10px;
    }

    .post-blue img {
      margin-right: 50px;
      height: 70px;
      width: 70px;
      align-items: center;
      position: relative;
      

    }
    .post{
      display: flex;
      margin-top: 20px;
      display: inline-flex;
      padding: 20px;

    }
    .post img{
      margin-right: 50px;
      height: 70px;
      width: 70px;
      align-items: center;
    }

    .maintext {
      margin-top: 25px;
      width: 550px;
    }

    .post-blue {
      display: flex;
      margin-top: 20px;
      background-color: hsl(210, 60%, 98%);
      padding: 20px;
    }

    .post-timestamp {
      font-family: fontFirst;
      color: hsl(218, 5%, 70%);
      
    }

    .title {
      font-family: fontBold;
      margin-right: 5px;
      color: hsl(224, 21%, 14%);
      
    }

    .post-container {
      padding-bottom: 50px;
    }

    .main {
      display: flex;
    }

    .notpos {
      margin-left: 50px;
      margin-right: 50px;
    }

    .txt {
      color: hsl(219, 14%, 63%);
    }

    .StrongBlue {
      color: hsl(219, 12%, 42%);
      margin-left: 5px;
    }
    .StrongBlueB{
      font-family: fontBold;
      color:hsl(219, 85%, 26%);
      margin-left: 5px;
    }

    .dot {
      height: 8px;
      width: 8px;
      background-color: rgb(232, 89, 89);
      border-radius: 50%;
      margin-top: 8px;
      margin-left: 5px;
    }
    .subpost{
      border-color: hsl(219, 14%, 63%);
      border-style: solid;
      padding: 10px;
      margin-top: 15px;
      color: hsl(219, 14%, 63%);
      
    }
    .number{
      background-color: hsl(219, 85%, 26%);
      width: 30px;
      border-radius: 5px;
      text-align: center;
      color: white;
    }
    .maintext img{
      float:right;
      position: relative;
      top: -20px;
      right: -50px;
    }
  </style>
</head>

<body>

  <div class="container-notpos">
    <div class="notpos">
      <div class="notifications-container">
        <div class="notifications">
          <div>Notifications</div>

          <div class="number">3</div>
        </div>
        <div class="notifications-right">
          Mark all as read
        </div>

      </div>
      <div class="post-container">
        <div class="post-blue">
          <img src="../notifications-page-main/assets/images/avatar-mark-webber.webp" alt="MarkImage">

          <div class="maintext">
            <div class="main">
              <div class="title">Mark Webber</div>
              <div class="txt"> reacted to your recent post </div>
              <strong>
                <div class="StrongBlue">My first tournament today!</div>
              </strong>
              <span class="dot"></span>
            </div>
            <div class="post-timestamp">1m ago </div>
          </div>


        </div>
        <div class="post-blue">
          <img src="../notifications-page-main/assets/images/avatar-angela-gray.webp" alt="MarkImage">

          <div class="maintext">
            <div class="main">
              <div class="title">Angela Gray</div>
              <div class="txt">  followed you  </div>
              <strong>
                <div class="StrongBlue"></div>
              </strong>
              <span class="dot"></span>
            </div>
            <div class="post-timestamp">5m ago </div>
          </div>


        </div>
        <div class="post-blue">
          <img src="../notifications-page-main/assets/images/avatar-jacob-thompson.webp" alt="MarkImage">

          <div class="maintext">
            <div class="main">
              <div class="title">Jacob Thompson</div>
              <div class="txt"> has joined your group  </div>
              <strong>
                <div class="StrongBlueB"> Chess Club</div>
              </strong>
              <span class="dot"></span>
            </div>
            <div class="post-timestamp">1 day ago </div>
          </div>


        </div>
        <div class="post">
          <img src="../notifications-page-main/assets/images/avatar-rizky-hasanuddin.webp" alt="MarkImage">

          <div class="maintext">
            <div class="main">
              <div class="title">Rizky Hasanuddin</div>
              <div class="txt">  sent you a private message   </div>
              <strong>
                <div class="StrongBlue"> </div>
              </strong>
              
            </div>
            <div class="post-timestamp">5 days ago </div>
            <div class="subpost">
              Hello, thanks for setting up the Chess Club. I've been a member for 
              a few weeks now and I'm already having lots of fun and improving my game.
            </div>
          </div>


        </div>
        <div class="post">
          <img src="../notifications-page-main/assets/images/avatar-kimberly-smith.webp" alt="MarkImage">

          <div class="maintext">
            <div class="main">
              <div class="title">Kimberly Smithn</div>
              <div class="txt">   commented on your picture    </div>
              
              
              
            </div>
            <img src="../notifications-page-main/assets/images/image-chess.webp" alt="">
            <div class="post-timestamp">1 week ago </div>
          </div>


        </div>
        <div class="post">
          <img src="../notifications-page-main/assets/images/avatar-nathan-peterson.webp" alt="MarkImage">

          <div class="maintext">
            <div class="main">
              <div class="title">Nathan Peterson</div>
              <div class="txt">reacted to your recent post </div>
              <strong>
                <div class="StrongBlue">
                  5 end-game strategies to
                </div>
              </strong>
              
            </div>
            <strong>
            <div class="StrongBlue"> increase your win rate</div>
            </strong>
            <div class="post-timestamp">2 weeks ago</div>
          </div>


        </div>
        <div class="post">
          <img src="../notifications-page-main/assets/images/avatar-anna-kim.webp" alt="MarkImage">

          <div class="maintext">
            <div class="main">
              <div class="title">Anna Kim</div>
              <div class="txt"> left the group      </div>
              <strong>
                <div class="StrongBlueB"> Chess Club</div>
              </strong>
              
            </div>
            <div class="post-timestamp">2 weeks ago</div>
          </div>


        </div>
      </div>
      

    </div>


    <!-- Notifications 3 
  Mark all as read Mark Webber reacted to your recent post My first tournament today!
 1m ago 
 Angela Gray followed you 5m ago 
 Jacob Thompson has joined your group Chess Club 1 day ago 
 Rizky Hasanuddin sent you a private message 5 days ago 
 Hello, thanks for setting up the Chess Club. 
 I've been a member for a few weeks now and I'm already having lots of fun and improving my game. 
 Kimberly Smith commented on your picture 1 week ago 
 Nathan Peterson reacted to your recent post 5 end-game strategies to increase your win rate 2 weeks ago 
 Anna Kim left the group Chess Club 2 weeks ago -->
    <!-- <div class="attribution">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
      Coded by <a href="#">Your Name Here</a>.
    </div> -->
</body>

</html>
