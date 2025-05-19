
1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

I would fit them within a Github action that runs whenever code is pushed, because that way I can add tests incrementally, make the sure the code I wrote was accurate, and save time by automating these tests. 

2. Would you use an end to end test to check if a function is returning the correct output? 

No. 

3. What is the difference between navigation and snapshot mode?

Navigation mode analyzes performance right after the page loads, so it also takes into account page load performance. On the other hand, snapshot mode analyzes performance at the current state of the page, which is not necessarily right after page load. 

4. Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

- add a `<meta name="viewport">` tag with width or initial-scale
- serve images in next gen formats
- Size images according to display size
   




