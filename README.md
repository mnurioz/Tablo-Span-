<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>Document</title>
    
    <style>
        table,tr,td,th{
            border: 1px solid black;
            text-align: center;
            height: 100px;
            width: 300px;
            border-radius: 5px;
        }

    </style>


</head>
<body>

    <table>
        <tr>
            <th>A1</th>
            <th>A2</th>
            <th>A3</th>
            <th>A4</th>
        </tr>

        <tr>
            <td>AaA</td>
            <td>BbB</td>
            <td colspan="2">CcC</td>
            
        </tr>

        <tr>
            <td>aAa</td>
            <td>bBb</td>
            <td>cCc</td>
            <td rowspan="4">dDd</td>
        </tr>

        <tr>
            <td>AAA</td>
            <td>BBB</td>
            <td>CCC</td>
            
        </tr>
        
    </table>
    
</body>
</html>
