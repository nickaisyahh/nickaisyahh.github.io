<!DOCTYPE html>
<html>

<head>

   <title>My Mobile Page!</title>
   <link rel="stylesheet" href="themes/myThemes.min.css" />
<link rel="stylesheet" href="themes/jquery.mobile.icons.min.css" />
   <link rel="stylesheet" href="https://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.css" />
   <script src="https://code.jquery.com/jquery-1.11.1.min.js"></script>
   <script src="https://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
</head>

<body>
<div data-role="page" id="page1" data-theme="d">
<div data-role="header">
<h1>Personal Information</h1>
<div data-role="navbar">
<ul>
<li> <a href="#page1" data-icon="grid">Personal Information</a> </li>
<li> <a href="#page2" data-icon="heart">Hobby</a> </li>
<li> <a href="#page3" data-icon="heart">Family Background</a> </li>
<li> <a href="#page4" data-icon="heart">Exam Result</a> </li>
</ul>
</div>
</div>

<div data-role="main" class="ui-content" style="font-family:verdana;">
<center>
<h1>BIODATA</h1>


<img src="C:\Users\acer\Pictures\iCloud Photos\Photos\P1.jpeg"  style="border-style:double; width:10%; height=10%;">


  <p>NAME : NIK SITI NUR AISYAH BINTI NIK FARIZU</p>
<p>AGE :  20 YEARS OLD</p>
<p>BIRTH OF DATE : 09 JUNE 2003</p>
<p>ADDRESS : LOT 2834 DESA PERMAI, PDG BONGOR,<br></br>1650 KOTA BHARU, KELANTAN</p>
<p>PHONE NUMBER : 017-945-1365</p>
<p>EMAIL : nickaisyahh@gmail.com</p>
 </center>
 
<div data-role="collapsible">
<h1>Education</h1>
<ul data-role="listview" data-inset="true">
           <li> <img src="C:\Users\acer\Desktop\SADAM\tadika.png" width="80" height="80">
		   
            <h2>2007 - 2009 : TADIKA A SATU</h2>
          </li>
          <li>  <img src="C:\Users\acer\Desktop\SADAM\skkk1.png" width="80" height="80">
            <h2>2010 - 2015 : SK KUBANG KERIAN 1</h2>
          </li>
          <li><img src="C:\Users\acer\Desktop\SADAM\maher.gif" width="80" height="80">
            <h2>2016 - 2020 : SMK DATO' AHMAD MAHER</h2>
          </li>		  
		  <li><img src="C:\Users\acer\Desktop\SADAM\poli.png" width="80" height="40">
            <h2>2021 - Now : POLITEKNIK SULTAN MIZAN ZAINAL ABIDIN</h2>          
          </li>		 
        </ul>
		</div>

<a href="#page2" data-transition="flow">Go to Page 2</a>
</div>

<div data-role="footer">
<h2>&copy; Web Class 2023</h2>
</div>
</div>

<div data-role="page" id="page2" data-theme="e">
<div data-role="header">
<h1>Hobby</h1>
<div data-role="navbar">
<ul>
<li> <a href="#page1" data-icon="grid">Personal Information</a> </li>
<li> <a href="#page2" data-icon="heart">Hobby</a> </li>
<li> <a href="#page3" data-icon="heart">Family Background</a> </li>
<li> <a href="#page4" data-icon="heart">Exam Result</a> </li>
</ul>
</div>
</div>

<div data-role="main" class="ui-content">
<center>
<h1>My Hobby: Painting</h1>
<img src="C:\Users\acer\Desktop\SADAM\painting.png"  style="width:30%; height=30%;">
      <br><br>
      <p style= "border-style:solid;">Painting is a wonderful hobby that will can make us express ourself. <br>
	  Painting also can make me be a creative person while also providing <br>a sense of relaxation and calm.<br>
	  This hobby can also make me feel good.</p></center>
<br></br>
<center>
<img src="C:\Users\acer\Desktop\SADAM\paint.png"  style="width:20%; height=20%; border-style:double;">
<br></br>

<form style="font-family:verdana">
<label for="essay">Tell me what you think about my painting!</label>
<textarea name="essay" id="essay" placeholder="Tell me how great are my painting!"></textarea>
<label for="rate">Rate my painting out of 10</label>
<br></br>
<input type="range" name="range" id="rate" min="0" max="10"/>

</form>

<button onclick="window.dialog.show();">Rate My Painting</button>
<br></br>
<dialog id="dialog">
  Thankyou For Rating Me!.
  <button onclick="window.dialog.close();">close</button>
</dialog>

