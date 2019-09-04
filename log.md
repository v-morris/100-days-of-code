# 100 Days Of Code - Log

### Day 7: September 3, 2019 

**Today's Progress**: Watched 2 Egghead videos about TypeScript. I did a bit of practice with it, just exploring types/using DOM elements. Learned about how to use interfaces/classes as well. 

**Thoughts:** I'm really excited to work with TypeScript more! It seems like a great way to practice structuring my code better. It reminds me a lot of Java. It's going to be a difficult transition, because I remember how much I struggled trying to go from JS to Java in the beginning! Took me a minute to get used to using types. But I love the structure. It's more code, but I really think it helps your code come together better in the end.

**Sources:**  Egghead.io

### Day 6: September 2, 2019 

**Today's Progress**: Finished Section 4 of the Advanced JavaScript Concepts Udemy Course. Topics included - 
* Primitive vs Non-Primitive Data types in JS
* Undefined - absence of a definition, Null - absence of a value
* Array.isArray() to check for array type because typeof will only show you that an array is an object
* Pass by Reference vs Pass by Value - objects are pass by reference, pointing to a specific place in memory. Primitive data types are pass by value and contain their own seperate places in memory, rather than point to one location.
* How to clone an object or array so prevent any issues caused by pass by reference
* Object.assign(), spread operator for shallow clones (one layer)
* JSON.parse(JSON.stringify()) for deep cloning -- but this can cause performance issues if the object is large
* Type Coersion when using a double equals sign
* Object.is for comparison
* Static typing in JS using FLow, Elm, ReasonML, or TypeScript

**Thoughts:** A little review again, but refreshed a lot of knowledge on pass by reference vs pass by value and how to deep clone. I looked up some info and it seems like that can get pretty complex. I'm excited to be on to Section 5 because it contains a lot of completely new knowledge, so I'm looking forward to learning it all. I'd also like to maybe start including some TypeScript in my work and maybe run through an Egghead course to get a quick idea of it. I've used it a tiny bit in the past, but mostly forget it. I've noticed a lot of employers want TypeScript, so it's on my list to review. I may work on an algorithm tonight as well, or at least review the Check Permutations algorithm.

**Sources:**  Advanced JavaScript Concepts - Andrei Neagoie Udemy Course

### Day 5: September 1, 2019 

