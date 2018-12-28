<template>
  <div id="app">
    <indicator></indicator>
    <head-bar>
      <a slot="logo" href="https://ubrand.udn.com/ubrand/index"></a>
      <a href="https://udn.com/upf/newmedia/2018_data/newedu/future/index.html">未來人才力</a>
      <a href="https://udn.com/upf/newmedia/2018_data/newedu/index.html" target="_blanck">誰殺了想像力</a>
    </head-bar>
    <animation-cover  :animationConfig1="srcRWD(coverMob1, coverWeb1)" aniamtionRef1="cover1"  aniamtionRef2="cover2">
      <h1 class="coverTitle1">活得更像人</h1>
      <h2 class="coverTitle2">不被未來世界淘汰的六大能力</h2>
    </animation-cover>
    <content-container>
      <share href="https://udn.com/upf/newmedia/2018_data/newedu/future/index.html"></share>
      <p><br></p>
      <h2>你想像的未來是什麼？</h2>
      <p><br></p>
      <p>專家學者預言，未來有近半的職業會被人工智慧取代；未來是AI時代，也是一個焦慮的世代，我們憂慮被職場淘汰，也憂慮下一代，在課堂上學不到面對未來的能力。</p>
      <p><br></p>
      <p>「將來的工作完全與現在不同，但你卻不一定會被淘汰，」永齡教育基金會董事長郭守正擘劃可能的未來世界，人工智慧以及機器人可以分擔勞動密集、龐大計算的工作，<span class="highlight">「人類不用害怕被取代，要學習如何運用機器人，讓我做更大、更有價值的事情。」</span></p>
      <p><br></p>
    </content-container>
    <column-one description="永齡教育基金會董事長郭守正認為，只要孩子眼中有亮光，就表示找到點燃熱情的志向，也會願意找解方。家長應該放手，讓孩子自己面對未知的世界。攝影／余承翰" :src="images.imgWeb0" :srcWeb="images.imgWeb0"></column-one>
    <content-container>
      <p>永齡教育基金會過去十年深耕希望小學，協助低學習成就的孩子，最能明白孩子的學習需求。郭守正認為，不需要焦慮擔心，培養孩子有解決問題、思考能力，以及溝通說故事的能力。</p>
      <p><br></p>
      <p>「我們必須活得更像人，才能與機器人競爭」，教育部政務次長姚立德說，AI時代，創意、關懷他人的工作不僅不會被淘汰，反而需求增加，走向精緻化。</p>
      <p><br></p>
    </content-container>
    <anchor title="AI世代衝擊">
      <animation-cover :animationConfig1="srcRWD(imgMob6, imgWeb6)" aniamtionRef1="image6">
          <h3>未來的世界是什麼樣貌？</h3>
      </animation-cover>
    </anchor>
     <content-container>
      <p><br></p>
      <p>姚立德說，大量運用科技的時代，人與人之間的接觸會變得格外昂貴，<span class="highlight">人工智慧無法取代的是創意或是個人化服務，像是諮詢、關懷、美容等相關產業，這些工作會被保留甚至走向精緻化。</span></p>
      <p><br></p>
      <p>面對資訊量大量累積的時代，共玩創作總監吳彥杰建議，要學習面對未來的能力，首先要看每個人想像的未來是什麼樣貌，孩子根據他的家庭背景與性向，想像他會在哪個未來定位上，需要什麼能力，再回過頭來為未來做準備。</p>
      <p><br></p>
      <p><br></p>
      <div class="main-title">
        <h3>不被機器人淘汰</h3>
        <h3>需要具備的六大能力</h3>
        <ul>
          <li class="green-line"></li>
          <li class="red-line"></li>
          <li class="black-line"></li>
        </ul>
      </div>
      <p><br></p>
      <anchor title="未來6大能力">
        <h3><span class="titleNumber">1</span>跨領域學習能力</h3>
      </anchor>
      <p><br></p>
      <p>未來資訊科技蓬勃發展，只專精於一個專業領域是不夠的，因為這個專業領域可能因為科技變化隨時會被取代，因此未來的公司對於人才的需求，也不會只有一種專業能力。<span class="highlight">未來人才會被期待要懂多個領域，並有綜整專業知識的能力。</span></p>
      <p><br></p>
      <p>成功大學資訊工程學系教授蘇文鈺舉例，這個世界上可能因為某個角落的某個人，做了某些事情，導致你三年後失業，而且完全無法阻止。</p>
      <p><br></p>
      <p>蘇文鈺說，因此在快速變動的時代，唯有滾動式的學習才有辦法面對，未來產生新的工作時，才能因應職場的變化。吳彥杰說，因應未來，要不斷的學習，如果覺得學習是苦差事，那就完了，「學什麼不重要，重點是想學」。</p>
      <p><br></p>
    </content-container>
    <column-one :src="images.imgMob1" :srcWeb="images.imgWeb1"></column-one>
    <content-container>
      <h3><span class="titleNumber">2</span>解決問題的能力</h3>
      <p><br></p>
      <p>「當小朋友眼中出現亮光時，你知道他自己會解決這個問題，他不會抱怨或覺得吃苦，這樣的事情就適合他們做。」郭守正認為，教育沒有標準答案，家長或老師不需要提供孩子或年輕人答案。他們會自己觀察，找到讓他們感興趣的問題，然後學習尋找資源、工具，並且自己動手解決。</p>
      <p><br></p>
      <p>郭守正強調，學習不只是在教室裡，家長與老師要學著放手，只要把適性、多元的平台準備好，讓孩子自由自主發揮。</p>
      <p><br></p>
      <p>「希望小學每年協助3000位學生，至少有一成的學生透過適性多元教育的過程，擁有解決問題的自信心，」郭守正認為，每個孩子都擁有潛在能力，只要給他們解決問題的自信心，「下一次再碰到問題時，不會退縮逃避，願意馬上動腦，想辦法解決問題。」</p>
      <p><br></p>
      <h3><span class="titleNumber">3</span>接收與分析資訊的能力</h3>
      <p><br></p>
      <p>20年前你能想像有 GOOGLE 嗎？只要鍵入關鍵字，資訊躍然眼前，未來人工智慧會幫人類分析更多資料，因此要有接收與分析資訊的能力。</p>
      <p><br></p>
      <p>姚立德說，以前長輩總愛說「小孩子有耳無嘴」，但在大量資訊充斥的時代，應該告訴孩子不要人云亦云，要有自己的看法，也訓練孩子要有批判性思維，在大量資訊中，懂得獨立思考、選擇判斷。</p>
      <p><br></p>
    </content-container>
    <column-one :src="images.imgMob2" :srcWeb="images.imgWeb2"></column-one>
    <content-container>
      <h3><span class="titleNumber">4</span>說故事的能力</h3>
      <p><br></p>
      <p>在未來，人不只與機器人搶工作，人與人彼此間的競爭也會更激烈，不想被取代，要有良好的口語文字表達能力，在溝通之前要先學習把腦中的想法講出來。</p>
      <p><br></p>
      <p>這幾年，永齡教育基金會開始投入創新教育領域，郭守正觀察到，很多youtuber、年輕人，都具備「溝通與說故事的能力」。他說，很多youtuber很年輕，小學生只要會拍攝素材、整理資料，他們就能製作影片，表達他們的訴求，這就是與社會溝通、說故事的能力。</p>
      <p><br></p>
      <p>共玩創作總監吳彥杰認為，未來人才必須用有效率、爭取眼球的方式將事情傳達出去，才有機會對關心的社群產生影響力。姚立德說，也應有國際移動力，讓自己有的能力與特質，不會因為到了別的國家，經歷不同的語言與文化就大打折扣。</p>
      <p><br></p>
      <h3><span class="titleNumber">5</span>關懷他人的能力</h3>
      <p><br></p>
      <p>全球孩童創意行動挑戰總監、印度河濱學校校長吉蘭‧貝兒‧瑟吉認為，當孩子不是被告知要做什麼，而是自己選擇要做什麼，當他們觀察周遭環境後，就會有好奇心，一起討論如何解決問題就會感受到想像力與創意，跟他人分享、陳述故事，就有自我表達能力。</p>
      <p><br></p>
      <p>她也認為，同理心是使人類跟其他動物不一樣的核心，因為有同理心，可以讓彼此合作，世界變得更加和善，但同理心不會憑空而來，需要從小的時候，不斷的引導與練習。</p>
      <p><br></p>
    </content-container>
    <column-one :src="images.imgMob3" :srcWeb="images.imgWeb3"></column-one>
    <content-container>
      <h3><span class="titleNumber">6</span>創造力</h3>
      <p><br></p>
      <p>「創造力是什麼？創造力就是無中生有。」成大教授蘇文鈺這幾年在偏鄉教孩子寫程式，他認為，創造力不是「教」出來的，學會寫程式也不代表具備創造力。他說，比如說有個小孩子，他從沒看過竹蜻蜓，有天他拿到冰棒棍，讓冰棒棍飛上天空，那就是創造力。</p>
      <p><br></p>
      <p>而20年後、40年後的人才需要具備什麼能力，才能為人類發展有所貢獻？鴻海教育基金會董事暨永齡教育基金會執行長劉宥彤說，面臨解構的時代，沒有單一價值觀，而且有各門各派的見解，因為他們對於未來的解讀不同。</p>
      <p><br></p>
      <p>但是「發展人類的天賦」卻是千古不變的核心價值，她強調，有些事情是「人」才能做的事情，而非機器可以取代。在多樣多元的時代中，我們只能努力創造多元的平台，培育出多元的人才。</p>
      <p><br></p>
      <share href="https://udn.com/upf/newmedia/2018_data/newedu/future/index.html"></share>
      <logo use-ubrand="yes" use-vision='no'>
        <div class="logo">
          <a href="http://www.yonglin.org.tw/" target="_blank"><img :src="logo"></a>
        </div>         
      </logo>
      
      <p><br></p>
      <editor>
        <div>製作人、文字：吳思萍</div>
        <div>網頁設計、影音製作：張心慈</div>
        <div>影音、攝影：蘇健忠、王騰毅、劉學聖、張心慈</div>
        <div>網頁製作：胡凈悟</div>
        <div>議題行銷：張乃文、陳欣媛、蔡嘉棋、王敏霏</div>
        <div>監製：林秀姿、董谷音、蔡幸怡、潘如瑩</div>
        <div>2018.12.25</div>
      </editor>
      <p><br></p>
      <relate title="延伸閱讀"
        text1="身處科技時代 如何讓孩子發揮出人的天性？" href1="https://ubrand.udn.com/ubrand/story/11815/3475980" :img1="related.read1"
        text2="唐鳳：別教小孩當工具人 否則容易被AI取代" href2="https://ubrand.udn.com/ubrand/story/11815/3462557" :img2="related.read2"
        text3="新加坡教育制度改革 小一小二率先廢除考試" href3="https://ubrand.udn.com/ubrand/story/11815/3448767" :img3="related.read3"
        text4="讓孩子好好做自己 歐巴桑捍衛性平與兒童人權" href4="https://ubrand.udn.com/ubrand/story/11815/3495990" :img4="related.read4">
      </relate>
      <p><br></p>
      <fb-comment href="https://udn.com/upf/newmedia/2018_data/newedu/future/index.html"></fb-comment>
    </content-container>
    <back-top></back-top>
    <foot></foot>
  </div>
