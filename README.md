<!DOCTYPE html>
<html lang="gu">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
   <title>સ્વામિનારાયણ સ્તુતિ</title>
   <style>
       body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    text-align: center;
    padding: 10px;
    max-width: 100%;
    margin: 0 auto;
}

.visible-content {
    font-size: 16px;
    margin-bottom: 15px;
    word-wrap: break-word;
}

.hidden-content {
    display: none;
    font-size: 16px;
    background-color: #e0f7fa;
    padding: 5px;
    border-radius: 5px;
    margin: 5px 0;
    word-wrap: break-word;
}

.toggle-button {
    background-color: #4CAF50;
    color: white;
    border: none;
    padding: 8px 15px;
    border-radius: 5px;
    cursor: pointer;
    font-size: 14px;
    margin: 4px;
    touch-action: manipulation;
}

@media screen and (max-width: 600px) {
    body {
        padding: 5px;
    }
    .visible-content {
        font-size: 14px;
    }
    .hidden-content {
        font-size: 14px;
    }
    .toggle-button {
        padding: 6px 12px;
        font-size: 12px;
    }
}
   </style>
</head>
<body>
   <div class="visible-content">
       અન્તર્યામિ
       <span id="line1" class="hidden-content">પરાત્પરં હિતકરં,</span>
       <button class="toggle-button" onclick="showContent('line1')">show</button>
       <span id="line2" class="hidden-content">સર્વોપરી શ્રીહરિ,</span>
       <button class="toggle-button" onclick="showContent('line2')">show</button><br>

       સાકારં
       <span id="line3" class="hidden-content">પરબ્રહ્મ સર્વશરણમ્,</span>
       <button class="toggle-button" onclick="showContent('line3')">show</button>
       <span id="line4" class="hidden-content">કર્તા દયાસાગરમ્।</span>
       <button class="toggle-button" onclick="showContent('line4')">show</button><br>

       આરાધ્યં
       <span id="line5" class="hidden-content">મમ ઇષ્ટદેવ પ્રકટં,</span>
       <button class="toggle-button" onclick="showContent('line5')">show</button>
       <span id="line6" class="hidden-content">સર્વાવતારી પ્રભુ,</span>
       <button class="toggle-button" onclick="showContent('line6')">show</button><br>

       વન્દે
       <span id="line7" class="hidden-content">દુઃખહરં સદા સુખકરં,</span>
       <button class="toggle-button" onclick="showContent('line7')">show</button>
       <span id="line8" class="hidden-content">શ્રીસ્વામિનારાયણમ્॥</span>
       <button class="toggle-button" onclick="showContent('line8')">show</button><br>

  
       <div>॥ શ્રી ગુણાતીતાનંદ સ્વામી મહારાજ સ્તુતિ ॥</div>
       સાક્ષાદ્
       <span id="line9" class="hidden-content">અક્ષરધામ દિવ્ય પરમં,</span>
       <button class="toggle-button" onclick="showContent('line9')">show</button>
       <span id="line10" class="hidden-content">સેવારતં મૂર્તિમાન્,</span>
       <button class="toggle-button" onclick="showContent('line10')">show</button><br>

સર્વાધાર
<span id="line11" class="hidden-content">સદા સ્વરોમ-વિવરે,</span>
<button class="toggle-button" onclick="showContent('line11')">show</button>
<span id="line12" class="hidden-content">બ્રહ્માંડ-કોટી-ધરમ્।</span>
<button class="toggle-button" onclick="showContent('line12')">show</button><br>

ભક્તિ
<span id="line13" class="hidden-content">ધ્યાન કથા સદૈવ કરણં,</span>
<button class="toggle-button" onclick="showContent('line13')">show</button>
<span id="line14" class="hidden-content">બ્રહ્મસ્થિતિદાયકમ્,</span>
<button class="toggle-button" onclick="showContent('line14')">show</button><br>

વન્દે 
<span id="line15" class="hidden-content">અક્ષરબ્રહ્મ પાદકમલં,</span>
<button class="toggle-button" onclick="showContent('line15')">show</button>
<span id="line16" class="hidden-content">ગુણાતીતાનન્દનમ્॥</span>
<button class="toggle-button" onclick="showContent('line16')">show</button><br>
  <div>॥  શ્રી ભગતજી મહારાજ સ્તુતિ ॥</div>
