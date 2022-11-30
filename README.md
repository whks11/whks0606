<!DOCTYPE html>
<html>
<head>
 <meta charset="utf-8">
 <meta name="viewport" content="width=device-width, initial-scale=1">
 <style type="text/css">
  * {
   margin: 0;
   padding: 0;
  }
  table {
   margin: 60px auto;
  }
  td {
   padding: 5px;
  }
  td:first-child {
   text-align: center;
  }
 </style>
 <title></title>
</head>
<body>
 <div>
  <table border="2px" cellspacing="0" cellpadding="1">
   <th colspan="2">
    信&nbsp;息&nbsp;统&nbsp;计&nbsp;表
   </th>
   <tr>
    <td width="10px">姓&nbsp;名:</td>
    <td><input type="text" name="name"></td>
   </tr>
   <tr>
    <td>年&nbsp;龄:</td>
    <td><input type="text" name="j"></td>
   </tr>
   <tr>
    <td>性&nbsp;别:</td>
    <td><input type="radio" name="sex" value="1">男<input type="radio" name="sex" value="0">女</td>
   </tr>
   <tr>
    <td>爱&nbsp;好:</td>
    <td><input type="checkbox" name="hobby" value="1">旅游<br>
    <input type="checkbox" name="hobby" value="2">登山<br>
    <input type="checkbox" name="hobby" value="3">健身<br>
    <input type="checkbox" name="hobby" value="4">上网<br>
    <input type="checkbox" name="hobby" value="5">游泳</td>
   </tr>
   <tr>
    <td>学&nbsp;历:</td>
    <td>
     <select name="degree">
      <option value="">--请选择--</option>    
      <option value="1">专科</option>    
      <option value="2">本科</option>    
      <option value="3">硕士</option>    
      <option value="4">博士及以上</option>
     </select>
    </td>
   </tr>
   <tr>
    <td>自&nbsp;我&nbsp;介&nbsp;绍:</td>
    
   </tr>
   <tr align="center">
    <td colspan="2"><input type="submit" value="提交">
    <input type="reset" value="重置"></td>
   </tr>
  </table>
 </div>
</body>
</html>
