---
layout: default
---

## Page 2

_yay_

<p id="text"></p>

That is all I have to say.

[back](./)


<script>
var cars = ["Saab", "Volvo", "BMW", "Audi", "Kia", "VW"];
var randomindex = Math.floor(Math.random()*cars.length);
document.getElementById("text").innerHTML = cars[randomindex];
</script>
