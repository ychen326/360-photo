# 360-photo
!DOCTYPE html
<html>
  <head>
    <meta charset="utf-8">
    <title>Union Station 360 Degree Photo • A-Frame</title>
    <meta name="description" content="Union Station 360 Degree Photo • A-Frame">
    <script src="https://aframe.io/releases/0.9.2/aframe.min.js"></script>
    <style>
      #gWidget {
        position: absolute;
        z-index: 99999;
        background: white;
        border-radius: 5px;
        right: 10px;
        top: 10px;
        padding: 5px;
      }
      
      #gWidget > p {
        margin: 0;
      }
    </style>
  </head>
  <body>
    <header id="gWidget"></header>
    <a-scene>
      <a-sky src="https://cdn.glitch.com/bdf3910f-12fa-4669-8c03-c6cef9690526%2F1.png?v=1599576385462"></a-sky>
    </a-scene>
    <script src="https://widget.glitch.me/widget.min.js"></script>
  </body>
</html>
