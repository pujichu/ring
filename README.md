
<?php
     $info = array(


          "user"=> array(
          	         array(1,"zhangsan" ,18,"nan"),
                     array(2,"lisi",22,"nv"),
                     array(3,"wangwu",11,"nan")
                     ),
           "score"=>array(
                     array(1,99,88,77),
                     array(2,79,94,61),
                     array(3,65,91,59)
                     ),
            "connect"=>array(
                     array(1,'110','aaa@qq'),
                     array(2,'121','www@qq'),
                     array(3,'119','sdw@qq')
                     )    



           );
  echo $info["connect"][1][2];

     echo "<pre>";
       print_r($info);
     echo "</pre>";

?>
