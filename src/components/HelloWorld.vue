<template>
  <b-container fluid v-if="!isMobile()">
    <b-row align-content="center">
      <b-col>
        <h1 style="font-size: 17vw">Hey Baby!!!</h1>
      </b-col>
    </b-row>
    <b-row align-content="center">
      <b-col>
        <b-row>
          <b-col>
            <b-img :src="require('../assets/g3_1.jpg')" fluid-grow alt="g3_1" />
          </b-col>
          <b-col>
            <b-img :src="require('../assets/g3_2.jpg')" fluid alt="g3_2" />
          </b-col>
          <b-col>
            <b-img :src="require('../assets/g3_3.jpg')" fluid alt="g3_3" />
          </b-col>
        </b-row>
      </b-col>
    </b-row>
    <b-row align-v="center">
      <b-col>
        <h1 style="font-size: 12vw">
          Happy 24
          <sup>th</sup> Birthday!!
        </h1>
      </b-col>
      <b-col>
        <h1 style="font-size: 12vw">
          &#128151; &#128151; &#128151; &#128151; &#128151; &#128151; &#128151;
          &#128151; &#128151;
        </h1>
      </b-col>
    </b-row>
    <b-row align-v="center">
      <b-col>
        <h1 style="margin: 4%">
          I'm so so so bummed that I am not around for your birthday. Really
          wanted to spend the day with you and bring you out and give you
          surprises but it's okay, just another 1 months~ish left before I come
          back to you! &#128537; Then we can hang out again FINALLY hahaha. Ok
          its not like an amazing birthday card or anything but I hope you like
          it. Of course I'll be bringing you stuff from Canada before I come
          back. You see la never give me enough photos then I got nothing much
          to put here, but of course I added some unglams for good measure
          &#129322;
        </h1>
      </b-col>
    </b-row>
    <b-row align-v="center">
      <b-col>
        <b-row>
          <b-col>
            <h1 style="margin: 4%">Like this...</h1>
          </b-col>
        </b-row>
        <b-row>
          <b-col>
            <b-img
              :src="require('../assets/g3_4.jpg')"
              v-bind:width="this.width"
              rounded
              center
              fluid
              alt="g3_4"
            />
          </b-col>
        </b-row>
        <b-row>
          <b-col>
            <h1 style="margin: 4%">And this...</h1>
          </b-col>
        </b-row>
        <b-row>
          <b-col>
            <b-img :src="require('../assets/g3_5.jpg')" rounded center fluid alt="g3_5" />
          </b-col>
        </b-row>
        <b-row>
          <b-col>
            <h1 style="margin: 4%">And also this &#128518;...</h1>
          </b-col>
        </b-row>
        <b-row>
          <b-col>
            <b-img :src="require('../assets/g3_6.jpg')" rounded center fluid alt="g3_6" />
          </b-col>
        </b-row>
      </b-col>
    </b-row>
    <b-row align-v="center">
      <b-col>
        <h1 style="margin: 4%">Hehehe okok don't angry &#128536;</h1>
      </b-col>
    </b-row>
    <b-row align-v="center">
      <b-col>
        <h1 style="margin: 4%">
          Thank you for being there for me and being so understanding these last
          few months in Canada. I know its not easy especially since we barely
          get to talk because of the time difference and everything but I'm
          really glad that we're hanging in there. Theres been so many nights
          where i wanted to just be lying next to you again and so many times
          I'm just sad that I don't get to see you. But I'm finally waaayyy
          closer to coming back home again.
        </h1>
        <h1>
          Can you believe it's been like 6 months since we met? Haha and I have
          stupidly been away longer than with you since we met &#128514;. But
          its okay, after this I'm not going anywhere and you're pretty much
          stuck with me HAHA. If there is anything I have been doing wrong or
          can do better please tell me okay? But you've been really amazing and
          I really enjoy the time I get to spend with you &#128522;
        </h1>
        <h1 style="margin: 4%">
          I would have probably called you
          already but if I haven't then I'll definitely be calling you in abit
          hehe. Have fuuunnnn todayyyyy! Also please take more photos with me if not every
          year you going to get unglams only HAHA &#128538; &#128538; &#128538;
          Wanted to make this way nicer but didn't have enough time but its okay
          next year you'll get physical cards since I'll be around hahaha.
        </h1>
        <h1 style="margin: 4%">Love you, see you soon &#128150;</h1>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
    smallTextStyle: String
  },
  methods: {
    isMobile: function() {
      var check = false;
      (function(a) {
        if (
          /(android|bb\d+|meego).+mobile|avantgo|bada\/|blackberry|blazer|compal|elaine|fennec|hiptop|iemobile|ip(hone|od)|iris|kindle|lge |maemo|midp|mmp|mobile.+firefox|netfront|opera m(ob|in)i|palm( os)?|phone|p(ixi|re)\/|plucker|pocket|psp|series(4|6)0|symbian|treo|up\.(browser|link)|vodafone|wap|windows ce|xda|xiino/i.test(
            a
          ) ||
          /1207|6310|6590|3gso|4thp|50[1-6]i|770s|802s|a wa|abac|ac(er|oo|s)|ai(ko|rn)|al(av|ca|co)|amoi|an(ex|ny|yw)|aptu|ar(ch|go)|as(te|us)|attw|au(di|m|r |s )|avan|be(ck|ll|nq)|bi(lb|rd)|bl(ac|az)|br(e|v)w|bumb|bw(n|u)|c55\/|capi|ccwa|cdm|cell|chtm|cldc|cmd|co(mp|nd)|craw|da(it|ll|ng)|dbte|dcs|devi|dica|dmob|do(c|p)o|ds(12|d)|el(49|ai)|em(l2|ul)|er(ic|k0)|esl8|ez([4-7]0|os|wa|ze)|fetc|fly(|_)|g1 u|g560|gene|gf5|gmo|go(\.w|od)|gr(ad|un)|haie|hcit|hd(m|p|t)|hei|hi(pt|ta)|hp( i|ip)|hsc|ht(c(| |_|a|g|p|s|t)|tp)|hu(aw|tc)|i(20|go|ma)|i230|iac( ||\/)|ibro|idea|ig01|ikom|im1k|inno|ipaq|iris|ja(t|v)a|jbro|jemu|jigs|kddi|keji|kgt( |\/)|klon|kpt |kwc|kyo(c|k)|le(no|xi)|lg( g|\/(k|l|u)|50|54|[a-w])|libw|lynx|m1w|m3ga|m50\/|ma(te|ui|xo)|mc(01|21|ca)|mcr|me(rc|ri)|mi(o8|oa|ts)|mmef|mo(01|02|bi|de|do|t(| |o|v)|zz)|mt(50|p1|v )|mwbp|mywa|n10[0-2]|n20[2-3]|n30(0|2)|n50(0|2|5)|n7(0(0|1)|10)|ne((c|m)|on|tf|wf|wg|wt)|nok(6|i)|nzph|o2im|op(ti|wv)|oran|owg1|p800|pan(a|d|t)|pdxg|pg(13|([1-8]|c))|phil|pire|pl(ay|uc)|pn2|po(ck|rt|se)|prox|psio|ptg|qaa|qc(07|12|21|32|60|[2-7]|i)|qtek|r380|r600|raks|rim9|ro(ve|zo)|s55\/|sa(ge|ma|mm|ms|ny|va)|sc(01|h|oo|p)|sdk\/|se(c(|0|1)|47|mc|nd|ri)|sgh|shar|sie(|m)|sk0|sl(45|id)|sm(al|ar|b3|it|t5)|so(ft|ny)|sp(01|h|v|v )|sy(01|mb)|t2(18|50)|t6(00|10|18)|ta(gt|lk)|tcl|tdg|tel(i|m)|tim|tmo|to(pl|sh)|ts(70|m|m3|m5)|tx9|up(\.b|g1|si)|utst|v400|v750|veri|vi(rg|te)|vk(40|5[0-3]|v)|vm40|voda|vulc|vx(52|53|60|61|70|80|81|83|85|98)|w3c(| )|webc|whit|wi(g |nc|nw)|wmlb|wonu|x700|yas|your|zeto|zte/i.test(
            a.substr(0, 4)
          )
        )
          check = true;
      })(navigator.userAgent || navigator.vendor || window.opera);
      if (check) {
        alert(
          "Use your laptop / some computer to see this website. Didn't have time to make it look nice in a phone too :( OR you can also enable the \"Desktop Site\" in your phone browser, but it'll still look nicer on a computer screen though."
        );
      }
      return check;
    }
  }
};
</script>