</center>
<br></br>
<br></br>
<br></br>
<a href="#page3" data-transition="flow">Go to Page 3</a>
</div>


<div data-role="footer">
<h2>&copy; Web Class 2023</h2>
</div>
</div>

<div data-role="page" id="page3" data-theme="f">
<div data-role="header">
<h1>Family Background</h1>
<div data-role="navbar">
<ul>
<li> <a href="#page1" data-icon="grid">Personal Information</a> </li>
<li> <a href="#page2" data-icon="heart">Hobby</a> </li>
<li> <a href="#page3" data-icon="heart">Family Background</a> </li>
<li> <a href="#page4" data-icon="heart">Exam Result</a> </li>
</ul>
</div>
</div>

<div data-role="main" class="ui-content">
<center>
<h1>Family Background</h1>
<p style="font-family:verdana">IZUDAA'S FAMILY</p>
<img src="C:\Users\acer\Downloads\try1-removebg-preview.png" width="330" height="350"></center>

<div data-role="collapsible">
        <h4>Family Member</h4>
        <ul data-role="listview" data-inset="true">
           <li> <img src="C:\Users\acer\Desktop\SADAM\father.png" width="80" height="80">
            <h2>FATHER</h2>
          </li>
          <li>  <img src="C:\Users\acer\Desktop\SADAM\mother.png" width="80" height="80">
            <h2>MOTHER</h2>
          </li>
          <li><img src="C:\Users\acer\Desktop\SADAM\brother.png" width="80" height="80">
            <h2>BROTHER</h2>
          </li>		  
		  <li><img src="C:\Users\acer\Desktop\SADAM\bro.png" width="80" height="80">
            <h2>LITTLE BROTHER</h2>          
          </li>		  
		  <li><img src="C:\Users\acer\Desktop\SADAM\sis.png" width="80" height="80">
            <h2>ME</h2>        
          </li>
        </ul>
      </div>

<div data-role="collapsible">
<h1>Family background</h1>
 <ul data-role="listview" data-inset="true">
<li>Father's Name : Nik Farizu Bin Nik Mohd<br>
   Age           : 52 Years Old<br>
   Occupation    : Teacher
   </li>
<li>Mother's Name : Noor Aida Bt Dato' Hj Shafii<br>
   Age           : 50 Years Old<br>
   Occupation    : Teacher
   </li>
<li>Brother's Name : Nik Muhammad Farid Bin Nik Farizu<br>
   Age           : 21 Years Old<br>
   Occupation    : Student
   </li>
<li>Little Brother's Name : Nik Muhammad Fareez Bin Nik Farizu<br>
   Age           : 14 Years Old<br>
   Occupation    : Student
   </li>
   
<li>Me : Nik Siti Nur Aisyah Bin Nik Farizu<br>
   Age           : 20 Years Old<br>
   Occupation    : Student
   
   </li>
   </ul>
</div>
</br>
</br>
<a href="#page4" data-transition="flow">Go to Page 4</a>
</div>



<div data-role="footer">
<h2>&copy; Web Class 2023</h2>
</div>
</div>
</div>

<div data-role="page" id="page4" data-theme="g">
<div data-role="header">
<h1>Exam Result</h1>
<div data-role="navbar">
<ul>
<li> <a href="#page1" data-icon="grid">Personal Information</a> </li>
<li> <a href="#page2" data-icon="heart">Hobby</a> </li>
<li> <a href="#page3" data-icon="heart">Family Background</a> </li>
<li> <a href="#page4" data-icon="heart">Exam Result</a> </li>
</ul>
</div>
</div>

<div data-role="main" class="ui-content">
<center>
<img src="C:\Users\acer\Desktop\SADAM\poli.png" width="350" height="100">
<h1>My Exam Result</h1></center>

<div data-role="collapsible">
<h1>Semester 1</h1>
<center>
<img src="C:\Users\acer\Pictures\Screenshot (3.png"  width="820" height="200"></center>
</div>

<div data-role="collapsible">
<h1>Semester 2</h1>
<center>
<img src="C:\Users\acer\Pictures\Screenshot (2).png"  width="820" height="200"></center>
</div>

<div data-role="collapsible">
<h1>Semester 3</h1>
<center>
<img src="C:\Users\acer\Pictures\Screenshot (1).png"  width="820" height="200"></center>
</div>

<div data-role="collapsible">
<h1>Semester 4 (SOON)</h1>
<center>
<img src="C:\Users\acer\Pictures\Screenshot .png"  width="820" height="200"></center>
</div>



<div data-role="footer">
<h2>&copy; Web Class 2023</h2>
</div>
</div>
</div>



</body>
</html>
