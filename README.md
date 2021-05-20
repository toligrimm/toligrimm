
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;200;300;400;500;600;700;800&display=swap" rel="stylesheet"><style>

.container {
  font-family: 'Montserrat', sans-serif;
  font-size: 14px;
  font-weight: 400;
  background: white;
  box-shadow: 2px 4px 8px 2px  rgba( 31, 38, 135, 0.37 );
  backdrop-filter: blur( 0.6px );
-webkit-backdrop-filter: blur( 0.6px );
  border-radius: 10px;
  border: 1px solid rgba( 255, 255, 255, 0.18 );
  width: 100%;
  height: auto;
  display: flex;
  align-items: flex-end;
  justify-content: space-between;
}

.navbar {
  background: none;
  margin-bottom: 3px;
  right: 40%;

}

#contacts {

justify-content: flex-end;
text-align: right;
font-size: 11px;
color: grey;
margin-right: 18px;
display: flex;
}

.dropdown {
  float: left;
}

  
.dropbtn:hover {
  font-family: 'Montserrat', sans-serif;
  font-size: 13px;
  font-weight: 400;
  background-color: white;
  color: black;
  text-align: center;
  height: 30px;
box-shadow: 4px 8px 12px 4px rgba( 31, 38, 135, 0.17 );
}
  
.dropdown .dropbtn {
  font-family: 'Montserrat', sans-serif, 200;
  font-size: 13px;
  font-weight: 500;
  border: none;
  outline: none;
  color: white;
  width: 17em;
  background-color: #ff9601;
  border: 1px;
  border-radius: 8px;
  font-family: inherit;
  margin-left: 10px;
  margin-bottom: 5px;
  height: 35px;
  cursor: pointer;
}

.dropdown:hover .dropbtn {
  font-family: 'Montserrat';
  font-size: 13px;
  font-weight: 500;
  background-color: white;
  color: black;
  text-align: center;
  height: 35px;
box-shadow: 4px 8px 12px 4px rgba( 31, 38, 135, 0.17 );
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: white;
  min-width: 160px;
  box-shadow: 2px 2px 6px 4px rgba( 31, 38, 135, 0.37 );
  z-index: 1;
  border-radius: 6px;
  margin-left: 10px;
  font-size: 13px;
  font-family: 'Montserrat';
}

.dropdown-content a {
  font-family: 'Montserrat', sans-serif;
  font-size: 13px;
  float: none;
  color: black;
  padding: 8px 8px;
  text-decoration: none;
  display: block;
  text-align: left;
  
}

.dropdown-content a:hover {
  font-family: 'Montserrat', sans-serif;
  font-size: 13px;
  background-color: #ff9601;
  color: white;
  border-radius: 6px;
  box-shadow: 0 8px 32px 0 rgba( 31, 38, 135, 0.37 );
}

.dropdown:hover .dropdown-content {
  display: block;
}

.tab {  
  float: left;
  width: 20%;
  height: 600px;
  justify-content: flex-start;
  margin-top: 40px;
  border-radius: 10px;
}

.tab button {
  font-family: "Montserrat";
  display: flex;
  background-color: white;
  color: black;
  padding: 10px;
  width: 100%;
  border: none;
  outline: none;
  text-align: left;
  cursor: pointer;
  transition: 0.3s;
  font-size: 14px;
  border-radius: 10px;
  margin-top: 5px;
  margin-bottom: 5px;
  box-shadow: 0 4px 12px 0 rgba( 31, 38, 135, 0.37 );
  overflow: hidden;
  height: auto;
}


.tab button:hover {
font-family: "Montserrat";
  background-color: #ff9601;
   box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
   border-radius: 6px;
   color: white;
}


.tab button.open {
font-family: "Montserrat";
  background-color: #ff9601;
  color: white;
}


.tabcontent {
  background: rgba( 255, 255, 255, 0.55 );
  box-shadow: 0 8px 32px 0 rgba( 31, 38, 135, 0.37 );
  border-radius: 10px;
  font-family: "Montserrat";
  float: left;
  padding: 0px 12px;
  border: none;
  width: 70%;
  border-left: none;
  height: 600px;
  margin-left: 15px;
  margin-top: 45px;
  overflow: scroll;
  justify-content: center;
  display: flex;
}

