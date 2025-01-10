---
title: 友链
icon: link
sidebar: false
---

<div class="vp-card-container">
  <VPCard
    v-for="i in 12"
    title="Mr.Hope"
    desc="Where there is light, there is hope"
    logo="https://mister-hope.com/logo.svg"
    link="https://mister-hope.com"
    background="rgba(253, 230, 138, 0.15)"
  />
  <VPCard
    title="Mr.Hope"
    desc="Where there is light, there is hope"
    logo="https://mister-hope.com/logo.svg"
    link="https://mister-hope.com"
    background="rgba(253, 230, 138, 0.15)"
  />
  <VPCard
    title="Mr.Hope"
    desc="Where there is light, there is hope"
    logo="https://mister-hope.com/logo.svg"
    link="https://mister-hope.com"
    background="rgba(253, 230, 138, 0.15)"
  />

  <SiteInfo name="Mr.Hope's Blog" url="https://mister-hope.com" preview="https://theme-hope.vuejs.press/assets/image/mrhope.jpg" />


</div>

<VPBanner
  title="Mr.Hope"
  content="Where there is light, there is hope"
  logo="https://mister-hope.com/logo.svg"
  :actions='[
    {
      text: "访问",
      link:"https://mister-hope.com",
    },
    {
      text: "仓库",
      link: "https://github/Mister-Hope/Mister-Hope.github.io",
      type: "default",
    },
  ]'
/>


<SiteInfo
  name="Mr.Hope's Blog"
  desc="Where there is light, there is hope"
  url="https://mister-hope.com"
  logo="https://mister-hope.com/logo.svg"
  repo="https://github.com/Mister-Hope/Mister-Hope.github.io"
  preview="https://theme-hope.vuejs.press/assets/image/mrhope.jpg"
/>