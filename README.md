# tliu0420_9103_major-project
Tianang Liu_User Input

1. Move the mouse on the screen to move the flower. Click the mouse to add a new flower at the current position of the mouse. You can also press the "number 1-7" button to switch different flowers. The flower style displayed when you click the mouse is the style of the added flower. Users can add the type of flowers they like at any position in the canvas according to their preferences.
2. I chose "User Input: Incorporate mouse or keyboard inputs for animation." to strengthen the original code. In the code I modified, I first modified the flower to be able to move according to the mouse position, and it will be displayed in real time. In addition, in our group work, we designed 7 different types of flowers. I bound these 7 flowers to the buttons of the numbers "1-7", and users can press these keys to switch the types of flowers. When the user clicks the mouse, a new flower will be added to the current mouse position, and the style of the flower is the style of the "number 1-7" selected by the user. The default style is the style of the flower associated with "number 1". Because I want the mouse to add flowers, I used "function addFlower()" and "function mousePressed()" in my code. In addition, I also used "function keyPressed()" to bind the 7 types of flowers to the "number 1-7" buttons. And I also used "function mouseMoved()" to bind the flower position coordinates to the real-time XY coordinates of the mouse, so that the flowers will move with the mouse.

Reference：

KeyPressed. (n. d.). P5.JS. Reference keyPressed().
reference | keyPressed() (p5js.org)

MousePressed. (n. d.). P5.JS. Reference mousePressed().
reference | mousePressed() (p5js.org)

MouseMoved. (n. d.). P5.JS. Reference mouseMoved().
reference | mouseMoved() (p5js.org)