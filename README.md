# StudentRepo
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>login page</title>
</head>
<link rel="stylesheet" href="login.css">
<body>
   <h1> <center> WELCOME TO LOGIN PAGE</center></h1>
    <hr>
    <div id="container">
        <div id="input">
Username:
 <input type="text" id="uname" placeholder="username"><br><br>
Password:
<input type="password" id="pass" placeholder="password"><br><br>
Cell No: &nbsp;
<input type="number" id="cell"><br><br>
Email ID:
<input type="text" id="email">
<br><br>
<button type="submit" id="btn" onclick= "login()">SUBMIT</button>
</div></div>
</body>
<script>
    function login(){
        var name = document.getElementById('uname').value;
        var passe = document.getElementById('pass').value;
        var cellno =document.getElementById('cell').value;
        var emai = document.getElementById('email').value;
        if(name == ""){
        alert("please enter username")
        uname.focus()
        }
        else if(passe == ""){
            alert("enter password")
            pass.focus()
        }
        else if (cellno =="") {
            alert("enter cell no.")
            cell.focus()
            } 
            else if(emai == ""){
                alert("enter your email")
                email.focus()
            }
            else if(name == "word" && passe == "1234"){
            location.assign("index.html")
        }
        else{
            alert("enter valied detail")
        }
    }
</script>
<div class="separator" style="clear: both;"><a href="https://1.bp.blogspot.com/-cBs9vLh2sZc/YQgeM2AOp_I/AAAAAAAAARY/TfpxKvqB-Q49A850r6IAk1nBkg47Gls2ACNcBGAsYHQ/s0/bgimage2.jpg" style="display: block; padding: 1em 0px; text-align: center;"><img alt="" border="0" data-original-height="500" data-original-width="786" src="https://1.bp.blogspot.com/-cBs9vLh2sZc/YQgeM2AOp_I/AAAAAAAAARY/TfpxKvqB-Q49A850r6IAk1nBkg47Gls2ACNcBGAsYHQ/s0/bgimage2.jpg" /></a></div><h1 style="text-align: center;"><span style="color: #2b00fe;">DO YOU MEAN BY SCIENCE ?</span></h1><h3 style="text-align: left;"><span style="color: #2b00fe;">&nbsp;</span><span style="color: #800180;">The word "science " derived from a Latin word "scientia" which means</span><span style="color: #2b00fe;"> </span><span style="color: #38761d;">KNOWLEDGE.</span></h3><section class="book" id="book"></section>
</html>