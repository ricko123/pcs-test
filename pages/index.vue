<template>
  <section>
    <div class="header-home">
      <b-container>
        <b-row class="d-flex justify-content-between align-items-center">
          <b-col cols="3">
            <h1>KerjaYuk!</h1>
          </b-col>
          <b-col cols="2">
            <nuxt-link to="/notification">
              <img src="@/assets/img/notif.svg" alt="">
            </nuxt-link>
          </b-col>
        </b-row>
      </b-container>
    </div>
    <b-container>
      <b-row>
        <b-col cols="12">
          <div class="greetings">
            Hi, Good Morning!
          </div>
          <CardMember />
        </b-col>
      </b-row>
      <b-row class="mb-3">
        <b-col cols="12">
          <div class="title-content">
            <h3>Today's activity</h3>
          </div>
        </b-col>
      </b-row>
      <b-row class="mb-4">
        <b-col cols="4" class="time-activity">
          <img src="@/assets/img/clock.png" alt="">
          <h4>08:30</h4>
          <p>Check In</p>
        </b-col>
        <b-col cols="4" class="time-activity">
          <img src="@/assets/img/work-schedule.png" alt="">
          <h4 class="working-hours">
            03:00:00
          </h4>
          <p>Working Hours</p>
        </b-col>
        <b-col cols="4" class="time-activity">
          <img src="@/assets/img/three-o-clock-clock.png" alt="">
          <h4>--:--</h4>
          <p>Check Out</p>
        </b-col>
      </b-row>
    </b-container>
    <b-container>
      <b-row class="mb-3">
        <b-col cols="12">
          <div class="title-content">
            <h3>PCS News</h3>
          </div>
        </b-col>
      </b-row>
    </b-container>
    <carousel
      :stage-padding="50"
      :items="1"
      :nav="false"
      :margin="30"
      :loop="true"
      :autoplay="true"
    >
      <div class="item">
        <b-row class="mb-2">
          <b-col cols="6" class="d-flex align-items-center">
            <img src="@/assets/img/user.png" class="img-user-slide" alt="">
            <span> Ana Riswati</span>
          </b-col>
          <b-col cols="6" class="text-right">
            <p>Senin</p>
            <p>30 Mei 2022</p>
          </b-col>
        </b-row>
        <b-row>
          <b-col cols="12">
            <div class="desc px-3">
              Kalimat 1 ...Lorem ipsum sit dolor amet<br>
              Kalimat 2 ...Lorem ipsum sit dolor amet<br>
              Kalimat 3 ...Lorem ipsum sit dolor amet<br>
              Kalimat 4 ...Lorem ipsum sit dolor amet
            </div>
          </b-col>
        </b-row>
      </div>
      <div class="item">
        <b-row class="mb-2">
          <b-col cols="6" class="d-flex align-items-center">
            <img src="@/assets/img/user.png" class="img-user-slide" alt="">
            <span> Ana Riswati</span>
          </b-col>
          <b-col cols="6" class="text-right">
            <p>Senin</p>
            <p>30 Mei 2022</p>
          </b-col>
        </b-row>
        <b-row>
          <b-col cols="12">
            <div class="desc px-3">
              Kalimat 1 ...Lorem ipsum sit dolor amet<br>
              Kalimat 2 ...Lorem ipsum sit dolor amet<br>
              Kalimat 3 ...Lorem ipsum sit dolor amet<br>
              Kalimat 4 ...Lorem ipsum sit dolor amet
            </div>
          </b-col>
        </b-row>
      </div>
      <div class="item">
        <b-row class="mb-2">
          <b-col cols="6" class="d-flex align-items-center">
            <img src="@/assets/img/user.png" class="img-user-slide" alt="">
            <span> Ana Riswati</span>
          </b-col>
          <b-col cols="6" class="text-right">
            <p>Senin</p>
            <p>30 Mei 2022</p>
          </b-col>
        </b-row>
        <b-row>
          <b-col cols="12">
            <div class="desc px-3">
              Kalimat 1 ...Lorem ipsum sit dolor amet<br>
              Kalimat 2 ...Lorem ipsum sit dolor amet<br>
              Kalimat 3 ...Lorem ipsum sit dolor amet<br>
              Kalimat 4 ...Lorem ipsum sit dolor amet
            </div>
          </b-col>
        </b-row>
      </div>
    </carousel>
    <b-container>
      <b-row>
        <b-col cols="12">
          <div class="title-content">
            <h3>Online</h3>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </section>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
