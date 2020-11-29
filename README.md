<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>log in</title>
<style type="text/css">
body {background-image: url("backfround2.jpg") ;
	}
#log{
	height:20px;}
#log p{text-align:center;
	   font-size: 20px;
	color: #EEEEEE
	}
table{ 
	background:url("bodyground1.jpg") no-repeat;
	border-collapse: collapse;
	font-family:Segoe, "Segoe UI", "DejaVu Sans", "Trebuchet MS", Verdana, "sans-serif";
	font-size:15px;
	color:#E6D40F;
	margin:auto;
	margin-top: 0 auto;
	border:1px #000000;
	}
td{
	
   
	border: 1px solid #000000;
	padding:20px;
	height:1px;
	}
	.one{width:200px }
	.two{width: 400px}
	.pho{height: 100px}
</style>
</head>

<body>

<div id="log">
	<p> 用户注册</p>
</div>
	<table>
	<tr>
		<td width="230" class='one'>账号</td>
		<td width="430" class="two">
			
	  <input type="text" name="firstname">
			
		</td>
	</tr>
	<tr>
		<td height="20">姓名</td>
	  <td><form><input type="text" name="secondname"></form></td>
	</tr>
	<tr>
		<td>密码</td>
		<td><form>     <input type="password" name="psw"></form> </td>
	</tr>
	<tr>
		<td>密码确认</td>
		<td><form><input type="password" name="repsw">
			</form></td>
	</tr>
	<tr>
		<td>性别</td>
		<td><form>
			<input type="radio" name="sex" value="male" checked>男 <input type="radio" name="sex" value="female">
			女
		</form></td>
	</tr>
	<tr>
		<td>出生年月</td>
		<td><form>
			<select name="years">
<option value="choice one" selected="selected">-请选择年份-</option>
<option value="yone">2001</option>
<option value="ytwot">2002</option>
<option value="ythree">2000</option>
</select>
<select name="months">
<option value="choice two">-请选择月份-</option>
<option value="mone">1月</option>
<option value="mtwo">2月</option>
<option value="mthree">3月</option>
</select></form></td>
	</tr>
	<tr>
		<td>爱好</td>
		<td><form>
			<input type="checkbox" name="intres" value="study">学习
			<input type="checkbox" name="intres" value="sport">运动
			<input type="checkbox" name="intres" value="intnet">上网
			<input type="checkbox" name="intres" value="read">阅读
		</form></td>
	</tr>
	<tr>
		<td>学院</td>
		<td><form>
<select name="college">
<option value="choice">-请选择院系-</option>
<option value="gy">管理学院</option>
<option value="cl">材料学院</option>
<option value="jd">机电学院</option>
</select>
		</form></td>
	</tr>
	<tr>
		<td>专业班级</td>
		<td><form>
			<input type="text" name="firstname">
		</form></td>
	</tr>
	<tr>
		<td>文件上传</td>
		<td>
			<form action="UploadFile.ashx" method="post" enctype="multipart/form-data">
    <input type="file" name="fileUpload" />
    <input type="submit" value="上传文件" />
    </form>
		</td>
	</tr>
	<tr>
	  <td class="pho">个人头像</td>
		<td>
		<img src=mmexport1567408817043.jpg width="150" height="200"></td>
	</tr>
	<tr>
		<td colspan="2" align="center">
			<form>
		  <input type="submit" value="确认">     
		<input type="Reset" value="重置">
			</form>
		</td >
	</tr>
		
	</table>
</body>
</html>