</template>

<script>
import Vue from 'vue'
import srcRWD from '@/mixin/srcRWD.js'
import AnimationCover from '@/components/AnimationCover.vue'
import AnimationImage from '@/components/AnimationImage.vue'
import globalComponents from '@/plugins/baseComponents.js'

Vue.use(globalComponents)

export default {
  name: 'App',
  mixins: [srcRWD],
  data () {
    return {
      logo: 'static/logo.jpg',
      related: {
        read1: 'static/related/read2-1.jpg',
        read2: 'static/related/read2-2.jpg',
        read3: 'static/related/read2-3.jpg',
        read4: 'static/related/read2-4.jpg'
      },
      images: {
        imgWeb0: 'static/pictures/image0.jpg',
        imgMob0: 'static/pictures/image0_m.jpg',
        imgWeb1: 'static/pictures/image1.jpg',
        imgMob1: 'static/pictures/image1_m.jpg',
        imgWeb2: 'static/pictures/image2.jpg',
        imgMob2: 'static/pictures/image2_m.jpg',
        imgWeb3: 'static/pictures/image3.jpg',
        imgMob3: 'static/pictures/image3_m.jpg'
      },
      coverWeb1: {
          renderer: 'svg',
          loop: true,
          autoplay: true,
          path: 'static/animation/cover/web/data.json'
      },
      coverMob1: {
          renderer: 'svg',
          loop: true,
          autoplay: true,
          path: 'static/animation/cover/mob/cover_m_ex.json'
      },
      imgWeb6: {
          renderer: 'svg',
          loop: true,
          autoplay: true,
          path: 'static/animation/image6/web/image6_ex.json'
      },
      imgMob6: {
          renderer: 'svg',
          loop: true,
          autoplay: true,
          path: 'static/animation/image6/mob/image6_m.json'
      }
    }
  },
  components: {
    'animation-cover': AnimationCover,
    'animation-image': AnimationImage
  },
  mounted () {}
}
</script>

