<table><tr><td> <em>Assignment: </em> IS601 - Mini Project 2 - Burgers</td></tr>
<tr><td> <em>Student: </em> Jahnavi Soman (js2679)</td></tr>
<tr><td> <em>Generated: </em> 4/1/2023 6:04:40 AM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-004-S23/is601-mini-project-2-burgers/grade/al762" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>Create a new branch per the desired branch name below</li><li>Add the baseline files from the following link:&nbsp;<a href="https://gist.github.com/MattToegel/028db0e3fd2b20c1fb8e284b341292bb">https://gist.github.com/MattToegel/028db0e3fd2b20c1fb8e284b341292bb</a>&nbsp;</li><li>Put them into a subfolder in your repository folder (I called my folder BurgerMachine)</li><li>git add .</li><li>git commit -m "baseline files"</li><li>git push origin (name of desired branch below)</li><li>You can go to github and open the pull request for evidence capturing later (don't close/merge the pull request until you're done with the assignment)</li><li>Do the below tasks and fill in the below entries</li><ol><li>git add/commit after any significant changes to build up history</li></ol><li>Save the input and generate the submission markdown file (copy to clipboard or download the file)</li><li>Name it something relevant to the assignment if it's not named already</li><li>git add the submission file</li><li>git commit the submission file</li><li>git push the submission file</li><li>Complete the pull request to dev</li><li>Create a pull request from dev to prod</li><li>Go to the prod branch on github, navigate to the submission file</li><li>Paste that link to Canvas</li></ol></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Code Changes - Add the calculate_cost() implementation </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot(s) of the updated method calculate_cost()</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/63836995/229330635-5489136b-0b87-4f04-a0ff-0d6ea50c2de9.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>this method calculates the cost of burger and returns the value as the<br>currency format with $ symbol by using :.2f format specifier<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/63836995/229330877-f22e4530-ce46-4b04-8b16-a5b2dafa20c2.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>In the output, we can see that input() prints the cost in currency<br>format with $ symbol<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Explain the approach to implementing the calculation</td></tr>
<tr><td> <em>Response:</em> <div>The calculate_cost() method initializes cost to zero and then iterates over each item<br>in the inprogress_burger list, adding the cost of each item to the cost<br>. Finally, the method returns the cost variable as a formatted string. The<br>string includes the $ symbol and formats the cost variable with two decimal<br>places using the :.2f format specifier.</div><div>The input() message prints the cost with $<br>as prefix. Later user enters the price with the same $ prefix and<br>the amount.</div><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Exception Handling </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot(s) of adjusted code to handle exceptions</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/63836995/229328828-6741b3a9-d202-48a5-82ff-69a98a07a485.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Adjusted code to handle out of stock exceptions with proper feedbacks at different<br>stages<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/63836995/229329111-5f7bbf29-de7c-4513-80b6-7e5f2507fe56.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Adjusted code to handle NeedsCleaningException, this exception is raised if remaining_uses exceeds 15.It<br>prompts the user to type &#39;clean&#39;<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/63836995/229329200-86dcb526-1029-483c-be2f-88e0efe42af5.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>code is showing invalid option if other words are given as input instead<br>of &#39;clean&#39;<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/63836995/229329351-4401be36-f0bc-45e7-836a-95a8c369d3ef.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>code is showing Invalid Choice Exceptions and proper feedback is given ensuring the<br>continuity in the program<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/63836995/229329526-031d2d98-a455-4ec6-b501-5158d062c1f9.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>code is showing ExceededRemainingChoicesExceptions with proper feedbacks and the stage at which remaining<br>choices were exceeded with continuity in program flow<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/63836995/229329678-26512b32-59e5-44f0-abdb-6cede382e882.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>code is showing InvalidPaymentException with proper userflow and feeedback<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Summarize each exception handling process</td></tr>
<tr><td> <em>Response:</em> <p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px;"><font face="Times New Roman, serif"><span style="font-size:<br>16px;">In the&nbsp;OutOfStockException,&nbsp;</span></font><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16px;">If currently_selecting is STAGE.Bun, then<br>the code will print a message indicating that there is an out of<br>stock of buns. Similarly, if currently_selecting is STAGE.Patty, then the code will print<br>a message indicating that there is an out of stock of patties, and<br>if currently_selecting is STAGE.Toppings, then the code will print a message indicating that<br>there is an out of stock of toppings.</span></p><p class="MsoNormal" style="margin: 0in 0in 8pt;<br>line-height: 16.8667px;">In the&nbsp;<span style="font-size: 13px;">NeedsCleaningException,&nbsp;</span>If the user inputs 'clean', then the clean_machine() method<br>is called to clean the machine, and a message is printed to indicate<br>that the cleaning was successful. Otherwise, a message is printed to indicate that<br>the cleaning was not successful because the user did not input 'clean'.</p><p class="MsoNormal"<br>style="margin: 0in 0in 8pt; line-height: 16.8667px;">In the&nbsp;<span style="font-size: 13px;">InvalidChoiceException,&nbsp;</span>If currently_selecting is STAGE.Bun, then<br>the code will print a message indicating that the choice of bun is<br>invalid and ask the user to enter a valid choice. Similarly, if currently_selecting<br>is STAGE.Patty, then the code will print a message indicating that the choice<br>of patty is invalid and ask the user to enter a valid choice,<br>and if currently_selecting is STAGE.Toppings, then the code will print a message indicating<br>that the choice of toppings is invalid and ask the user to enter<br>a valid choice.</p><p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px;">In the&nbsp;<span style="font-size: 13px;">ExceededRemainingChoicesException,&nbsp;If<br>currently_selecting is STAGE.Toppings, then the code will print a message indicating that the<br>remaining choice for toppings has been exceeded and move on to the next<br>category. The variable toppings is used in the message to indicate which topping<br>has exceeded the remaining choices. The code also sets currently_selecting to STAGE.Pay to<br>indicate that the sandwich is ready for payment. If currently_selecting is STAGE.Patty, then<br>the code will print a message indicating that the remaining choice for patties<br>has been exceeded and move on to the toppings category. The variable patty<br>is used in the message to indicate which patty has exceeded the remaining<br>choices.</span></p><p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px;"><span style="font-size: 13px;">In the&nbsp;</span><span style="font-size: 13px;">InvalidPaymentException,<br>If this exception is raised, the code will print a message indicating that<br>the payment amount is invalid and ask the user to enter the exact<br>amount.</span></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Test Cases </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot(s) of test cases per the checklist</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/63836995/229238067-1af86131-a11f-447a-8877-f78111c45d91.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>In the above image, bun was the first choice, so there was no<br>error. Therefore, test 1 is satisfied<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/63836995/229238330-5698cc42-5a51-4fa2-b296-f4376c3baa56.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Here, bun was not the first choice, so an error was raised with<br>the exception invalid stage. Therefore, test 1 is satisfied<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/63836995/229238563-a274df1d-bc5d-41ca-b3ab-bb32f3379aa5.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>if the patties exceed more than 3 , exception is raised. So, test<br>4 is satisfied<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/63836995/229238868-331a0dc2-9fa3-40da-a0a0-b54b6a74d828.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>if the toppings are less than 3, code accepts. So, test 5 is<br>done<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/63836995/229256116-2b44a4b5-3f6e-4059-8bb7-6f955a39427d.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>This is  test 2 and 3 showing out of stock exception as<br>the quantity is less than 0<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/63836995/229255225-99bb1d55-bfab-41cb-99c2-57ba64be48d1.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>this image shows three kinds of burger inputs and the calculation of the<br>price<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/63836995/229256557-65669176-f7ee-4279-ab3a-d546c19160d3.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>this image shows the increase in total sale after every sale of burger.So,<br>test 8 is done<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Summarize each test case logic</td></tr>
<tr><td> <em>Response:</em> <p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px; font-size: 11pt; font-family: Calibri, sans-serif;"><span<br>style="font-size: 12pt; line-height: 18.4px; font-family: &quot;Times New Roman&quot;, serif;">Test 1 - ensures that<br>a bun selection is required before adding patties and toppings. If directly patty<br>is given as input, invalid stage exception was raised<o:p></o:p></span></p><p class="MsoNormal" style="margin: 0in 0in<br>8pt; line-height: 16.8667px; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12pt; line-height: 18.4px; font-family:<br>&quot;Times New Roman&quot;, serif;">&nbsp;</span></p><p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px; font-size: 11pt;<br>font-family: Calibri, sans-serif;"><span style="font-size: 12pt; line-height: 18.4px; font-family: &quot;Times New Roman&quot;, serif;">Test 2<br>- ensures that patties can only be added if they are in stock.<br>As there were no patties out of stock exception was raised. If patties<br>were available, then output is shown as seen in test1<o:p></o:p></span></p><p class="MsoNormal" style="margin: 0in<br>0in 8pt; line-height: 16.8667px; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12pt; line-height: 18.4px;<br>font-family: &quot;Times New Roman&quot;, serif;">&nbsp;</span></p><p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px; font-size:<br>11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12pt; line-height: 18.4px; font-family: &quot;Times New Roman&quot;, serif;">Test<br>3 - ensures that toppings can only be added if they are in<br>stock.&nbsp;<o:p></o:p></span><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16px;">As there were no toppings out<br>of stock exception was raised. If toppings were available, then output is shown<br>as seen in test1</span></p><p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px; font-size: 11pt;<br>font-family: Calibri, sans-serif;"><span style="font-size: 12pt; line-height: 18.4px; font-family: &quot;Times New Roman&quot;, serif;">&nbsp;</span></p><p class="MsoNormal"<br>style="margin: 0in 0in 8pt; line-height: 16.8667px; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12pt;<br>line-height: 18.4px; font-family: &quot;Times New Roman&quot;, serif;">Test 4 - ensures that up to<br>3 patties of any combination can be added. If patties are exceeded more<br>than 3, then exceeded remaining choices exception is raised, otherwise the burger stages<br>are shown<o:p></o:p></span></p><p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px; font-size: 11pt; font-family: Calibri,<br>sans-serif;"><span style="font-size: 12pt; line-height: 18.4px; font-family: &quot;Times New Roman&quot;, serif;">&nbsp;</span></p><p class="MsoNormal" style="margin: 0in<br>0in 8pt; line-height: 16.8667px; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12pt; line-height: 18.4px;<br>font-family: &quot;Times New Roman&quot;, serif;">Test 5 - ensures that up to 3 toppings<br>of any combination can be added.&nbsp;<o:p></o:p></span><span style="font-family: &quot;Times New Roman&quot;, serif; font-size: 16px;">If<br>toppings are exceeded more than 3, then exceeded remaining choices exception is raised,<br>otherwise the burger stages are shown</span></p><p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px;<br>font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12pt; line-height: 18.4px; font-family: &quot;Times New Roman&quot;,<br>serif;">&nbsp;</span></p><p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px; font-size: 11pt; font-family: Calibri, sans-serif;"><span<br>style="font-size: 12pt; line-height: 18.4px; font-family: &quot;Times New Roman&quot;, serif;">Test 6 - ensures that<br>the cost must be calculated properly based on the choices.<o:p></o:p></span></p><p class="MsoNormal" style="margin: 0in<br>0in 8pt; line-height: 16.8667px; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12pt; line-height: 18.4px;<br>font-family: &quot;Times New Roman&quot;, serif;">&nbsp;</span></p><p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px; font-size:<br>11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12pt; line-height: 18.4px; font-family: &quot;Times New Roman&quot;, serif;">Test<br>7 - ensures that the total sales must be calculated properly. In the<br>above image, each burger sale was calculated&nbsp;<o:p></o:p></span></p><p class="MsoNormal" style="margin: 0in 0in 8pt; line-height:<br>16.8667px; font-size: 11pt; font-family: Calibri, sans-serif;"><span style="font-size: 12pt; line-height: 18.4px; font-family: &quot;Times New<br>Roman&quot;, serif;">&nbsp;</span></p><p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px; font-size: 11pt; font-family: Calibri,<br>sans-serif;"><span style="font-size: 12pt; line-height: 18.4px; font-family: &quot;Times New Roman&quot;, serif;">Test 8 - ensures<br>that the total burgers should properly increment for each purchase. Whenever a burger<br>is ordered, the total sales increased one after one as shown in the<br>above code<o:p></o:p></span></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Misc </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add pull request for the assignment</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/aneeshlanka/IS601/pull/10">https://github.com/aneeshlanka/IS601/pull/10</a> </td></tr>
<tr><td> <em>Sub-Task 2: </em> Explain any issues/difficulties or something you learned while doing this assignment</td></tr>
<tr><td> <em>Response:</em> <p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px; font-size: 11pt; font-family: Calibri, sans-serif;"><span<br>style="font-size: 12pt; line-height: 18.4px; font-family: &quot;Times New Roman&quot;, serif;">I have learned to create<br>multiple test cases to thoroughly test a program along with handling the exceptions.<br>I have learnt about usage of lists, functions, pytest fixtures. I have also<br>learned how to create pull requests on GitHub. Additionally, I have gained a<br>better understanding of how to debug code and identify errors. One difficulty I<br>encountered was understanding how to use the pytest library to write test cases.<br>However, I eventually learned how to use it and was able to complete<br>the assignment.<o:p></o:p></span></p><br></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshots of successful output</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/63836995/229253077-e29811f3-66de-4ee2-a0e2-97d10277ea35.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>the output asks the user to enter the bun and patty and toppings<br>and calculates the price in currency format <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/63836995/229254534-30b91bb6-2225-4bb7-a6a6-d20a85e2f6ac.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>in this screenshot, few inputs are given wrong and immediately a prompt was<br>raised to correct the user in entering the inputs and payment cost<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-004-S23/is601-mini-project-2-burgers/grade/al762" target="_blank">Grading</a></td></tr></table>
