# assembly_debug_sheets
Sheets formatted to help debug assembly code for different processors.

Since I started learning assembly coding, I've found myself taking notes and writing down register and memory values on random pieces of paper for a long time.

So I thought it would be a good idea to have a template you can print which would allow to see more clearly what are you writing down, in an organized manner and able to identify the pieces of code you were debugging.

This is what you'll find here.

These debug sheets have the name of the processor, the 'project' (or whatever it is) you're trying to debug and the sheet number (important if you're debugging a pretty long code!) on the top of the page.
Then you'll find a header with register names and, if possible, a column for notes.

Some processors do combine several registers into another ones. For example, the 6809 combines 8-bit accumulators A and B into a 16-bit accumulator called D. To highlight that, these combined accumulators will be coloured slightly darker and it's combined name will appear at the bottom of the page. That way, you can see the full combined register and its parts at the same time. For clarity, if there are several of this combined registers together, the colour scheme will alternate so the columns are easily identifiable.

And, that's it!

I hope you find them useful and if you have any suggestion, please let me know.

Happy debugging! :D
