<!DOCTYPE html>
<html>
 <head>
   <meta charset="utf-8">
   <title>HTML Part 2 Lesson Three Hands On</title>
 </head>
 <body>
     <form>
         <label for="firstName">First Name:</label>
         <input type="text" id="firstName" name="firstName" placeholder="First Name:"/>
         <label for="lastName">Last Name:</label>
         <input type="text" id="lastName" name="lastName" placeholder="Last Name:"/>
         <button type="submit">Submit</button>

     </form>
     <h4>My Dream Developer Positions</h4>
     <form>
         <input type="radio" id="positionOne" name="position" value="fullStack" />
         <label for="fullStackDeveloper">Full Stack Developer</label><br>
         <input type="radio" id="positionTWo" name="position" value="frontEnd" />
         <label for="frontEndDeveloper">Front End Developer</label><br>
         <input type="radio" id="positionThree" name="position" value="backEnd" />
         <label for="backEndDeveloper">Back End Developer</label><br>
         <input type="radio" id="positionFour" name="position" value="junior" />
         <label for="juniorDeveloper">Junior Developer</label><br>
         <input type="submit" value="submit" />

     </form>
   
 </body>
</html>