શ્રીમન્
<span id="line17" class="hidden-content">નિર્ગુણ મૂર્તિ સુંદર તનુ,</span>
<button class="toggle-button" onclick="showContent('line17')">show</button>
<span id="line18" class="hidden-content">અધ્યાત્મ-વાર્તારતમ્,</span>
<button class="toggle-button" onclick="showContent('line18')">show</button><br>

દેહાતીત
<span id="line19" class="hidden-content">દશા અખંડ-ભજનં,</span>
<button class="toggle-button" onclick="showContent('line19')">show</button>
<span id="line20" class="hidden-content">શાન્તં ક્ષમાસાગરમ્।</span>
<button class="toggle-button" onclick="showContent('line20')">show</button><br>

આજ્ઞા-પાલન
<span id="line21" class="hidden-content">-તત્પરં ગુણગ્રહી,</span>
<button class="toggle-button" onclick="showContent('line21')">show</button>
<span id="line22" class="hidden-content">નિર્દોષમૂર્તિ સ્વયમ્,</span>
<button class="toggle-button" onclick="showContent('line22')">show</button><br>

વન્દે
<span id="line23" class="hidden-content">પ્રાગજીભક્ત-પાદકમલં,</span>
<button class="toggle-button" onclick="showContent('line23')">show</button>
<span id="line24" class="hidden-content">બ્રહ્મસ્વરૂપં ગુરુમ્॥</span>
<button class="toggle-button" onclick="showContent('line24')">show</button><br>
       <!-- Continue this pattern for all 28 lines -->
       <div>॥ શ્રી શાસ્ત્રીજી મહારાજ સ્તુતિ ॥</div>
       શુદ્ધોપાસન
<span id="line25" class="hidden-content">મન્દિરં સુરચનમ્,</span>
<button class="toggle-button" onclick="showContent('line25')">show</button>
<span id="line26" class="hidden-content">સિદ્ધાન્ત-રક્ષાપરમ્,</span>
<button class="toggle-button" onclick="showContent('line26')">show</button><br>

સંસ્થા-સ્થાપન
<span id="line27" class="hidden-content">દિવ્ય-કાર્ય-કરણં,</span>
<button class="toggle-button" onclick="showContent('line27')">show</button>
<span id="line28" class="hidden-content">સેવામયં જીવનમ્।</span>
<button class="toggle-button" onclick="showContent('line28')">show</button><br>

નિષ્ઠા
<span id="line29" class="hidden-content">નિર્ભયતા સુકષ્ટસહનં,</span>
<button class="toggle-button" onclick="showContent('line29')">show</button>
<span id="line30" class="hidden-content">ધૈર્યં ક્ષમાધારણમ્,</span>
<button class="toggle-button" onclick="showContent('line30')">show</button><br>

શાસ્ત્રી
<span id="line31" class="hidden-content">યજ્ઞપુરુષદાસ-ચરણં,</span>
<button class="toggle-button" onclick="showContent('line31')">show</button>
<span id="line32" class="hidden-content">વન્દે પ્રતાપી ગુરુમ્॥</span>
<button class="toggle-button" onclick="showContent('line32')">show</button><br>
<div>॥  શ્રી યોગીજી મહારાજ સ્તુતિ ॥</div>
વાણી
<span id="line33" class="hidden-content">અમૃતપૂર્ણ હર્ષકરણી,</span>
<button class="toggle-button" onclick="showContent('line33')">show</button>
<span id="line34" class="hidden-content">સંજીવની માધુરી,</span>
<button class="toggle-button" onclick="showContent('line34')">show</button><br>

દિવ્યં
<span id="line35" class="hidden-content">દૃષ્ટિપ્રદાન દિવ્ય હસનં,</span>
<button class="toggle-button" onclick="showContent('line35')">show</button>
<span id="line36" class="hidden-content">દિવ્યં શુભં કીર્તનમ્।</span>
<button class="toggle-button" onclick="showContent('line36')">show</button><br>

