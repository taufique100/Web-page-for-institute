# Web-page-for-institute

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BoxShadow_textShadow</title>
    <style>
        .container {
            display: flex;
        }

        .card {
            margin: 25px 20px;
            padding: 11px 20px;
            /* border: 2px solid rgb(29, 105, 29); */

            background-color: rgb(246, 176, 85);
            box-shadow: 14px 17px 10px grey;
            /*Syntax:-
             box-shadow: offset-x offset-y bllur-radius spread-radius colour */
            /*box-shadow: inset 3px 5px ;*/


        }

        .card h2 {
            text-shadow: 3px 4px 2px rgb(109, 101, 101);

        }

        header {
            display: flex;
            flex-direction: column;
        }

        .navbar1 {
            display: flex;
            flex-direction: column;
            /*padding: 20px;*/
            border-radius: 10px solid red;

        }

        .navigation {
            display: flex;
            padding: 11px 15px;
            margin: -7px -5px;
            border-radius: 12px;
            background-color: black;
        }

        .item {
            list-style: none;
            padding: 0px 25px;
            margin: 0px 10px;
            color: white;

        }

        .navbar1 li {
            text-decoration: none;
            border: 2px;
        }

        body input {
            margin: 12px 615px;
            padding: 8px 24px;
            border: 2px solid rgb(12, 12, 12);
            border-radius: 10px;
            display: flex;
        }

        body input:hover {
            background-color: rgb(194, 248, 246);
        }

        .navbar1 li:hover {
            background-color: #423d3d;
        }
        #list1,#list2,#list3,#list4 {
            border-radius: 4px;
            font-size: 20px;
        }
        header::before{
            content: "";
            background: url('https://source.unsplash.com/user/c_v_r') no-repeat center center/ cover;
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            opacity: 0.4;

        }
    </style>
</head>

<body >
    <header>
        <div class="navbar1">
            <ul class="navigation">
                <li class="item" id="list1">Home</li>
                <li class="item" id="list2">Services</li>
                <li class="item" id="list3">About Us</li>
                <li class="item" id="list4">Contact Us </li>
            </ul>
        </div>
    </header>
    <div class="Search">
        <input type="search" id="search" placeholder="Search">
    </div>

    <div class="container">
        <div class="card" id="card-1">
            <h2>C++ course</h2>
            <p> This is the complete course of c++ which will start from beiging of august months. Lorem ipsum dolor sit
                amet consectetur adipisicing elit. Maxime aliquid praesentium in, ad eligendi omnis eos quas mollitia
                esse temporibus pariatur facilis dicta eum ut deleniti! Quis ullam, ipsam harum blanditiis facilis animi
                explicabo?</p>
        </div>
        <div class="card" id="card-2">
            <h2>JavaScript course</h2>
            <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. In, perspiciatis quis ipsa autem fuga sapiente
                accusantium adipisci quod quaerat. Inventore dicta reprehenderit esse illo placeat ipsum, harum iste
                quae repellat ad nulla a vel!</p>
        </div>
        <div class="card" id="card-3">
            <h2>NodeJs course</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sequi ad minus omnis facilis, dolore id,
                consequuntur quas quos ipsa voluptates dignissimos fugit obcaecati, et praesentium architecto? Pariatur
                optio quos dolorem doloribus nam totam quis!</p>
        </div>
    </div>
</body>

</html>
