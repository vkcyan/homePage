<template>
  <div id="app">
    <mainpage></mainpage>
  </div>
</template>

<script>
import mainpage from "./components/main"
export default {
  components: {
    mainpage
  }
}
</script>

<style lang="less">
#app {
  body,
  ol,
  ul,
  h1,
  h2,
  h3,
  h4,
  h5,
  h6,
  p,
  th,
  td,
  dl,
  dd,
  form,
  fieldset,
  legend,
  input,
  textarea,
  select {
    margin: 0;
    padding: 0;
  }
  body {
    font: 12px "黑体", "Arial Narrow", HELVETICA;
    background: #fff;
    -webkit-text-size-adjust: 100%;
  }
  a {
    color: #2d374b;
    text-decoration: none;
  }
  a:hover {
    color: #cd0200;
    text-decoration: underline;
  }
  em {
    font-style: normal;
  }
  li {
    list-style: none;
  }
  img {
    border: 0;
    vertical-align: middle;
  }
  table {
    border-collapse: collapse;
    border-spacing: 0;
  }
  p {
    word-wrap: break-word;
  }
}
</style>