.polaroid {
  width: 180px;
  height: 180px;
  background-color: white;
  box-shadow: 0 4px 8px 0 rgba(31, 38, 135, 0.37), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  margin-bottom: 25px;
  float: left;
  margin-left: 20px;
  margin-right: 20px;
  border-radius: 10px;

}

.button {
  font-family: "Montserrat";
  font-size: 14px;
  font-weight: 400;
  background-color: #ff9601;
  color: white;
  border: none;
  border-radius: 6px;
  box-shadow: 0 4px 12px 0 rgba( 31, 38, 135, 0.37 );
  cursor: pointer;
  height: 40px;
}

.button:hover {
  font-family: "Montserrat";
  background-color: white;
  color: black;
}

#post {
  text-align: center;
  padding: 5px 20px;
  margin: auto;
  }
  
#exline {
  text-align: center;
  padding: 5px 20px;
  }
  
#dpd {
  text-align: center;
  padding: 5px 20px;
  }
  
#alemtat {
  text-align: center;
  padding: 5px 20px;
  }
  
img {
   height: 120px;
   width: 120px;
   margin-left: 28px;
   margin-top: 10px;
}

#info {
  font-family: 'Montserrat';
  font-size: 14px;
  font-weight: 400;
  background: white;
  color: black;
  border: 1px solid #ff9601;
  border-radius: 6px;
  box-shadow: 0 4px 12px 0 rgba( 31, 38, 135, 0.37 );
  padding: 10px 20px;
  margin-left: 0;
  width: 93.5%;
}
 #delivery td {
  text-align: left;
  padding: 12px;

}

#delivery tr {
  font-family: Montserrat;
  font-size: 14px;
  background: white;
  color: black;
}

#delivery tr.header,  {
  background-color: #ff9601;
}
#delivery {
  font-family: Montserrat;
  font-size: 14px;
  width: 100%;
  background: #ff9601;
  color: white;
  border-radius: 10px;
}

#delivery td {
  font-family: Montserrat;
  border: 1px solid #ddd;
  padding: 8px;
  font-size: 14px;
}
#delivery th {
  padding: 8px;
  font-family: Montserrat;
  font-size: 14px;
}


#delivery th {
  font-family: Montserrat;
  padding-top: 12px;
  padding-bottom: 12px;
  text-align: left;
  background-color: #ff9601;
  color: white;

}

li {
  font-family: Montserrat;
  font-size: 14px;
  font-weight: 400;
}
  h3 { 
  font-size: 18px;
  margin: 10px;
  font-weight: 600;
  font-family: Montserrat;
}

p { 
  font-size: 14px;
  margin: 10px;
  font-weight: 400;
  font-family: Montserrat;
}
</style>
<div class="container">
  <div class="navbar">
    <div class="dropdown">
      <a href="https://omarket.kz/lerning/?COURSE_ID=1&LESSON_ID=73&LESSON_PATH=1.73"><button class="dropbtn">Общие условия по доставке</button></a>
    <div class="dropdown-content">
      <a href="https://omarket.kz/lerning/?COURSE_ID=1&LESSON_ID=74&LESSON_PATH=1.73.74">География и сроки доставки Магазина.</a>
      <a href="https://omarket.kz/lerning/?COURSE_ID=1&LESSON_ID=75&LESSON_PATH=1.73.75">Отказ от получения посылки</a>
      <a href="https://omarket.kz/lerning/?COURSE_ID=1&LESSON_ID=76&LESSON_PATH=1.73.76">Ответственность за доставку товаров</a>
      <a href="https://omarket.kz/lerning/?COURSE_ID=1&LESSON_ID=77&LESSON_PATH=1.73.77">Претензии</a>
    </div>
    </div>
    <div class="dropdown">
 <a href="https://omarket.kz/lerning/?COURSE_ID=1&LESSON_ID=81&LESSON_PATH=1.7.81"><button class="dropbtn">Условия доставки для Заказчиков</button></a>
    </div>
    <div class="dropdown">
 <a href= "https://omarket.kz/lerning/?COURSE_ID=1&LESSON_ID=78&LESSON_PATH=1.13.22.78"><button class="dropbtn">Условия доставки для Поставщиков</button></a><div class="dropdown-content">
 <a href="https://omarket.kz/lerning/?COURSE_ID=1&LESSON_ID=78&LESSON_PATH=1.13.22.78">Ограничения по доставке груза</a> <a href="https://omarket.kz/lerning/?COURSE_ID=1&LESSON_ID=79&LESSON_PATH=1.13.22.79">Работа с заказом и вызов курьера</a> 
 <a href="https://omarket.kz/lerning/?COURSE_ID=1&LESSON_ID=80&LESSON_PATH=1.13.22.80">Возврат Товара</a>
      </div>
    </div>
  </div>

  <div id="contacts">
     Работа службы технической поддержки: <br>
     Пн-Пт: 9:00-19:00.<br>
     +7 (7172) 27-04-01<br>
     help@omarket.kz
  </div>
