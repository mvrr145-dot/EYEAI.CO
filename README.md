<!DOCTYPE html>
<html>
<head>

<meta name="viewport" content="width=device-width, initial-scale=1">

<script type="module"
src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js">
</script>

<style>

body{
background:black;
color:white;
font-family:sans-serif;
text-align:center;
margin:0;
}

h1{
font-size:40px;
letter-spacing:4px;
margin-top:20px;
}

button{
padding:12px 20px;
margin:8px;
border:none;
border-radius:20px;
background:#00f0ff;
color:black;
font-weight:bold;
}

</style>

</head>

<body>

<h1>EYEAI.CO</h1>
<p>Futuristic AR Robots</p>

<button onclick="r1()">CYBERION</button>
<button onclick="r2()">NEO-X</button>
<button onclick="r3()">MECHA CORE</button>
<button onclick="r4()">QUANTEX</button>
<button onclick="r5()">AURORA BOT</button>
<button onclick="r6()">META DRONE</button>

<model-viewer
id="viewer"
src="https://modelviewer.dev/shared-assets/models/RobotExpressive.glb"
ios-src="https://modelviewer.dev/shared-assets/models/RobotExpressive.usdz"
ar
ar-modes="scene-viewer webxr quick-look"
camera-controls
auto-rotate
shadow-intensity="1"
style="width:100%; height:70vh;">
</model-viewer>

<script>

function r1(){
document.getElementById("viewer").src="https://modelviewer.dev/shared-assets/models/RobotExpressive.glb";
document.getElementById("viewer").setAttribute("ios-src","https://modelviewer.dev/shared-assets/models/RobotExpressive.usdz");
}

function r2(){
document.getElementById("viewer").src="https://modelviewer.dev/shared-assets/models/RobotExpressive.glb";
document.getElementById("viewer").setAttribute("ios-src","https://modelviewer.dev/shared-assets/models/RobotExpressive.usdz");
}

function r3(){
document.getElementById("viewer").src="https://modelviewer.dev/shared-assets/models/RobotExpressive.glb";
document.getElementById("viewer").setAttribute("ios-src","https://modelviewer.dev/shared-assets/models/RobotExpressive.usdz");
}

function r4(){
document.getElementById("viewer").src="https://modelviewer.dev/shared-assets/models/RobotExpressive.glb";
document.getElementById("viewer").setAttribute("ios-src","https://modelviewer.dev/shared-assets/models/RobotExpressive.usdz");
}

function r5(){
document.getElementById("viewer").src="https://modelviewer.dev/shared-assets/models/RobotExpressive.glb";
document.getElementById("viewer").setAttribute("ios-src","https://modelviewer.dev/shared-assets/models/RobotExpressive.usdz");
}

function r6(){
document.getElementById("viewer").src="https://modelviewer.dev/shared-assets/models/RobotExpressive.glb";
document.getElementById("viewer").setAttribute("ios-src","https://modelviewer.dev/shared-assets/models/RobotExpressive.usdz");
}

</script>

</body>
</html>