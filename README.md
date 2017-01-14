# JS-SplitPage-Tutorial
用javascript達成網頁分頁的教學
### Intro
控制getSplitPage()函式內四個參數即可控制分頁的呈現  
後端僅需 SELECT COUNT(*) FROM page 並更新 count 變數即可

<pre>
//物品總數
var count = 36;
//當前頁面
var onpage = 7; 
//一個頁面顯示幾個物品
var file = 5;
//一個頁面顯示前後幾個頁面
var range = 5;
</pre>
### Demo
實際執行結果  

<img src="https://github.com/unromanticman/JS-SplitPage-Tutorial/blob/master/shot/demo01.png" width="350"/>  
 
<img src="https://github.com/unromanticman/JS-SplitPage-Tutorial/blob/master/shot/demo02.png" width="350"/>  

<img src="https://github.com/unromanticman/JS-SplitPage-Tutorial/blob/master/shot/demo03.png" width="350"/>  

### 思路  
只需要透過資料庫取得物品總數即可達成分頁  

此外每頁的物品呈現也只要透過limit來取即可