</div>
<div class="tab">
 <button class="tablinks" onclick="openTab(event, 'tk')" id="defaultOpen">Транспортные компании</button> <button class="tablinks" onclick="openTab(event, 'fromKATO')">География забора и доставки грузов</button> <button class="tablinks" onclick="openTab(event, 'deliverydays')">Сроки доставки грузов</button>
</div>
<div id="tk" class="tabcontent">
  <h3>География и сроки доставки Магазина</h3>
 <br>
  <p>
     В настоящий момент партнерами Магазина по доставке являются:
  </p>
  <ul>
    <li>АО "Казпочта"</li>
    <li>ТОО «ExLine»</li>
    <li>ТОО “ДПД Казахстан”</li>
    <li>ТОО "АлемТат"</li>
  </ul>
 <br>
 <p id="info">
     ⓘ Список партнеров по доставке постоянно расширяется и дифференцируется.
  </p>
  <br>
  <div class="polaroid">
 <img alt="post.kz" src="https://post.kz/react/static/media/logo_blue.292d6f7d.svg">
    <div id="post">
      <div class="text">
 <a href="https://post.kz" target="_blank"><button class="button">Перейти на сайт КазПочты</button></a>
      </div>
    </div>
  </div>
  <div class="polaroid">
 <img alt="exline.kz" src="https://fixtech.kz/images/exline.jpg">
    <div id="exline">
 <a href="https://exline.kz" target="_blank"><button class="button">Перейти на сайт Exline</button></a>
    </div>
  </div>
  <div class="polaroid">
 <img alt="dpd.kz" src="http://www.logo-designer.co/wp-content/uploads/2015/03/lippincott-logo-design-GeoPost-DPDgroup.png">
    <div id="dpd">
 <a href="http://www.dpd.kz" target="_blank"><button class="button">Перейти на сайт DPD</button></a>
    </div>
  </div>
  <div class="polaroid">
 <img alt="alemtat.kz" src="http://www.alemtat.kz/wp-content/themes/Alemtat/images/logo_sn.png">
    <div id="alemtat">
 <a href="http://www.alemtat.kz" target="_blank"><button class="button">Перейти на сайт Alem Tat</button></a>
    </div>
  </div>
</div>
<div id="fromKATO" class="tabcontent">
  <h3>География забора и доставки грузов</h3>

    <br>
  <table id="delivery" cellspacing="0">
  <tbody>
     <tr class="header">
    <th style="width:40%;" id="delivery">Откуда можно забрать</th>
    <th style="width:40%;" id="delivery">Откуда можно забрать
</th>

  </tr>
  
  <tr>
    <td>
      <p>
         Актау
      </p>
    </td>
    <td rowspan="19">
      <p align="center">
         Более 3000 городов и других населенных пунктов по территории Республики Казахстан.
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Актобе
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Алматы
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Атырау
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Балхаш
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Караганда
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Кокшетау
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Костанай
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Кызылорда
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Нур-Султан
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Павлодар
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Петропавловск
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Семей
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Талдыкорган
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Тараз
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Уральск
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Усть-Каменогорск
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Шымкент
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Экибастуз
      </p>
    </td>
  </tr>
  </tbody>
  </table>
