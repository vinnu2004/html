<!DOCTYPE html>
<html>  
<head>
    <script type="text/javascript" src="emp.js"></script>
</head>
    <body>        
        <form name="employee" onsubmit="getallData()">
        <table border="1" align="center">
        <tr><td>
 
        <table cellpadding="10"> 
            <tr>
               <td align="center" colspan="2"><h1>Employee Details</h1></td>
            </tr>
 
 
        <tr>
         <th>Title:</th> 
         <td>
            <select name="Title" required>
                <option value="">Title</option>
                <option value="Mr.">Mr.</option>
                <option value="Mrs.">Mrs.</option>
                <option value="Ms.">Ms.</option>
            </select>           
         </td>
        </tr>
        <tr>
            <th>FirstName:</th>
            <td> <input type="text" name="fcode"  pattern="[A-Za-z]{,15}" required/></td>
        </tr>   
 
 
 
        <tr>
            <th>LastName:</th>
            <td> <input type="text" name="lcode"  pattern="[A-Za-z]{,15}" required/></td>
        </tr>   
 
 
 
            <tr>
            <th>Gross Salary:</th>
            <td> <input type="text" name="gcode" pattern="[0-9]{1,}" title="Gross salary should be a positive number" required/></td>
        </tr>   
 
 
 
            <tr>
            <th>Address:</th>
            <td> <textarea name="add" cols="40" rows="5" Title="Fill the address" required/></textarea></td>
        </tr>       
 
    <tr>
            <td align="center" colspan="2"><input type="submit"  value="Salary Slip"/></td>  
</tr>           
 
 
        </table>
</td></tr>
</table>
</form>
</body>
</html>
