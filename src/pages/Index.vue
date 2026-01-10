<template>
  <Layout class="content-box" :show-logo="false" :show-nav="true">
    <h1>Tẹjúmádé Àfọ̀njá</h1>
    <div class="profile-header">
      <div class="profile-header__img">
          <g-image
          src="~/assets/images/about-img.jpg"
          class="profile-img"
        ></g-image>
        
      </div>
        <div class="profile-header__intro">
         I am a doctoral researcher at CISPA Helmholtz Center (advised by <a href="https://cispa.saarland/group/fritz/" target="_blank">Prof. Mario Fritz</a>).
         My Ph.D research is at the intersection of privacy and machine learning where I focus on 
         developing robust methodologies for the generation and evaluation of private synthetic tabular data, 
         with a specific emphasis on applications within the healthcare domain. My publications are visible on my 
         <a href="https://scholar.google.com/citations?hl=en&user=u6q18aAAAAAJ&view_op=list_works&sortby=pubdate" target="_blank">Google Scholars</a> page.
        </div>
    </div>

    <div class="more-details">
        <div>
          During the summer of 2020, I had the opportunity to intern remotely with
          <a href="https://www.papernot.fr/" target="_blank"
            >Prof. Nicolas Papernot</a
          >
          at the University of Toronto and Vector Institute where I investigated
          the security of speaker classification models, specifically, I worked
          on generative model extraction of speaker classification models.
        </div>

        <div>
          In 2018, I co-founded
          <a href="http://www.aisaturdayslagos.com/" target="_blank">AI Saturdays Lagos</a>, 
          a volunteer-driven artificial intelligence community
          where we offer free classes on Data Science, Machine Learning and Deep
          Learning for about 16 weeks (classes are on Saturdays) through
          structured learning groups. You can find documentation of our cohorts organised on  
          <a href="https://github.com/AISaturdaysLagos/cohort_structure" target="_blank">Github</a>
          to support other communities looking to start similar initiative. From 2018-2019, we completely
          operated as in-person only community where we gathered together at a location in Lagos, Nigeria. 
          However, since the onset of the Covid19 pandemic, we now teach our classes virtually. 
          In the future, we hope to move to a hybrid setup where we blend in-person and online classes.
        </div>

        <div>
        In 2021, we registered a non-profit organisation called <a href="https://tri-ai.org/" target="_blank">TRI AI</a> (Artificial Intelligence Teaching, Research and Innovation for Africa Ltd/GTe)
        to extend our educational initiatives at AI Saturdays Lagos and scale its impact across Africa. 
        </div>

        <div>
          From 2019 till date, I have been a member, volunteer or organiser at <a href="https://deeplearningindaba.com/" target="_blank" >
          Deep Learninig Indaba</a>, an educational charity
          focused on strengthening African AI where I served as one of the General Chairs for Indaba 2025. 

        </div>
        <div>
          From 2019-2021, I co-organised Machine Learning for the Developing World (<a
            href="https://sites.google.com/view/ml4d/home?authuser=0"
            target="_blank"
            >ML4D</a
          >) NeurIPS workshop where I served as the lead organiser in 2020, as well as the
          chair of the steering committee in 2021.
          I have also
          co-organised other initiatives like Mechanism Design for Social Good development working group(<a
            href="https://bridges.eaamo.org/previous_wgs/development/"
            target="_blank"
            >MD4SG-Dev</a
          >), now known as EEAMO Bridges.
        </div>

        <div>
          You can stay in touch with me via
          <a href="https://linkedin.com/in/tejumadeafonja">LinkedIn</a> or 
          <a href="https://twitter.com/tejuafonja">Twitter</a>. 
          You can also contact me via <a mail-to="tejumade@tri-ai.org" target="_blank">email</a>.
        </div>
      
        <div>
          I write on <g-link to="/xhirot">Xhirot</g-link>, 
          <a href="https://medium.com/@tejuafonja" target="_blank">my Medium page</a>, and
          <a href="https://medium.com/ai-saturdays-lagos-articles" target="_blank">AISaturdaysLagos Medium page</a>
        </div>

      </div>
  </Layout>
</template>

export default {
  metaInfo: {
    title: 'Home'
  }
}


<style lang="scss">
a {
  color: #fdb310 !important;
}

.content-box h1 {
  margin-top: 1rem;
  margin-bottom: 2rem;
  text-align: center;
}
.more-details {
  display: flex;
  flex-wrap: wrap;
  margin-top: 1.5rem;
  & div {
    margin-bottom: 1.5rem;
    text-align: justify;
  }
}
.profile-header {
  display: flex;
  width: 100%;

&__img {
  display: block;
  width: 60%;
  margin-right: 1rem;
  }

&__intro{
  width: 100%;
  text-align: justify;
  }
}

.profile-img {
  width: 12em;
  height: 12em;
}
@media screen and (max-width: 650px) {
  .profile-header {
  display: flex;
  flex-direction: column;
  }

  .profile-header {

  &__img {
  width: 100%;
  text-align: center;

  }

  &__intro {
    margin-top: 1.5rem;
    }
  
  }

}

</style>