</div>
<div id="deliverydays" class="tabcontent">
  <h3>Сроки доставки грузов</h3>
 <br>
  <p id="info">
     ⓘ По городу (только в пределах городов забора, по таблице выше) – 1 рабочий день.
  </p><br>
  <p>
     Между основными городами (из любого в любой):
  </p>
  <table id="delivery" cellspacing="0">
  <tbody>
  <tr>
  <th style="width:40%;" id="delivery">Откуда забрать</th>
  <th style="width:40%;" id="delivery">Куда доставить</th>
      <th style="width:40%;" id="delivery">Срок доставки</th>
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Актау
      </p>
    </td>
    <td>
      <p>
         Актау
      </p>
    </td>
    <td rowspan="19">
      <p align="center">
         2-8 рабочих дней
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Актобе
      </p>
    </td>
    <td>
      <p>
         Актобе
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Алматы
      </p>
    </td>
    <td>
      <p>
         Алматы
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Атырау
      </p>
    </td>
    <td>
      <p>
         Атырау
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Балхаш
      </p>
    </td>
    <td>
      <p>
         Балхаш
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Караганда
      </p>
    </td>
    <td>
      <p>
         Караганда
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Кокшетау
      </p>
    </td>
    <td>
      <p>
         Кокшетау
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Костанай
      </p>
    </td>
    <td>
      <p>
         Костанай
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Кызылорда
      </p>
    </td>
    <td>
      <p>
         Кызылорда
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Нур-Султан
      </p>
    </td>
    <td>
      <p>
         Нур-Султан
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Павлодар
      </p>
    </td>
    <td>
      <p>
         Павлодар
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Петропавловск
      </p>
    </td>
    <td>
      <p>
         Петропавловск
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Семей
      </p>
    </td>
    <td>
      <p>
         Семей
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Талдыкорган
      </p>
    </td>
    <td>
      <p>
         Талдыкорган
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Тараз
      </p>
    </td>
    <td>
      <p>
         Тараз
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Уральск
      </p>
    </td>
    <td>
      <p>
         Уральск
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Усть-Каменогорск
      </p>
    </td>
    <td>
      <p>
         Усть-Каменогорск
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Шымкент
      </p>
    </td>
    <td>
      <p>
         Шымкент
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Экибастуз
      </p>
    </td>
    <td>
      <p>
         Экибастуз
      </p>
    </td>
  </tr>
  </tbody>
  </table>
 <br>
 <br>
  <table id="delivery" cellspacing="0">
  <tbody>
  <tr>
  <th style="width:40%;" id="delivery">Откуда забрать</th>
      <th style="width:40%;" id="delivery">Куда доставить</th>
      <th style="width:40%;" id="delivery">Срок доставки</th>
      
  </tr>
  <tr>
    <td>
      <p>
         Актау
      </p>
    </td>
    <td rowspan="19">
      <p align="center">
         Более 3000 городов и других населенных пунктов по территории Республики Казахстан.
      </p>
    </td>
    <td rowspan="19">
      <p align="center">
      </p>
      <p align="center">
      </p>
      <p align="center">
      </p>
      <p align="center">
      </p>
      <p align="center">
      </p>
      <p align="center">
      </p>
      <p align="center">
      </p>
      <p align="center">
      </p>
      <p align="center">
      </p>
      <p align="center">
      </p>
      <p align="center">
         3-15 рабочих дней
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Актобе
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Алматы
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Атырау
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Балхаш
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Караганда
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Кокшетау
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Костанай
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Кызылорда
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Нур-Султан
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Павлодар
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Петропавловск
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Семей
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Талдыкорган
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Тараз
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Уральск
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Усть-Каменогорск
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Шымкент
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <p>
         Экибастуз
      </p>
    </td>
  </tr>
  </tbody>
  </table>
 <br>
  <p id="info">
     ⓘ В некоторых случаях (перевозка в зимний период, перевозка отдельных видов товаров, требующих специальных условий доставки, нарушения Поставщиком ограничений по доставке и т.д.) срок может быть продлен.
  </p>
  <div id="info">
     ⓘ Все сроки указаны в рабочих днях, без учета:
    <ul>
      <li> дня приема груза</li>
      <li> выходных дней</li>
      <li> праздничных дней</li>
    </ul>
  </div>
  <p id="info">
     ⓘ Срок доставки отсчитывается только с момента фактического забора груза Перевозчиком, а не с даты вызова курьера.
  </p>
</div>
<script>
  function openTab(evt, tabName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" open", "");
  }
  document.getElementById(tabName).style.display = "block";
  evt.currentTarget.className += " open";
}

document.getElementById("defaultOpen").click();

</script>
