# recome
<!DOCTYPE html>
<html>
<head>

</head>
<style>
p.ex {
    
    margin-top: 0px;
    margin-bottom: 0px;
    margin-right: 50px;
    margin-left: 500px;
   }
p.exd {
    
    margin-top: 0px;
    margin-bottom: 0px;
    margin-right: 50px;
    margin-left: 350px;
  }
.box{
  margin: 50px auto;
  width: 500px;
  height: 50px;
   
}

.container-1{
  width: 500px;
  vertical-align: middle;
  white-space: nowrap;
  position: relative;
 border: 2px #7e7e7e;
}
.button {
    background-color: #7f7fff;
    border: none;
    color: white;
    padding: 7px 20px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 0px 0px;
    cursor: pointer;
}
</style>
<p class="ex"><img src="C:\Users\tarun.pc\Desktop\22\logo-quezx.png" alt="Mountain View" style="width:304px;height:150px;" align="middle"></p>     
<br>
<p style="color:#323232;"class="exd"><font size="7"> Job Skill Recommendation System</font></P>
<body  bgcolor="#939393">
<div class="box">
   <div class="container-1">
          <span class="icon><i class="fa fa-search"></i></span>
          <input type="search" id="mySearch" oninput="B()"placeholder="Search.." list="roles" style="width: 500px; height: 30px; ">
         <button class="button" onclick="A()">Go</button>
   </div>
</div>

<datalist id="roles">
</datalist>
<br>
<div  id="output"></div>