<style  lang="scss">
@import './assets/CSS/theme.css';
@import './assets/CSS/UdnFontSize.css';


html, body {
  margin: 0;
  padding: 0;
}
#app {
  .coverTitle1 {
      @media screen and (min-width: 768px) and (max-width: 1023px) {
        margin-top: 25px;
        font-size: 45px;
      }
      @media screen and (min-width: 1024px) {
        margin-top: 25px;
        font-size: 45px;
      }
    }
    .coverTitle2 {
      @media screen and (min-width: 768px) and (max-width: 1023px) {
        margin-top: 0;
        font-size: 30px;
      }
      @media screen and (min-width: 1024px) {
        margin-top: 0;
        font-size: 30px;
      }
      
    }
  .titleNumber {
    display: inline-block;
    width: 40px;
    text-align: center;
    line-height: 40px;
    background-color: #2ca58d;
    border-radius: 50%;
    margin-right: 14px;
    color: #fff;
    @media (min-width: 768px) and (max-width: 1023px) {
        width: 60px;
        line-height: 60px;
    }
    @media screen and (min-width: 1024px) {
        width: 60px;
        line-height: 60px;
    }
  }
  .main-title {
    position: relative;
    padding-bottom: 33px;
    h3 {
      font-weight: 900;
    }
    ul {
      margin: 0;
      padding: 0;
      position: absolute;
      left: 0;
      bottom: 0;
      width: 50%;
      height: 6px;
      display: flex;
      list-style: none;
      .green-line {
        flex: 6;
        background-color: #2ca58d;
      }
      .red-line {
        flex: 1;
        background-color: #f46197;;
      }
      .black-line {
        flex: 2;
        background-color: #384156;
      }
    }
  }
}
</style>
