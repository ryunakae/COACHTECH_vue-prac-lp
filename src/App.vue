<template>
  <div id="app">
    <Header></Header>
    <main>
      <div id="div1">
        <h1>機械ではできない仕事を</h1>
        <div class="news_block">
          <h2>news</h2>
          <div>
            <time>2019/01/01</time>
            <p class="news_title">ニュースタイトルがここに入ります。３月の決算報告書</p>
          </div>
        </div>
      </div>
      <div id="div2">
        <div class="mission_paragraph">
          <h1>お客様のために進化する成長企業であり続ける</h1>
          <p>顧客主導型のサービスを提供する企業として、お客様の会社経営に必要なサービスと情報を提供し続ける企業支援会社を目指します。企業が現在直面している「勝ち残るため」の戦略を提供できる会社として、ホームページをはじめ、各種マーケッティングをご提供いたします。</p>
          <a href="#"><div>ミッション詳細</div></a>
        </div>
        <img src="./assets/mission-img.jpg" alt="mission-img" id="mission_img">
      </div>
      <div id="div3">
        <h1 id="div3_h1">service</h1>
        <div id="service_div1" class="service_div">
          <h2>web制作事業</h2>
          <h3>コーチングのミッション</h3>
          <p>ユーザーが求める物を分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の作成実績があります</p>
          <a href="#"><div>サービス詳細</div></a>
        </div>
        <img src="./assets/service2.jpg" alt="service2" id="right_img">
        <img src="./assets/service1.jpg" alt="service1" id="left_img">
        <div id="service_div2" class="service_div">
          <h2>web制作事業</h2>
          <h3>コーチングのミッション</h3>
          <p>ユーザーが求める物を分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の作成実績があります</p>
          <a href="#"><div>サービス詳細</div></a>
        </div>
        <div id="blank"> </div>
      </div>
      <div id="div4">
        <div id="company">
          <h1>company</h1>
          <h2>会社概要</h2>
        </div>
        <div id="recruit">
          <h1>recruit</h1>
          <h2>採用情報</h2>
        </div>
      </div>
      <div id="FAQ">
        <h1>FAQ</h1>
        <h2>良くある質問</h2>
      </div>
      <div id="div5">
        <h1>contact</h1>
        <h2>お問い合わせ</h2>
        <h1 class="strong">お気軽にお問い合わせください。</h1>
        <p>資料請求・お問い合わせなどなんでも気軽にお問い合わせください。お仕事のご連絡もお問い合わせページに飛んでいただいて、入力フォームにご記入お願いいたします。</p>
        <a href="#"><div>お問い合わせへ</div></a>
      </div>
    </main>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Footer
  }
}
</script>

<style>
/* リセットcss LP制作コピペ*/
html, body, div, span, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
abbr, address, cite, code,
del, dfn, em, img, ins, kbd, q, samp,
small, strong, sub, sup, var,
b, i,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, figcaption, figure,
footer, header, hgroup, menu, nav, section, summary,
time, mark, audio, video {
    margin:0;
    padding:0;
    border:0;
    outline:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
}

body {
    line-height:1;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}

article,aside,details,figcaption,figure,
footer,header,hgroup,menu,nav,section {
    display:block;
}

nav ul {
    list-style:none;
}

blockquote, q {
    quotes:none;
}

blockquote:before, blockquote:after,
q:before, q:after {
    content:'';
    content:none;
}

a {
    margin:0;
    padding:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
    text-decoration: none;
}

/* change colours to suit your needs */
ins {
    background-color:#ff9;
    color:#000;
    text-decoration:none;
}

/* change colours to suit your needs */
mark {
    background-color:#ff9;
    color:#000;
    font-style:italic;
    font-weight:bold;
}

del {
    text-decoration: line-through;
}

abbr[title], dfn[title] {
    border-bottom:1px dotted;
    cursor:help;
}

table {
    border-collapse:collapse;
    border-spacing:0;
}

/* change border colour to suit your needs */
hr {
    display:block;
    height:1px;
    border:0;  
    border-top:1px solid #cccccc;
    margin:1em 0;
    padding:0;
}

input, select {
    vertical-align:middle;
}

/* ブロック１ */
#div1 {
  background: url(./assets/eyecatch.jpg) no-repeat;
  background-size: cover;
  background-position: center;
  color: #f2f2f2;
  height: 500px;
  display: flex;
}
#div1 h1 {
  font-size: 3rem;
  font-weight: bold;
  font-style: italic;
  position: relative;
  top: 280px;
  left: 10%;
  margin-right: 15vw;
}
.news_block {
  height: 50px;
  align-self: flex-end;
  position: absolute;
  right: 0;
  display: flex;
  flex-direction: row-reverse;
  align-items: center;
  background-color: black;
}
.news_block h2 {
  color: #f2f2f2;
  width: 120px;
  text-align: center;
  font-size: 0.75rem;
}
.news_block div {
  background-color: #f2f2f2;
  color: #000;
  height: 50px;
}
.news_title {
  padding: 5px;
  padding-left: 15px;
  padding-right: 15px;
  width: 500px;
  font-size: 0.9rem;
}
time {
  font-size: 0.75rem;
}

