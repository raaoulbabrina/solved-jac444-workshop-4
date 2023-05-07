Download Link: https://assignmentchef.com/product/solved-jac444-workshop-4
<br>



<strong>Description:</strong>

The following workshop lets you practice basic java coding techniques, creating classes, methods, using arrays, <strong>Java I/O</strong>, inheritance, polymorphism, Exceptional Handling.

<strong> </strong>

<strong>Task 1: </strong>

Write a program for <em>hangman game</em> that randomly picks a word from a text file named <strong>hangman.</strong>txt and prompts the user to guess one letter at a time, as shown in the sample run.




<ul>

 <li>Each letter in the word is displayed as an asterisk. When the user makes a correct guess, the actual letter is then displayed.</li>

 <li>When the user finishes a word, the following streps should happen o Display the number of misses to the user. o Ask the user to give you a new word, then add that word to your file <strong>txt</strong>. (Optional if you want to check for the duplicate words in the file)</li>

</ul>

o Ask the user whether to continue to play.

<ul>

 <li>If the user missed the same letter more than one time give extra hint to the player like “You’ve already tried this letter, try another letter”. Don’t count twice the same letter which is missed by the user.</li>

 <li>Have minimum 10 words of your choice in the file <strong>txt</strong>.</li>

</ul>




<table width="623">

 <tbody>

  <tr>

   <td width="623">(Guess) Enter a letter in word ******* &gt; p(Guess) Enter a letter in word p****** &gt; r(Guess) Enter a letter in word pr**r** &gt; pp is already in the word(Guess) Enter a letter in word pr**r** &gt; o(Guess) Enter a letter in word pro*r** &gt; g(Guess) Enter a letter in word progr** &gt; dd is not in the word(Guess) Enter a letter in word progr** &gt; m(Guess) Enter a letter in word progr*m &gt; dYou have already tried d, try a new letter</td>

  </tr>

  <tr>

   <td width="623">(Guess) Enter a letter in word progr*m &gt; aThe word is program. You missed 1 timeEnter a new word to be added in the memory&gt; appleDo you want to guess another word? Enter y or n&gt;</td>

  </tr>

 </tbody>

</table>




<strong>Note: </strong>Students can make the output better as well in easier and more readable format.




<strong> </strong>

<strong>Task – 2  </strong>

Write a program that prompts the user to enter a file name and displays the occurrences of each letter in the file. Letters are case-sensitive. Here is a sample run:




<table width="487">

 <tbody>

  <tr>

   <td width="487">Enter a filename: Somefile.txtNumber of A’s: 56Number of a’s: 24 Number of B’s: 134…Number of Z’s: 9 Number of z’s: 2</td>

  </tr>

 </tbody>

</table>










Workshop Header




/**********************************************

<strong>Workshop #  </strong>

<strong>Course:</strong><em>&lt;subject type&gt; – Semester </em>

<strong>Last Name:</strong><em>&lt;student last name&gt; </em>

<strong>First Name:</strong><em>&lt;student first name&gt; </em>

<strong>ID:</strong><em>&lt;student ID&gt; </em>

<strong>Section:</strong><em>&lt;section name&gt; </em>

<em>This assignment represents my own work in accordance with Seneca Academic Policy. </em>

<em>Signature </em>

<strong>Date:</strong><em>&lt;submission date&gt; </em>

**********************************************/




<strong> </strong>

Code Submission Criteria:

Please note that you should have:

<ul>

 <li>Appropriate indentation.</li>

 <li>Proper file structure</li>

 <li>Follow java naming convention</li>

 <li>Document all the classes properly</li>

 <li>Do Not have any debug/ useless code and/ or files in the assignment</li>

 <li>Do not have everything in the <em>main method</em>.</li>

 <li>Have a separate TestClass with the main method in it.</li>

 <li>Check your inputs if the user is not entering garbage inputs.</li>

 <li>Use exceptional handling or other methods to let the user know if the inputs are incorrect.</li>

</ul>




Deliverables and Important Notes:




<strong>All these deliverables are supposed to be uploaded on the blackboard once done. </strong>

<strong> </strong>

<ul>

 <li>You are supposed to create video/ record voice/ detailed document of your running solution. <strong>(50%)</strong>  o Screen Video captured file should state your last name and id, like</li>

</ul>

Ali_123456.mp4 (or whatever the extension of the file is) o Record voice clip should also include a separate word file with the screen shots of your program’s output, state your last name and id, like Ali_123456.mp3 (or whatever the extension of the file is)

o Detailed document should include screen shots of your output, have your name and id on the top of the file and save the file with your last name and id, like Ali_123456.docx (or whatever the extension of the file is)

<ul>

 <li>A word/ text file which will reflect on learning of your concepts in this workshop. Also include the instructions on how to run your code.                                 <strong>(30%)</strong>

  <ul>

   <li>Should state your Full name and Id on the top of the file and save the file with your last name and id, like Ali_123456.txt</li>

  </ul></li>

 <li>Submission of working code.                                                                         <strong>(20%)</strong>

  <ul>

   <li>Make sure your follow the “<strong>Code Submission Criteria”</strong> mentioned above.</li>

   <li>You should zip your whole working project to a file named after your Last Name followed by the first 3 digits of your student ID. For example, zip.</li>

  </ul></li>

 <li>Your marks will be deducted according to what is missing from the above-mentioned submission details.</li>

 <li>Late submissions would result in additional 10% penalties for each day or part of it.</li>

 <li>Remember that you are encouraged to talk to each other, to the instructor, or to anyone else about any of the assignments, but the final solution may not be copied from any source.</li>

</ul>




<strong> </strong>