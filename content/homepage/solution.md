---
title: ''
weight: 6
header_menu: true
header_background: '#FEE9FB'
---

{{< rawhtml >}}
<style>
/* FEE9FB, FFE4FA */
html, body {
    height: 100%;
    margin: 0;
}
#videowrapper{
    position: relative;
    overflow: hidden;
}

#fullScreenDiv{
    min-height: 100%;
    height: 100vh;
    width: 100vw;
    padding:0;
    margin: 0;
    background-color: gray;
    position: relative;
}

#video{
    width: 100vw;
    height: auto;
    margin: auto;
    display: block;
}
@media (min-aspect-ratio: 16/9) {
  #video{
    width: 100vw;
    height:auto;
  }
}

@media (max-aspect-ratio: 16/9) {
  #video {
    height: 100vh;
    width:auto;
    margin-left: 50vw;
    transform: translate(-50%);
  }
}

#videoMessage{
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    left: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
</style>
  <div id="videowrapper">
    <div class="container">
      <div id="fullScreenDiv">
        <video id="video" role="presentation" preload="auto" playsinline="" crossorigin="anonymous" loop="" muted="" autoplay="" class="blur">
          <source src="images/production_ID_4838265.mp4" type="video/mp4">
        </video>
        <div id="videoMessage" class="styling">
          <div id="site-head-content" class="inner" style="color: white">
            <h1 style="font-size: 400%">Features</h1>
          </div>
        </div>
      </div>
    </div>
  </div>
{{< /rawhtml >}}