/* ブロック２ */
#div2 {
  height: 400px;
  margin-bottom: 120px;
  background-color: #000;
  color: #f2f2f2;
  display: flex;
  align-items: center;
}
#mission_img {
  height: 320px;
  width: auto;
  position: absolute;
  right: 8vw;
  top: 700px;
}
.mission_paragraph {
  z-index: 1;
  position: relative;
  left: 10%;
  width: 70%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
.mission_paragraph h1 {
  font-size: 1.5rem;
  margin-bottom: 20px;
}
.mission_paragraph p {
  font-size: 1rem;
  margin-bottom: 20px;
  line-height: normal;

}
.mission_paragraph a {
  color: #000
}
.mission_paragraph div {
  padding: 8px;
  padding-left: 15px;
  padding-right: 15px;
  width: fit-content;
  background-color: #f2f2f2;
  font-size: 0.75rem;
}

/* ブロック３ */
#div3 {
  background-color: #cccccc;
  display: grid;
  grid-template-columns: repeat(10, 1fr);
  grid-auto-rows: minmax(70px, auto);
}
#div3_h1 {
  grid-column: 1 / -1;
  text-align: center;
  margin: 20px;
  font-size: 1.25rem;
}
#service_div1 {
  grid-column: 3 / -5;
  grid-row: 3 / 4 ;
}
#right_img {
  grid-column: 6 / -1;
  grid-row: 2 / 5;
}
#left_img {
  grid-column: 1 / -6;
  grid-row: 6 / 9;
}
#service_div2 {
  grid-column: 5 / -3;
  grid-row: 7 / 8 ;
}
#blank {
  grid-row: 9 / 10;
}
.service_div {
  background-color: #fff;
  z-index: 1;
  height: auto;
  padding: 30px;
  font-size: 0.9rem;
  display: flex;
  flex-direction: column;
  line-height: 120%;
}
.service_div h2 {
  margin: 7px;
}
.service_div h3 {
  margin: 7px;
}
.service_div p {
  margin: 7px;
}
.service_div a {
  margin: 5px;
  color: #000;
  align-self: flex-end;
}
.service_div div {
  border: solid 1px #000;
  padding: 5px;
  padding-left: 20px;
  padding-right: 20px;
  width: fit-content;
}
#div3 img {
  width: 50vw;
}

/* ブロック４ */
#div4 {
  margin-top: 70px;
  margin-bottom: 70px;
  display: flex;
  justify-content: space-between;
  color: #f2f2f2;
}
#div4 div {
  width: 48vw;
  height: 250px;
  background-size: cover;
  background-position: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  font-size: 1.5rem;
}
#div4 div h2 {
  font-size: 1rem;
  margin: 10px;
}
#company {
  background: url(./assets/company.jpeg);
}
#recruit {
  background: url(./assets/recruit.jpg);
}

/* FAQ */
#FAQ {
  margin: 0 auto;
  margin-bottom: 70px;
  width: 60vw;
  height: 70px;
  display: flex;
  background-color: black;
  color: #f2f2f2;
  text-align: center;
  align-items: center;
}
#FAQ h1 {
  width: 10vw;
  font-size: 1.5rem;
}
#FAQ h2 {
  width: 50vw;
  font-size: 1rem;
}

/* ブロック５ */
#div5 {
  height: 400px;
  background: url(./assets/contact-bg.jpg);
  background-size: cover;
  background-position: center;
  color: #f2f2f2;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
#div5 h1 {
  font-size: 1.5rem;
}
#div5 h2 {
  font-size: 1rem;
  margin: 8px;
}
.strong {
  font-size: 1.75rem;
  margin: 15px;
}
#div5 p {
  font-size: 0.9rem;
  margin: 15px;
  margin-left: 15%;
  margin-right: 15%;
  text-align: center;
  line-height: 120%;
}
#div5 a {
  color: #f2f2f2;
}
#div5 div {
  font-size: 1rem;
  border: solid 1px #f2f2f2;
  padding: 5px;
  padding-left: 15px;
  padding-right: 15px;
}
@media (max-width: 768px) {
  
  html {
    font-size: 80%;
  }

  #hamburger {
    width: 40px;
    height: 40px;
    position: absolute;
    cursor: pointer;
    z-index: 100;
    top: 15px;
    right: 20px;
    transition: 0.4s;
  }
  
  #hamburger span {
    position: absolute;
    left: 2px;
    display: block;
    width: 35px;
    height: 2px;
    background-color: #fff;
    transition: 0.8s;
  }
  
  #hamburger span:nth-of-type(1) {
    top: 10px; /* ハンバーガーメニューの1本目の棒 */
  }
  
  #hamburger span:nth-of-type(2) {
    top: 20px; /* ハンバーガーメニューの2本目の棒 */
  }
  
  #hamburger span:nth-of-type(3) {
    top: 30px; /* ハンバーガーメニューの3本目の棒 */
  }
  
  .site_nav {
    display: none; /* デスクトップのナビを消す */
  }


  .news_block {
    width: 100vw;
  }
  .news_block h2 {
    width: 20vw;
  }
  .news_title {
    width: 80vw;
  }

  #mission_img {
    width: 62.57vw;
    height: auto;
    top: calc(1020px - 41.61vw);
  }

  #div3 img {
    width: 100%;
  }
  #service_div1 {
    grid-column: 2 / -2;
    grid-row: 3 / 5 ;
  }
  #right_img {
    grid-column: 2 / -2;
    grid-row: 2 / 3;
  }
  #left_img {
    grid-column: 2 / -2;
    grid-row: 6 / 7;
  }
  #service_div2 {
    grid-column: 2 / -2;
    grid-row: 7 / 9 ;
  }
  #blank {
    grid-row: 9 / 10;
  }

  #div4 {
    display: block;
  }
  #div4 div {
    width: 100%;
    height: 200px;
  }

  .footer_logo {
    margin: 0 auto;
    text-align: center;
  }
}
</style>
