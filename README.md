<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <?php
    $myname = "นัทธมน";
    $name = array("ชยางกูร","ไชยวัฒน์","วโรดม","อภิวิชญ์(4)","ชานนท์","นพดล","ชินกฤช","พงศ์พรณ์","พรเทพ","วรชัย","สรวิชญ์","ไชยวัฒน์(12)","วงศ์วริศ","คณิศร","ธนวัฒน์","แทนไท","ปรัญชัย","พัทธดนย์","สัณหณัฐ","จิรภัทร","จิรานุวัฒน์","สิปปกร","อชิรวัตติ์","ปณิทัศน์","กันตพัฒน์","ชุติเดช","วชิรวิชญ์","พุฒิเกียรติ","ศุภโชค","สุภาวิตา","พิมพ์ชนก","วรนัน","อภิชญา","สิรินดา","ปภาดา","ณัฐชา","ธัญชนก","กัญญวรา","นภัสสร");
    echo "$myname<br>";
    for ($i=0; $i<count($name); $i++)
    {
        echo "$name[$i]<br>"; 
    }
    ?>
</body>
</html>
