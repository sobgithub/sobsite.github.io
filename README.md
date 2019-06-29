<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Flexbox CSS3 в одном видео за 20 минут!</title>
    <style>
            .container-1{
                display: flex;
                /* выравнивает блоки по высоте контента */
                align-items: flex-start;
            }
            .container-1 div{
                padding: 10px;
                border: 1px solid silver;
            }
            .box-1{
                /* flex: 1; */
                /* регулируем ширину блока */
                flex: 2;
                /* меняет местами блоки */
                order:2;
            }
            .box-2{
                flex: 2;
                order:1;
            }
            .box-3{
                flex: 1;
                order: 3;
            }
    </style>
            
</head>

<body>
 <div class="container-1">
    <div class="box-1">
        <h3>Box 1</h3>
        <p>Lorem ipsum dolor sit amet, consectetur 
           adipisicing elit. Distinctio repellat aspernatur
           fugit commodi ipsa expedita voluptas voluptates, 
           quis nihil ut.</p>
    </div>
    <div class="box-2">
        <h3>Box 2</h3>
        <p>Lorem ipsum dolor sit amet, consectetur 
                adipisicing elit. Distinctio repellat aspernatur
                fugit commodi ipsa expedita voluptas voluptates, 
                quis nihil ut.</p>
    </div>
    <div class="box-3">
        <h3>Box 3</h3>
        <p>Lorem ipsum dolor sit amet, consectetur 
                adipisicing elit. Distinctio repellat aspernatur
                fugit commodi ipsa expedita voluptas voluptates, 
                quis nihil ut.
                fugit commodi ipsa expedita voluptas voluptates, 
                quis nihil ut.
        </p>
    </div>
 </div>
</body>
</html>