**Today's Progress**: Finished Section 3 of the Advanced JavaScript Concepts Udemy course. A little review, but learned some things a lot more in depth. Todays topics included -
* Leakage of global variables - 'use strict' prevents this from happening
* Function Scope vs Block Scope - var is function scoped, Example: can be accessed outside of if/for loop, let and const are block scoped and can only be accessed inside a block of code
* Variable collision and why it is important to not pollute the global environment with variables. Other script files will overwrite each other if there are variables of the same name.
* IIFE - Immediately Invoked Function Expression, help to prevent variable collision by creating a local environment.
* 'this' keyword - the object that the function is a property of, gives methods access to their object and also can execute same code for multiple objects. The 'this' keyword is dynamically scoped rather than lexically scope (this is fixed by either using an arrow function or .bind(this). You can also create a reference to 'this' by creating a variable in the obj you are referencing.
* call(), apply(), bind() - call and apply both borrow methods from objects, bind stores a method to be used later
* Function currying - uses bind() to give partial parameters (first parameter) to other functions
* context vs scope

**Thoughts:** These are topics I've covered a little in the past but they never sunk in completely. I'm taking a lot of notes to hopefully help me remember better. It's already a lot easier to understand this now with a year of coding under my belt. When I tried to understand these topics previously, it was more difficult to understand them without much knowledge. So outside of taking notes, I think just having more overall knowledge is helping it sink in more easily.

**Sources:**  Advanced JavaScript Concepts - Andrei Neagoie Udemy Course


### Day 4: August 31, 2019 

**Today's Progress**: Worked on the check permutations algorithm and practiced using Maps in JavaScript. Read about the various Map methods and how to use them

**Thoughts:** I feel like I'm pretty close to a good solution, but I might have used too many for loops and also feel like I didn't follow the DRY principle as well as I should have.. I will check for solutions tomorrow and compare to what I got. But I believe my solution works from what I can tell. It's late though so I will double check after a night of rest! 

**Sources:**  
https://www.geeksforgeeks.org/map-has-in-javascript/<br/>
https://2ality.com/2015/01/es6-maps-sets.html

**Links:** [Check Permutations](https://repl.it/@digidarkdev/Check-Permutation "Check Permutations")


### Day 3: August 30, 2019 

**Today's Progress**: I continued Andrei Neagoie's Advanced JavaScript Concepts Udemy course. Topics covered today include -
* Execution Context - JS engine creates global() execution context. Access to Global object(window) and "this" keyword
* Lexical Environment - every time we create an execution context, a new lexical environment is created.
* Hoisting - only var and function declaration get hoisted
* Function Invocation - access to "this" keyword and "arguments" keyword (which is an object)
* Array.from() turns arguments into an array. Can also use rest parameters
* Variable environments
* Scope Chain - each execution context has a connection to its parent

I also began another algorithm from Cracking the Coding Interview. I'm learning about creating a Map to check for permutations of a string. Have not solved it yet and need to look into comparing Maps. I did solve it one way, which involved sorting the string and comparing, but it is not the most optimized way.

**Thoughts:** Some of the topics covered today were review because I do know a lot of this stuff, and I use a lot of these concepts. I think I just forget what a lot of it is actually called! I didn't get to spend a lot of time on the algorithm today but I started learning about how to use Maps, which seems comparible to something I'd see in Java. So I'll be exploring this more tomorrow.

**Sources:**  
https://flaviocopes.com/javascript-data-structures-map/  
https://javascript.info/map-set

**Links:** [Check Permutations](https://repl.it/@digidarkdev/Check-Permutation "Check Permutations")


### Day 2: August 29, 2019 

**Today's Progress**: Unfortunately I had a migraine most of today so I didn't get much in after applying to jobs... but I was able to practice an algorithm from Cracking the Coding Interview. I learned about using Sets in JavaScript, which I did not know existed. I did tried two different functions to check if a string has unique characters. One way was with a Set, the other I tried character codes like I had learned in Java. I only did it was ASCII and not Unicode.

**Thoughts:** Wishing I made more progress today but I'm happy I learned about Sets. It will be very useful in the future. I also enjoy finding multiple ways to solve one problem. Tomorrow I'd like to get back to the Advanced JavaScript Concepts course, and try another algorithm.

**Sources:**  https://flaviocopes.com/javascript-data-structures-set/

**Links:** [Unique Character Checker](https://repl.it/@digidarkdev/Unique-Characters "Unique Character Checker")

### Day 1: August 28, 2019 

**Today's Progress**: Today I finished section 2 of Andrei Neagoie's Advanced JavaScript Concepts Udemy course. I also started an algorithm from Cracking the Coding Interview that I want to cover more deeply tomorrow because I know there is a way to do it with ASCII checks. I learned several concepts that I had forgotten over time. The topics I covered today are -- 

-- The JavaScript Engine

-- JS being both an interpreted and a compiled language, depending on the implementation of it.

-- Interpreters and compilers - interpreters translate line by line on the fly and compilers work ahead of time to create the translation. Interpreters are quick to get up and running, but code is not as optimized as a compiled language.

-- JIT compiler - JS now interprets and compiles, best of both worlds - the profiler watches the code and makes notes on how to optimize it.

-- inline caching and hidden classes

-- Web Assembly

-- Call Stack and Memory Heap - the call stack keeps track of where we are in the code, memory heap is where we allocate, use, and release memory

-- JS is a single threaded language - 1 call stack, 1 memory heap

-- Garbage collection & memory leaks

-- JavaScript Runtime & Web API

-- Event loop and callback queue


**Thoughts:** Today was a busy day of JS foundational knowledge. I learned a ton about how the language works behind the scenes, which I know will help my thought process when coding. I actually decided to start hand writing my notes because I think that will help this knowledge sink in more. I cleared out my Repl account and wanted to start using it to try an algorithm a day(maybe not every day but I'm going to try!). I want to dive deeper into the unique character checker. I know there is a much more efficient way to check than what I am doing because I've done it in Java before... but I think I'm not sure how to convert that to JavaScript. So I'm going to try to link these two thought processes for these languages together so I can better understand concepts and worry less about syntax.

**Sources:**  Advanced JavaScript Concepts - Andrei Neagoie Udemy Course

**Links:** [Unique Character Checker](https://repl.it/@digidarkdev/Unique-Characters "Unique Character Checker")


