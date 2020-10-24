<!DOCTYPE html>

<html style="font-size: 50.02px;"><head>

    <meta charset="UTF-8">



    <meta http-equiv="X-UA-Compatible" content="ie=edge">

    <meta name="viewport" content="width=device-width, initial-scale=1">

    <title>电子假条</title>

    <script type="text/javascript">

        //JS监听浏览器文字大小代码

        //1rem=24px

        (function (doc, win) {

            var docEl = doc.documentElement,

                resizeEvt = 'orientationchange' in window ? 'orientationchange' : 'resize',

                recalc = function () {

                    var clientWidth = docEl.clientWidth;

                    if (!clientWidth) return;

                    docEl.style.fontSize = 20 * (clientWidth / 375) + 'px';

                };



            if (!doc.addEventListener) return;

            win.addEventListener(resizeEvt, recalc, false);

            doc.addEventListener('DOMContentLoaded', recalc, false);

        })(document, window);

    </script>

    <style type="text/css">

        * {

            margin: 0px;

            padding: 0px;

        }



        body, div, dl, dt, dd, ul, ol, li, h1, h2, h3, h4, h5, h6, pre, code, form, fieldset, legend, input, button, textarea, p, blockquote, th, td {

            margin: 0;

            padding: 0;

        }



        ul, li {

            list-style: none;

        }



        a {

            text-decoration: none;

            color: #000000;

        }



        body {

            font-family: "微软雅黑";

            /*font-size: 0.625;*/

            padding: 1rem 1rem;

        }



        img {

            display: block;

            max-width: 100%;

        }



        .clean {

            clear: both;

            width: 0px;

            height: 0px;

            line-height: 0px;

            overflow: hidden;

        }



        header {

            display: flex;

            flex-direction: row;

            align-items: center;

            padding-bottom: 0.5rem;

            border-bottom: 1px solid #f3f3f3;

        }



        .header-rt {

            font-size: 0.8rem;

            font-weight: bold;

            margin-bottom: 0.1rem;

        }



        .header-rb {

            font-size: 0.6rem;

        }



        header img {

            width: 2rem;

            height: 2rem;

            margin-right: 0.6rem;

            border-radius: 50%;

        }



        .list-cont {

            padding: 0.6rem 0;



        }



        .list {

            font-size: 0.7rem;

            display: flex;

            flex-direction: row;

            line-height: 1.3rem;

        }



        .lisft {

            width: 6rem;

        }



        .listr {

            color: #6c6c6c;

        }



        .list-center {

            font-size: 0.7rem;

            padding: 0.6rem 0;

            border-bottom: 1px solid #f3f3f3;

            color: #6c6c6c;

        }



        .list-center-ul li {

            margin: 0.3rem 0;

        }



        .foot {

            display: flex;

            flex-direction: row;

            align-items: center;

            padding-top: 0.5rem;

            padding-bottom: 0.5rem;

        }



        .foot img {

            width: 2rem;

            height: 2rem;

            margin-right: 0.6rem;

            border-radius: 50%;

        }



        .foot-r {

            flex: 1;

        }



        .foot-rb {

            font-size: 0.6rem;

            display: flex;

            justify-content: space-between;

            flex: 1;

            flex-direction: column;

        }



        .foot-rb > div {

            display: flex;

            justify-content: space-between;

        }



        .foot-context {

            color: #6c6c6c;

            font-size: 0.7rem;

            line-height: 1.3rem;

            text-indent: 2em;

        }



    </style>

</head>

<body>

<header>

     <img src="https://bkimg.cdn.bcebos.com/pic/5bafa40f4bfbfbed8b68d1fe79f0f736afc31f79?x-bce-process=image/resize,m_lfit,w_220,limit_1">

    <div class="header-r">

        <div class="header-rt">唐英昆</div>

        <div class="header-rb">计算机科学与技术学院(计科（金融信息化）1801班)</div>

    </div>

</header>

<section>

    <ul class="list-cont">

        <li class="list">

            <div class="lisft">请假事由:</div>

            <div class="listr">事假</div>

        </li>

        <li class="list">

            <div class="lisft">请假开始时间:</div>

            <div class="listr" id="div_timer start"></div>

        </li>

        <li class="list">

            <div class="lisft">请假结束时间:</div>

            <div class="listr" id="div_timer end">

            </div>

        </li>

        <li class="list">

            <div class="lisft">紧急联系人:</div>

            <div class="listr">

              13256253363

            </div>

        </li>

        <li class="list">

            <div class="lisft">申请时间:</div>

            <div class="listr" id="div_timer shen"></div>

        </li>

        <li class="list">

            <div class="lisft">是否离校:</div>

            <div class="listr">

                    不离校

            </div>

        </li>

    </ul>

</section>

<section class="list-center">

  事假，找同学

</section>

<ul class="list-center-ul">

</ul>

<section class="foot">

    <img src="https://wx.qlogo.cn/mmopen/vi_32/nvQiaZvBgILfwhedzQWPFattGBTfTjYx8Nq3qBJ4w1aqI6oe2wibiaFarlzlSsVbCiaMWESzXdenXbgDNS54cwKFFA/132">

    <div class="foot-r">

        <div class="header-rt">张建</div>

        <div class="foot-rb">

            <div>

            <div>

                审批通过

            </div>

    <div id ="div_timer jian"></div>

    </div>

    <div>同意</div>

    </div>

    </div>

</section>

<section class="foot">

    <img src="https://wx.qlogo.cn/mmopen/vi_32/DYAIOgq83eqVr1IbMhqrLaIBcKf6fbHk8g7oia7ugsXib0fNmM2j2knoJ0nnaicMjezEVcsD8KL1NxiciclPMxfA2jw/132">

    <div class="foot-r">

        <div class="header-rt">吕海霞</div>

        <div class="foot-rb">

            <div>

            <div>

                审批通过

            </div>

    <div id="div_timer lv"></div>

    </div>

    <div></div>

    </div>

    </div>

</section>

<div class="clean"></div>





</body></html>



<script type="text/javascript">

    //获取系统时间

    function showTime() {

    nowtime = new Date();

 

    year = nowtime.getFullYear();//年

    month = nowtime.getMonth() + 1;//月

    day = nowtime.getDate();//日

 

    //吕

    document.getElementById("div_timer lv").style = "white-space:pre;";

    document.getElementById("div_timer lv").innerText = year + "-" + p(month) + "-" + p(day) + " " +"09" + ":" + "16" ;

    //建

    document.getElementById("div_timer jian").style = "white-space:pre;";

    document.getElementById("div_timer jian").innerText = year + "-" + p(month) + "-" + p(day) + " " +"09" + ":" + "10" ;

    //申请

    document.getElementById("div_timer shen").style = "white-space:pre;";

    document.getElementById("div_timer shen").innerText = year + "-" + p(month) + "-" + p(day) + " " +"08" + ":" + "09" ;

    //start

    document.getElementById("div_timer start").style = "white-space:pre;";

    document.getElementById("div_timer start").innerText = year + "-" + p(month) + "-" + p(day) + " " +"7" + ":" + "00" ;

    //end

    document.getElementById("div_timer end").style = "white-space:pre;";

    document.getElementById("div_timer end").innerText = year + "-" + p(month) + "-" + p(day) + " " +"23" + ":" + "30" ;





    }

    setInterval("showTime()", 1000);

    //月日时分秒小于10补0

    function p(s) {

    return s < 10 ? '0' + s : s;

    }

    </script>
