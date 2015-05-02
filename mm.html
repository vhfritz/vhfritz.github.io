<html>
<head>
  <meta name=viewport content='width=750' />
  <style>
  body {
    background-image: url(wood.png);
    background-size: 100% 100%;
  }
  button {
    margin: 5px 20px;
    font-size: 20px;
    padding: 6px 12px;
  }
  img {
    height: 100px;
    width: 100px;
  }
  .die {
    width: 100px;
    height: 100px;
    transform-style: preserve-3d;
    transition: transform 0.5s;
    transition-timing-function: linear;
    display: inline-block;
    margin: 20px;
  }
  .die .side {
    position: absolute;
  }
  .die .side1 { transform: translateZ(50px); }
  .die .side2 { transform: rotateX(180deg) translateZ(50px); }
  .die .side3 { transform: rotateY(90deg) translateZ(50px); }
  .die .side4 { transform: rotateY(-90deg) translateZ(50px); }
  .die .side5 { transform: rotateX(90deg) translateZ(50px); }
  .die .side6 { transform: rotateX(-90deg) translateZ(50px); }

  .die.show-side1 { transform: translateZ(-50px); }
  .die.show-side2 { transform: translateZ(-50px) rotateX(-180deg); }
  .die.show-side3 { transform: translateZ(-50px) rotateY(-90deg); }
  .die.show-side4 { transform: translateZ(-50px) rotateY(90deg); }
  .die.show-side5 { transform: translateZ(-50px) rotateX(-90deg); }
  .die.show-side6 { transform: translateZ(-50px) rotateX(90deg); }

  </style>
</head>
<body>
<script>
function roll(numDice) {
  for (var i = 1; i < 6; i++) {
    var dieEl = document.getElementById("die" + i);
    if (i <= numDice) {
      dieEl.style.visibility = '';
      rollDie(dieEl);
    } else {
      dieEl.style.visibility = 'hidden';
    }
  }
}

// Rolls the given die element.
function rollDie(dieEl) {
    var currentSide = getCurrentSide(dieEl);
    for (var i = 1; i < 7; i++) {
      dieEl.classList.remove('show-side'+i);
    }
    var randomSide = Math.floor(Math.random() * 6) + 1;
    var otherSide = getDifferentSide(currentSide, randomSide);
    dieEl.classList.add('show-side'+otherSide);
    setTimeout(function () {
      dieEl.classList.remove('show-side'+otherSide);
      dieEl.classList.add('show-side'+randomSide);
    }, 550);
}

// Gets current side of the die.
function getCurrentSide(dieEl) {
  return dieEl.className[dieEl.className.length - 1];
}

// Returns a side that is not side1 or side 2.
function getDifferentSide(side1, side2) {
  var sides = [1, 2, 3, 4, 5, 6];
  var filteredSides = sides.filter(function(side) {
    return side != side1 && side != side2;
  });
  return filteredSides[Math.floor(Math.random() * 4)];
}
</script>
<button onclick="roll(1)">1</button>
<button onclick="roll(2)">2</button>
<button onclick="roll(3)">3</button>
<button onclick="roll(4)">4</button>
<button onclick="roll(5)">5</button>
<hr>
<div id="diceArea">
  <div class="die show-side1" id="die1">
    <div class="side side1"><img src="MMD1.png"/></div>
    <div class="side side2"><img src="MMD2.png"/></div>
    <div class="side side3"><img src="MMD3.png"/></div>
    <div class="side side4"><img src="MMD4.png"/></div>
    <div class="side side5"><img src="MMD5.png"/></div>
    <div class="side side6"><img src="MMD6.png"/></div>
  </div>
  <div class="die show-side2" id="die2">
    <div class="side side1"><img src="MMD1.png"/></div>
    <div class="side side2"><img src="MMD2.png"/></div>
    <div class="side side3"><img src="MMD3.png"/></div>
    <div class="side side4"><img src="MMD4.png"/></div>
    <div class="side side5"><img src="MMD5.png"/></div>
    <div class="side side6"><img src="MMD6.png"/></div>
  </div>
  <div class="die show-side3" id="die3">
    <div class="side side1"><img src="MMD1.png"/></div>
    <div class="side side2"><img src="MMD2.png"/></div>
    <div class="side side3"><img src="MMD3.png"/></div>
    <div class="side side4"><img src="MMD4.png"/></div>
    <div class="side side5"><img src="MMD5.png"/></div>
    <div class="side side6"><img src="MMD6.png"/></div>
  </div>
  <div class="die show-side4" id="die4">
    <div class="side side1"><img src="MMD1.png"/></div>
    <div class="side side2"><img src="MMD2.png"/></div>
    <div class="side side3"><img src="MMD3.png"/></div>
    <div class="side side4"><img src="MMD4.png"/></div>
    <div class="side side5"><img src="MMD5.png"/></div>
    <div class="side side6"><img src="MMD6.png"/></div>
  </div>
  <div class="die show-side5" id="die5">
    <div class="side side1"><img src="MMD1.png"/></div>
    <div class="side side2"><img src="MMD2.png"/></div>
    <div class="side side3"><img src="MMD3.png"/></div>
    <div class="side side4"><img src="MMD4.png"/></div>
    <div class="side side5"><img src="MMD5.png"/></div>
    <div class="side side6"><img src="MMD6.png"/></div>
  </div>
</div>
<script>
  var images = new Array();
  function preload() {
    for (var i = 1; i < 7; i++) {
      images[i] = new Image();
      images[i].src = "MMD"+i+".png";
    }
  }
  preload();
  roll(5);
</script>
</body>
</html>
