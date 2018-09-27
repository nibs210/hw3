# hw3
P&amp;E Homework 3
What code draws the blades of grass?

  stroke(random(60, 70), 100, 90);
  line(x, height-10, x + random(-10, 10), height-10-random(h));

What code makes the "lawnmower" come by? How often does it come by?

 if (random() > 0.999) {
    noStroke();
    fill(255);
    rect(-1, -1, width+2, height-15);
    h = 10;
    It is randomly chosen based on a chance every cycle

What's the point of the h variable?

the h variable determines the length of the blades of grass

What do the three numerical arguments of colorMode do?

converts HSB to RGB

What does the -10 do in the second and fourth arguments of the line function, height-10-random(h)? Why is it there?

it determines the location of the brown rectangle that makes up the "dirt"
