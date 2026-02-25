<!DOCTYPE html>
<html>
<head>
  <title>Meme Generator</title>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js"></script>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background: #f4f4f4;
    }

    .controls {
      margin: 20px;
    }

    .meme-container {
      position: relative;
      display: inline-block;
      margin-top: 20px;
    }

    .meme-container img {
      max-width: 500px;
      max-height: 500px;
      display: block;
    }

    .text {
      position: absolute;
      left: 50%;
      transform: translateX(-50%);
      width: 90%;
      text-align: center;
      font-weight: bold;
      text-shadow: 2px 2px 5px black;
      word-wrap: break-word;
      cursor: move;
    }
