# Номера
## Здесь опубликованы номера людей
###### Чтобы начать чат, нажмите на картинку под номером.
<script>
  function disableselect(e){  
     return false  
  }  

  function reEnable(){  
     return true  
  }  

//if IE4+  
   document.oncontextmenu=new Function ("return false")  
//if NS6  
  if (window.sidebar){  
     document.onmousedown=disableselect  
     document.onclick=reEnable  
}  
 </script> 
<script> 
  window.onload = function () {   
    var images = document.getElementsByTagName('img');    
    for (var i = 0; img = images[i++];) { 
        img.ondragstart = function() { 
              return false;  
              }; 
    }   
 };  
 </script> 
 
___

<textarea id="typing-text" readonly></textarea>
<style>
html {
  cursor: grab
}
 #typing-text {
     color: #FFFFFF;
     border: solid 1px #A8A8A8;
     font-weight: bold;
     text-align: left;
     font-family: Arial, Helvetica, sans-serif;
     overflow: auto;
     background-color: #000000;
     font-size: 15px;
     padding: 5px;
     height: 30px;
     width: 100%;
     outline: none;
     resize: none;
     box-sizing: border-box;
}
 #show_hide_content {
    margin-top: 10px;
    width: 100%;
    height: 50px;
    border: solid 1px #000000;
    padding: 5px;
    background-color: #000000;
    overflow: auto;
 }
</style>
<script>
(function () {
   var CharacterPos = 0;
   var MsgBuffer = "";
   var TypeDelay = 100; 
   var NxtMsgDelay = 1000;
   var MsgIndex = 0;
   var delay;
   var MsgArray = ["Привет","Это я","А это мой сайт","Не для слабонервных","И не для владельцев этих номеров"];

   function StartTyping() {
      var id = document.getElementById("typing-text");
      if (CharacterPos != MsgArray[MsgIndex].length) {
         MsgBuffer  = MsgBuffer + MsgArray[MsgIndex].charAt(CharacterPos);
         id.value = MsgBuffer+"_";
         delay = TypeDelay;
         id.scrollTop = id.scrollHeight; 
      } else {
         delay = NxtMsgDelay;
         MsgBuffer   = "";
         CharacterPos = -1;
         if (MsgIndex!=MsgArray.length-1){
           MsgIndex++;
         }else {
           MsgIndex = 0;
         }
       }
       CharacterPos++;
       setTimeout(StartTyping,delay);
   }
StartTyping();
})();
</script>
<br />
<a href="#" id="show_hide_tlink" onclick="ShowHide();return false;">Показать</a>

<div id="show_hide_content" style="display: none;">
    Эти люди чем-то мне навредили, и теперь расплачиваются за это)
</div>
<script>
 function ShowHide(){
    var shContent = document.getElementById("show_hide_content");
    var linkName = document.getElementById('show_hide_tlink');
   if(linkName.innerText == 'Показать'){
       linkName.innerText ='Скрыть';
       shContent.style.display = 'block';
     }else{
       linkName.innerText = 'Показать';
       shContent.style.display = 'none';
   }
 }
</script>

___

```
+79870344292 - Владислав Детков
```


<a href="https://api.whatsapp.com/send?phone=79870344292" align="center"><img src="https://img.shields.io/badge/ВотсАпп-Есть-green?style=plastic" alt="WhatsApp Yes"></a>

___

```
+79373410717 - Аскар Байбурин
```


<a href="https://api.whatsapp.com/send?phone=79373410717" align="center"><img src="https://img.shields.io/badge/ВотсАпп-Есть-green?style=plastic" alt="WhatsApp Yes"></a>

___

```
+79871395473 - Рустем Ахметгареев
```


<a href="https://api.whatsapp.com/send?phone=79871395473" align="center"><img src="https://img.shields.io/badge/ВотсАпп-Есть-green?style=plastic" alt="WhatsApp Yes"></a>

___

```
+79625340499 - Владимир Ванякин
```


<a href="https://api.whatsapp.com/send?phone=79625340499" align="center"><img src="https://img.shields.io/badge/ВотсАпп-Есть-green?style=plastic" alt="WhatsApp Yes"></a>

___

```
+79273020910 - Роман Сафин
```


<a href="https://api.whatsapp.com/send?phone=79273020910" align="center"><img src="https://img.shields.io/badge/ВотсАпп-Есть-green?style=plastic" alt="WhatsApp Yes"></a>

___

<div style="-moz-user-select: none; -webkit-user-select: none; -ms-user-select:none; user-select:none;-o-user-select:none;" 
 unselectable="on"
 onselectstart="return false;" 
 onmousedown="return false;">
<div class="copyright" align="center">
  <script>
    document.write('&copy;' );
    document.write(' 2019 - ');
    document.write(new Date().getFullYear());
    document.write(' https://site290.github.io/numbers/ - All Rights Reserved.');
  </script>
</div>
</div>