Download Link: https://assignmentchef.com/product/solved-sdev425-week4-implementing-low-impact-security-controls
<br>
In this homework you will enhance an existing JavaFX Login application to add select low-impacts security controls based on recommendations from the NIST security controls database. We won’t be able to implement all of the baseline controls for this exercise. However; the assignment details below provide direction on which ones should be implemented. You will also asked to choose one additional low-impact security control, of your choice and implement it.

Assignment Part I: Review and Understand the Sample JavaFX application

More than likely you have not coded a JavaFX application before. However; if you successfully completed the CMIS242 prerequisite, you have seen how to create Simple GUI’s using the Swing class. JavaFX is quite similar to the Swing classes. In fact, most of the classes and methods provide the same functionality. The sample code provided will refresh and enhance your GUI building skills.

<ol>

 <li>Using Netbeans, start a new Java project. Select the JavaFX application option.</li>

</ol>










<ol start="2">

 <li>Name the project SDEV425HW2 (or a name of your choice).</li>

</ol>







<ol start="3">

 <li>Click Finish and the template application code will be provided.</li>

</ol>













<ol start="4">

 <li>Click the Green arrow to run the application.</li>

</ol>










<ol start="5">

 <li>Clicking the button will display “Hello World” in the Netbeans output.</li>

</ol>




<ol start="6">

 <li>Study the template code paying careful attention to the methods, and the use of the event handlers.</li>

</ol>




<ol start="7">

 <li>Using the Login Application, <strong>provided as an attachment in this assignment</strong>, copy and paste it into your project. Note: you may need to change the class and package name of the Login application.</li>

</ol>




<ol start="8">

 <li>Run and <strong>experiment</strong> with the code so you understand what each line of code is doing.</li>

</ol>




<ol start="9">

 <li>Demonstrate you successfully completed this part of the assignment by providing screen captures generated from your development environment showing both the FX Hello, World and SDevAdmin login apps running with no additional modifications.</li>

</ol>




<ol start="10">

 <li>Describe an overview of the functionality of the SDEVAdmin login application pointing out the functionality of critical code components.</li>

</ol>

<strong>Part II: Apply select NIST low-impact security controls to the JavaFX Login application. </strong>




The following security controls should be applied to the application (check the NIST Security Controls Database for details, description and guidance for each control:

<ul>

 <li>AC-7 – UNSUCCESSFUL LOGON ATTEMPTS</li>

 <li>AC-8 – SYSTEM USE NOTIFICATION</li>

 <li>AU-3 – CONTENT OF AUDIT RECORDS</li>

 <li>AU-8 – TIME STAMPS</li>

 <li>IA-2(1) IDENTIFICATION AND AUTHENTICATION (ORGANIZATIONAL USERS) | NETWORK ACCESS TO PRIVILEGED ACCOUNTS (Note this is an enhancement of an existing low-impact security control)</li>

 <li>Select one additional low-impact security control and implement it. This can be an enhancement or a required low-impact security control. Selecting a control that provides documentation as opposed to code changes is also acceptable and encouraged.</li>

</ul>

Hints:

<ol>

 <li>Start with the baseline Login Application and add methods (or additional classes) as needed to comply with each of the security controls.</li>

 <li>You will need to make some decisions for your implementation for the security audit/log files format. Each student may have a slightly different implementation.</li>

 <li>For the multi-factor authentication, keep it simple. One approach is to send an email to the user with a security code. Then, have them check their email and enter the code. If the code matches, they are properly authenticated.</li>

 <li>There are examples for using JavaMail and writing to files in the materials for this week. Be sure to use those as needed.</li>

 <li>Pay attention to the details of the NIST database description and make sure all of the selected security controls for this project are fully implemented.</li>

 <li>Start on this early. This will take you longer than you think.</li>

</ol>