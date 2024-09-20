hi tol so basically note lang to pero medyo mahaba siya tapos baka di umabot sa messenger. wag mo tong ipasa ha baka ito mapasa mo to HAHAHAH


EXPLAINING THE PROCESS 
- the part where we had most fun at was when we were making the css and deciding on what our concept would be. we conceptualized on making either pong or a puzzle game, but we figured a good challenge would be focusing on generations and how we can apply it to our actual work.
- we also had the most ease in making the basic framework of the work, such as the css and the html. the main thing we had spent most time on was of course, the java itself.
- as simple as the game looks, the generation behind the maze is what took us the most time. (585 lines total) 


HOW THE JAVASCRIPT WORKS IN FISH FIND
-  the crucial part includes three major functions: rand(max) generates a random number between 0 and max, shuffle(a) randomly shuffles the elements of an array using an algorithm, and changeBrightness(factor, sprite) adjusts the brightness of an image. the changeBrightness function creates a virtual canvas, draws an image onto it, modifies the brightness by adjusting the rgb color components based on a factor, and returns a new image with the updated brightness. the code leverages canvas manipulation and random number generation for tasks involving image processing and array handling. basically, the algorithm is dependent on the difficulty of generation and the generated integers are then translated as image data. 


THE DIFFICULTIES
- figuring out the usage of math.floor and how to properly define and tweak the values in accordance to difficulty
-  line 104, figuring out function defineMaze(), that generates a maze using a "depth-first" search algorithm. it initializes several variables to track the maze's progress, including the current position, the number of cells visited, and the maximum number of loops allowed before shuffling directions. the function marks the current cell as visited and attempts to move in each possible direction, carving paths between cells. if a new cell is reached, it updates the position and recursively continues the process. if no new cells can be visited, it backtracks to the previous cell. the process continues until all cells in the maze are visited.