Download Link: https://assignmentchef.com/product/solved-cs2310-lab-6-debugger
<br>
<h1></h1>

<ul>

 <li>What is a debugger?</li>

 <li>A tool for programmer to</li>

 <li>Trace the execution path of a program</li>

 <li>Step through the code line by line and investigate the value of variables at each step</li>

 <li>When you need a debugger?</li>

 <li>When a program does not act as the programmer expected, the debugger can help to find out the logical bug</li>

</ul>

<h1>Outline</h1>

<ul>

 <li>In this lab you will learn how to</li>

 <li>Trace a program</li>

 <li>Display the value of variable</li>

 <li>Finish exercises</li>

</ul>

<h1>Lab Exercise</h1>

<ul>

 <li>Debug a sample program (debug1.cpp)</li>

 <li>Steps:

  <ol>

   <li>Create a new project in Visual Studio (VS)</li>

   <li>Download the debug1.cpp from Canvas and save it to the project folder</li>

   <li>In Visual Studio, add an existing item to the project</li>

  </ol></li>

</ul>

Add the sample program to the project

Tip: Display Line Numbers in Visual Studio

<ul>

 <li>To display line numbers in code

  <ol>

   <li>On the menu bar, choose <strong>Tools</strong>, <strong>Options</strong>. Expand the <strong>Text Editor </strong>node, and then select either the node for the language you are using, or <strong>All Languages </strong>to turn on line numbers in all languages. Or, you can type <strong>line number </strong>in the <strong>Quick Launch </strong></li>

  </ol></li>

</ul>

Tip: Display Line Numbers in Visual Studio

<ul>

 <li>To display line numbers in code</li>

</ul>

<ol start="2">

 <li>Select the <strong>Line numbers </strong>checkbox.</li>

</ol>

<h1>Set a breakpoint</h1>

<h2>Steps to invoke the debugger</h2>

<ul>

 <li>Build/Rebuild the solution</li>

 <li>Start the debugger</li>

 <li>Start a debugging session using <strong>F5 </strong>(<strong>Debug </strong>&gt; <strong>Start Debugging</strong>). This command starts your app with the debugger attached.</li>

 <li>The green arrow on the tool bar also starts the debugger (same as <strong>F5</strong>).</li>

 <li>The program execution should stop at the line “x=3”</li>

</ul>

<h3>Start the debugger (menu bar)</h3>

<h2>Start the debugger (tool bar)</h2>

<h1>Execution stop at x=3</h1>

<h1>Step through a program</h1>

<ul>

 <li>Step over (F10):</li>

 <li>Execute the current statement and stop at the next statement.</li>

 <li>If the current statement is a function call, the function will be called.</li>

 <li>Step Into (F11):</li>

 <li>If the current statement is a function call, go inside the function body and stop at the first statement.</li>

 <li>Step out (Shift+F11):</li>

 <li>Finish the execution of current function and stop at the point where the function is called.</li>

</ul>

<h1>Step into code, line by line</h1>

Step through code, skipping functions

Step through code, skipping functions

<h1>Summary of short-cut key</h1>

<table width="0">

 <tbody>

  <tr>

   <td width="441"><strong>Key</strong></td>

   <td width="441"><strong>Function</strong></td>

  </tr>

  <tr>

   <td width="441">F5</td>

   <td width="441">Start debugging</td>

  </tr>

  <tr>

   <td width="441">Ctrl + F5</td>

   <td width="441">Start without debugging</td>

  </tr>

  <tr>

   <td width="441">Shift + F5</td>

   <td width="441">Stop debugging</td>

  </tr>

  <tr>

   <td width="441">F10</td>

   <td width="441">Step over</td>

  </tr>

  <tr>

   <td width="441">F11</td>

   <td width="441">Step into</td>

  </tr>

  <tr>

   <td width="441">Shift + F11</td>

   <td width="441">Step out</td>

  </tr>

 </tbody>

</table>

<h2>Display the value of a variable</h2>

<ul>

 <li>Value of variable can be found in</li>

 <li>Autos: display related variables (selected by VS)</li>

 <li>Locals: display local variable only</li>

 <li>.N: display user selected variable</li>

</ul>

<h2>Display the value of a variable</h2>

<h1>Example: x = -858993460</h1>

<h1>Example: x = 3</h1>

<h1>Example: input new x</h1>

<h1>Example: x = 5</h1>

If you can’t find the watch window

<h1>Add a variable to Watch</h1>

<h1>Add a variable to Watch</h1>

<h1>Add a variable to Watch</h1>

<h1>Exercise 1</h1>

<ul>

 <li>Download the program cToF.cpp</li>

 <li>The program accepts a real number in Fahrenheit (F) and output the temperature in Celsius, where C = (F – 32)</li>

</ul>

* 5 / 9.

<ul>

 <li>Compile and execute the program.</li>

 <li>Type 100 as the input</li>

 <li>Notice that the output of the program is not correct and the program contains logical errors.</li>

 <li>Try to locate and debug the program using the VS debugger</li>

 <li>Hint: what is the value of 5/9?</li>

</ul>

<h1>Exercise 1: Wrong Output</h1>

<h1>Exercise 2</h1>

<ul>

 <li>Do this question after you have learnt the topic on arrays</li>

 <li>Download sumArray.c, correct the logical errors in the program with the use of the debugger</li>

</ul>