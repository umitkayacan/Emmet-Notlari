Etiket Adı + Tab Tuşu
p ve tab tuşu
! ve tab tuşu 

a{Tıkla}
Etiketin tanımını oluşturuyor
<a href="">Tıkla</a>
h1{deneme}
ul+tab
ul>li + tab
<h1>deneme</h1>

Tagların tipleri için
input:email
input:text
bunlara name ve id vermek için 
input[name=abc id=abc type=password]
<input type="password" name="abc" id="abc">

+ OPERATÖRÜ

tek satırda yazıp birden fazla etiket oluşturmak için
h1+p ve tab'a bas

h1+p+h5
<h1></h1>
<p></p>
<h5></h5>


* OPERATÖRÜ
ul>li + tab
<ul>
	<li></li>
</ul>
ul>li*10
<ul>
	<li></li>
	<li></li>
	<li></li>
	<li></li>
	<li></li>
	<li></li>
	<li></li>
	<li></li>
	<li></li>
	<li></li>
</ul>

> (BÜYÜKTÜR ) operatörü
etiketin içerisine anlamında kullanırız. 
div>p+p+h5+a*5
<div>
	<p></p>
	<p></p>
	<h5></h5>
	<a href=""></a>
	<a href=""></a>
	<a href=""></a>
	<a href=""></a>
	<a href=""></a>
</div>

ul>li>a*5
<ul>
	<li>
		<a href=""></a>
		<a href=""></a>
		<a href=""></a>
		<a href=""></a>
		<a href=""></a>
	</li>
</ul>

CLASS VE ID TANIMLAMA

div.classadi
<div class="classadi"></div>

div.#idadi
<div class="" id="idadi"></div>

veya 
classadi
#idadi

olarak da kullanabiliriz

Birden fazla class atama işlemi için

.div.text.container
<div class="div text container"></div>

LOREM IPSUM EKLEME
lorem + tab

p>lorem + tab

10 kelimelik lorem 
p>lorem10
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Debitis, iure.</p>

p*3>lorem

<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptas fugiat, culpa aliquam voluptate, deserunt inventore aliquid doloribus. Est sequi quas dolorem provident cumque, et quod nemo at labore obcaecati excepturi.</p>
<p>Veritatis iste ipsum magni eveniet sed suscipit, cupiditate nesciunt impedit laudantium, nam optio aperiam quibusdam sapiente velit et ea repudiandae provident explicabo veniam sint! Error qui nesciunt quia tenetur voluptatibus!</p>
<p>Reiciendis quibusdam accusamus cupiditate sequi architecto similique corrupti consequuntur exercitationem iste, ad sed nostrum alias, illo ea libero rerum vero vel velit tempora quidem molestiae esse, delectus officiis doloremque. Illum.</p>

# NUMARALANDIRMA
img[src=images/resim$.jpg]*5

<img src="images/resim1.jpg" alt="">
<img src="images/resim2.jpg" alt="">
<img src="images/resim3.jpg" alt="">
<img src="images/resim4.jpg" alt="">
<img src="images/resim5.jpg" alt="">
