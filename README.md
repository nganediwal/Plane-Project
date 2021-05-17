# Plane-Project
var points;
points = 0;
var americanText = "";
var deltaText = "";
var easyjetText = "";
var lanText = "";
var lufthansaText = "";
var airfranceText = "";
var chinaeasternText = "";
var anaText = "";
var britishText = "";
var turkishText = "";
var southwestText = "";
var airchinaText = "";
var aircanadaText = "";
var unitedText = "";
var chinasouthernText = "";
var emiratesText = "";
var indigoText = "";
var ryanairText = "";
onEvent("planeCommercial", "click", function(event) {
  setScreen("commercialPlanes");
});
onEvent("planeCompany", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("button2", "click", function(event) {
  setScreen("homeScreen");
});
onEvent("button1", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("button23", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("button3", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("button4", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("button7", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("button5", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("button6", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("button8", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("button9", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("button10", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("button11", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("button12", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("button56", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("button12", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("button12", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("button13", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("button14", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("button15", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("button16", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("button17", "click", function(event) {
  setScreen("planelistScreen");
});
onEvent("planeGame", "click", function(event) {
  setScreen("gameScreen");
});
onEvent("button62", "click", function(event) {
  setScreen("americanQuestion");
});
onEvent("americanAirlines", "click", function(event) {
  setScreen("americanScreen");
});
onEvent("deltaButton", "click", function(event) {
  setScreen("deltaScreen");
});
onEvent("southwestButton", "click", function(event) {
  setScreen("southwestScreen");
});
onEvent("unitedButton", "click", function(event) {
  setScreen("unitedScreen");
});
onEvent("RyanAirButton", "click", function(event) {
  setScreen("ryanairScreen");
});
onEvent("chinaSouthernButton", "click", function(event) {
  setScreen("chinasouthernScreen");
});
onEvent("chinaEasternButton", "click", function(event) {
  setScreen("chinaeasternScreen");
});
onEvent("easyJet", "click", function(event) {
  setScreen("easyjetScreen");
});
onEvent("TurkishButton", "click", function(event) {
  setScreen("turkishScreen");
});
onEvent("airChinaButton", "click", function(event) {
  setScreen("airchinaScreen");
});
onEvent("lufthansaButton", "click", function(event) {
  setScreen("lufthansaScreen");
});
onEvent("emiratesButton", "click", function(event) {
  setScreen("emiratesScreen");
});
onEvent("IndigoButton", "click", function(event) {
  setScreen("indigoScreen");
});
onEvent("allNiponButton", "click", function(event) {
  setScreen("anaScreen");
});
onEvent("lanButton", "click", function(event) {
  setScreen("lanScreen");
});
onEvent("airCanadaButton", "click", function(event) {
  setScreen("aircanadaScreen");
});
onEvent("britishAirwaysButton", "click", function(event) {
  setScreen("britishScreen");
});
onEvent("airFranceButton", "click", function(event) {
  setScreen("airfranceScreen");
});
onEvent("planeGame", "click", function(event) {
  setScreen("gameScreen");
});
onEvent("button26", "click", function(event) {
  setScreen("AirbusA320");
});
onEvent("button27", "click", function(event) {
  setScreen("Boeing737");
});
onEvent("button28", "click", function(event) {
  setScreen("boeing777");
});
onEvent("button29", "click", function(event) {
  setScreen("EmbraerERJ");
});
onEvent("button44", "click", function(event) {
  setScreen("AirbusA330");
});
onEvent("button63", "click", function(event) {
  setScreen("BombardierCRJ");
});
onEvent("button64", "click", function(event) {
  setScreen("boeing767");
});
onEvent("button65", "click", function(event) {
  setScreen("Boeing787");
});
onEvent("button66", "click", function(event) {
  setScreen("EmbraerE-170");
});
onEvent("button67", "click", function(event) {
  setScreen("Boeing747");
});
onEvent("button71", "click", function(event) {
  setScreen("commercialPlanes");
});
onEvent("button72", "click", function(event) {
  setScreen("commercialPlanes");
});
onEvent("button73", "click", function(event) {
  setScreen("commercialPlanes");
});
onEvent("button74", "click", function(event) {
  setScreen("commercialPlanes");
});
onEvent("button75", "click", function(event) {
  setScreen("commercialPlanes");
});
onEvent("button76", "click", function(event) {
  setScreen("commercialPlanes");
});
onEvent("button77", "click", function(event) {
  setScreen("commercialPlanes");
});
onEvent("button78", "click", function(event) {
  setScreen("commercialPlanes");
});
onEvent("button79", "click", function(event) {
  setScreen("commercialPlanes");
});
onEvent("button80", "click", function(event) {
  setScreen("commercialPlanes");
});
onEvent("button81", "click", function(event) {
  setScreen("homeScreen");
});
// i got this image from Google Images 
function addPoint() {
  setScreen("correctScreen");
  points = points + 1;
  setText("label30", "Points: " + points);
  setImageURL("image71", "https://i.pinimg.com/originals/fb/94/ec/fb94ecf0a9973eb02b5e0977130e23b3.jpg");
}
onEvent("button18", "click", function(event) {
  americanText = getText("americanInput");
  if ((americanText.toLowerCase().includes("american"))) {
    addPoint();
    onEvent("button69", "click", function(event) {
      setScreen("deltaQuestion");
    });
  } else {
    setScreen("wrongScreen");
    onEvent("button70", "click", function(event) {
      setScreen("deltaQuestion");
    });
  }
});
onEvent("button19", "click", function(event) {
  deltaText = getText("deltaInput");
  if ((deltaText.toLowerCase().includes("delta"))) {
    addPoint();
    onEvent("button69", "click", function(event) {
      setScreen("easyjetQuestion");
    });
  } else {
    setScreen("wrongScreen");
    onEvent("button70", "click", function(event) {
      setScreen("easyjetQuestion");
    });
  }
});
onEvent("button25", "click", function(event) {
  easyjetText = getText("easyjetInput");
  if ((easyjetText.toLowerCase().includes("easyjet"))) {
    addPoint();
    onEvent("button69", "click", function(event) {
      setScreen("lanQuestion");
    });
  } else {
    setScreen("wrongScreen");
    onEvent("button70", "click", function(event) {
      setScreen("lanQuestion");
    });
  }
});
onEvent("button33", "click", function(event) {
  lanText = getText("lanInput");
  if ((lanText.toLowerCase().includes("lan")) || lanText.toLowerCase().includes("latam")) {
    addPoint();
    onEvent("button69", "click", function(event) {
      setScreen("lufthansaQuestion");
    });
  } else {
    setScreen("wrongScreen");
    onEvent("button70", "click", function(event) {
      setScreen("lufthansaQuestion");
    });
  }
});
onEvent("button53", "click", function(event) {
  lufthansaText = getText("lufthansaInput");
  if ((lufthansaText.toLowerCase().includes("lufthansa"))) {
    addPoint();
    onEvent("button69", "click", function(event) {
      setScreen("airfranceQuestion");
    });
  } else {
    setScreen("wrongScreen");
    onEvent("button70", "click", function(event) {
      setScreen("airfranceQuestion");
    });
  }
});
onEvent("button36", "click", function(event) {
  airfranceText = getText("airfranceInput");
  if ((airfranceText.toLowerCase().includes("france"))) {
    addPoint();
    onEvent("button69", "click", function(event) {
      setScreen("chinaeasternQuestion");
    });
  } else {
    setScreen("wrongScreen");
    onEvent("button70", "click", function(event) {
      setScreen("chinaeasternQuestion");
    });
  }
});
onEvent("button24", "click", function(event) {
  chinaeasternText = getText("chinaeasternInput");
  if ((chinaeasternText.toLowerCase().includes("eastern"))) {
    addPoint();
    onEvent("button69", "click", function(event) {
      setScreen("anaQuestion");
    });
  } else {
    setScreen("wrongScreen");
    onEvent("button70", "click", function(event) {
      setScreen("anaQuestion");
    });
  }
});
onEvent("button32", "click", function(event) {
  anaText = getText("anaInput");
  if ((anaText.toLowerCase().includes("ana"))) {
    addPoint();
    onEvent("button69", "click", function(event) {
      setScreen("britishQuestion");
    });
  } else {
    setScreen("wrongScreen");
    onEvent("button70", "click", function(event) {
      setScreen("britishQuestion");
    });
  }
});
onEvent("button35", "click", function(event) {
  britishText = getText("britishInput");
  if ((britishText.toLowerCase().includes("british"))) {
    addPoint();
    onEvent("button69", "click", function(event) {
      setScreen("turkishQuestion");
    });
  } else {
    setScreen("wrongScreen");
    onEvent("button70", "click", function(event) {
      setScreen("turkishQuestion");
    });
  }
});
onEvent("button48", "click", function(event) {
  turkishText = getText("turkishInput");
  if ((turkishText.toLowerCase().includes("turkish"))) {
    addPoint();
    onEvent("button69", "click", function(event) {
      setScreen("southwestQuestion");
    });
  } else {
    setScreen("wrongScreen");
    onEvent("button70", "click", function(event) {
      setScreen("southwestQuestion");
    });
  }
});
onEvent("button20", "click", function(event) {
  southwestText = getText("southwestInput");
  if ((southwestText.toLowerCase().includes("southwest"))) {
    addPoint();
    onEvent("button69", "click", function(event) {
      setScreen("airchinaQuestion");
    });
  } else {
    setScreen("wrongScreen");
    onEvent("button70", "click", function(event) {
      setScreen("airchinaQuestion");
    });
  }
});
onEvent("button51", "click", function(event) {
  airchinaText = getText("airchinaInput");
  if ((airchinaText.toLowerCase().includes("china"))) {
    addPoint();
    onEvent("button69", "click", function(event) {
      setScreen("aircanadaQuestion");
    });
  } else {
    setScreen("wrongScreen");
    onEvent("button70", "click", function(event) {
      setScreen("aircanadaQuestion");
    });
  }
});
onEvent("button34", "click", function(event) {
  aircanadaText = getText("aircanadaInput");
  if (aircanadaText.toLowerCase().includes("canada")) {
    addPoint();
    onEvent("button69", "click", function(event) {
      setScreen("unitedQuestion");
    });
  } else {
    setScreen("wrongScreen");
    onEvent("button70", "click", function(event) {
      setScreen("unitedQuestion");
    });
  }
});
onEvent("button21", "click", function(event) {
  unitedText = getText("unitedInput");
  if ((unitedText.toLowerCase().includes("united"))) {
    addPoint();
    onEvent("button69", "click", function(event) {
      setScreen("chinasouthernQuestion");
    });
  } else {
    setScreen("wrongScreen");
    onEvent("button70", "click", function(event) {
      setScreen("chinasouthernQuestion");
    });
  }
});
onEvent("button46", "click", function(event) {
  chinasouthernText = getText("chinasouthernInput");
  if ((chinasouthernText.toLowerCase().includes("southern"))) {
    addPoint();
    onEvent("button69", "click", function(event) {
      setScreen("emiratesQuestion");
    });
  } else {
    onEvent("button70", "click", function(event) {
      setScreen("emiratesQuestion");
    });
  }
});
onEvent("button30", "click", function(event) {
  emiratesText = getText("emiratesInput");
  if ((emiratesText.toLowerCase().includes("emirates"))) {
    addPoint();
    onEvent("button69", "click", function(event) {
      setScreen("indigoQuestion");
    });
  } else {
    setScreen("wrongScreen");
    onEvent("button70", "click", function(event) {
      setScreen("indigoQuestion");
    });
  }
});
onEvent("button31", "click", function(event) {
  indigoText = getText("indigoInput");
  if ((indigoText.toLowerCase().includes("indigo"))) {
    addPoint();
    onEvent("button69", "click", function(event) {
      setScreen("ryanairQuestion");
    });
  } else {
    setScreen("wrongScreen");
    onEvent("button70", "click", function(event) {
      setScreen("ryanairQuestion");
    });
  }
});
onEvent("button22", "click", function(event) {
  ryanairText = getText("ryanairInput");
  if ((ryanairText.toLowerCase().includes("ryanair"))) {
    addPoint();
    onEvent("button69", "click", function(event) {
      setScreen("endScreen");
    });
  } else {
    setScreen("wrongScreen");
    onEvent("button70", "click", function(event) {
      setScreen("endScreen");
    });
  }
});
function doublePoints() {
  if (ryanairText.toLowerCase().includes("ryanair")) {
    points = points + 2;
  } else if (chinasouthernText.toLowerCase().includes("southern")) {
    points = points + 2;
  } else if (indigoText.toLowerCase().includes("indigo")) {
    points = points + 2;
  }
}
// i got these images from wikimedia
function endScreen() {
  setText("label29", points);
  if (points >= 13) {
    setText("textArea", "You are an airline genius!");
    if (points >= 15) {
      setImageURL("image", "https://upload.wikimedia.org/wikipedia/commons/thumb/6/65/Royal_Crown_of_France.svg/2000px-Royal_Crown_of_France.svg.png");
    } else {
      setImageURL("image", "https://upload.wikimedia.org/wikipedia/commons/thumb/8/81/Crown_of_Italy.svg/1200px-Crown_of_Italy.svg.png");
    }
  } else if ((points >= 8)) {
    if (points >= 12) {
      setText("textArea", "Not bad!");
      setImageURL("image", "https://upload.wikimedia.org/wikipedia/commons/thumb/8/81/Crown_of_Italy.svg/1200px-Crown_of_Italy.svg.png");
    } else {
      setImageURL("image", "https://upload.wikimedia.org/wikipedia/commons/thumb/8/81/Crown_of_Italy.svg/1200px-Crown_of_Italy.svg.png");
    }
  } else {
    setText("textArea", "Unfortunately you didn't do that well, good try though!");
    setImageURL("image", "https://d21ii91i3y6o6h.cloudfront.net/gallery_images/from_proof/6564/large/1438016188/king-shit.png");
  }
}
endScreen();
