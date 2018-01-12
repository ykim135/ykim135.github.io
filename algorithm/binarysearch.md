##Binary Search

I remember when I was serving in the military a couple of years ago back in 2014. 
I served in the joint U.S and Korean army and was based in Yongsan.

Back then, I was a newly deployed private and my first mission was...

Organizing paperwork and handing over documents upon request. 

Amazing right? You wouldn't know how disappointed I was after weeks of basic training
only to find out that all I would be doing is sorting papers. 

My sergeant would yell "You! Private! Come here! Get that man's ID number and give him the docs he needs ASAP!"
and that's when I would know that I would have to get my nose stuck in that cabinet and fetch him the papers he needs.

The docs were all sorted in order by ID and John who was my coworker would look fly through the stacks of papers and
until he hit the matching ID number. 

Took him around 5 minutes but I would say that's good enough if the person standing over the counter
is patient enough. 

As the paper stack grew bigger and bigger, it was getting harder for poor old John and his brute force way of
finding what he needs. That's when I started to wrap my head around a better solution and up came the binary search
algorithm that I learned in my data structures course ages ago. 

I would without hesitation attack the mid part of the paper stack and if it shows some id that's smaller than 
what I have, I would move on to the first half of the stack. If it's bigger, I move towards the second half of the stack.

So basically, I shrink the search scope into half size and then peek at the value at the middle of the stack. I repeat 
the process of moving to the first half of the stack if the number in the middle is smaller than what I have and move onto the 
second half of the stack in the opposite case. 

That my friends, is binary search in real life. Who would have though the age old algorithm from your textbook would 
be so pragmatic? (no pun intended)

## How do you really describe binary search?

If I were to explain it in a more textbook-ish way, I would say binary search is a divide and conquer search technique 
that halves the scope of search based on how small or large the search value is compared to a target value.

Binary search is performed on arrays and trees and it is essential to know how to implement the search using both structures.

Before we dive into code, I want to take a moment for a little storytelling to 
understand how the concept works. This is my most favorite method when it comes
to learning and teaching because it helps us understand the broad basics while abstracting
away the hard part which comes later.