બ્રહ્માનંદ
<span id="line37" class="hidden-content">પ્રસન્‍ન સ્નેહરસિતં,</span>
<button class="toggle-button" onclick="showContent('line37')">show</button>
<span id="line38" class="hidden-content">દિવ્યં કૃપાવર્ષણમ્,</span>
<button class="toggle-button" onclick="showContent('line38')">show</button><br>

યોગીજી
<span id="line39" class="hidden-content">ગુરુ જ્ઞાનજીવન પદે,</span>
<button class="toggle-button" onclick="showContent('line39')">show</button>
<span id="line40" class="hidden-content">ભાવે સદા વન્દનમ્॥</span>
<button class="toggle-button" onclick="showContent('line40')">show</button><br>
<div>॥  શ્રી પ્રમુખસ્વામી મહારાજ સ્તુતિ ॥</div>
વિશ્વે
<span id="line41" class="hidden-content">વૈદિક ધર્મ મર્મ મહિમા,</span>
<button class="toggle-button" onclick="showContent('line41')">show</button>
<span id="line42" class="hidden-content">સત્સંગ વિસ્તારકમ્,</span>
<button class="toggle-button" onclick="showContent('line42')">show</button><br>

વાત્સલ્યં
<span id="line43" class="hidden-content">કરુણા અહો જનજને,</span>
<button class="toggle-button" onclick="showContent('line43')">show</button>
<span id="line44" class="hidden-content">આકર્ષણમ્ અદ્‍ભુતમ્।</span>
<button class="toggle-button" onclick="showContent('line44')">show</button><br>

દાસત્વં
<span id="line45" class="hidden-content">ગુરુભક્તિ નિત્ય ભજનં,</span>
<button class="toggle-button" onclick="showContent('line45')">show</button>
<span id="line46" class="hidden-content">સંવાદિતા સાધુતા,</span>
<button class="toggle-button" onclick="showContent('line46')">show</button><br>

નારાયણસ્વરૂપ
<span id="line47" class="hidden-content">સ્વામી પ્રમુખં,</span>
<button class="toggle-button" onclick="showContent('line47')">show</button>
<span id="line48" class="hidden-content">વન્દે ગુરું મુક્તિદમ્॥</span>
<button class="toggle-button" onclick="showContent('line48')">show</button><br>
<div>॥ શ્રી મહંતસ્વામી મહારાજ સ્તુતિ ॥</div>
દિવ્યં
<span id="line49" class="hidden-content">સૌમ્યમુખારવિન્દ સરલં,</span>
<button class="toggle-button" onclick="showContent('line49')">show</button>
<span id="line50" class="hidden-content">નેત્રે અમીવર્ષણમ્,</span>
<button class="toggle-button" onclick="showContent('line50')">show</button><br>

નિર્દોષં
<span id="line51" class="hidden-content">મહિમામયં સુહૃદયં,</span>
<button class="toggle-button" onclick="showContent('line51')">show</button>
<span id="line52" class="hidden-content">શાન્તં સમં નિશ્ચલમ્।</span>
<button class="toggle-button" onclick="showContent('line52')">show</button><br>

નિર્માનં
<span id="line53" class="hidden-content">મૃદુ દિવ્યભાવ સતતં,</span>
<button class="toggle-button" onclick="showContent('line53')">show</button>
<span id="line54" class="hidden-content">વાણી શુભા નિર્મલા,</span>
<button class="toggle-button" onclick="showContent('line54')">show</button><br>

વન્દે
<span id="line55" class="hidden-content">કેશવજીવનં મમ ગુરું,</span>
<button class="toggle-button" onclick="showContent('line55')">show</button>
<span id="line56" class="hidden-content">સ્વામી મહન્તં સદા॥</span>
<button class="toggle-button" onclick="showContent('line56')">show</button><br>
   </div>
   <script>
       function showContent(contentId) {
           const element = document.getElementById(contentId);
           element.style.display = "inline";
           setTimeout(() => {
               element.style.display = "none";
           }, 1000);
       }
   </script>
</body>
</html>
