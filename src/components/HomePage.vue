<template>
  <div class="home-page">
    <div class="head">
	    <div>设置</div>
	    <div>日常</div>
	    <div>图表</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.head {
	position: relative;
	margin: 10px 20px;
	text-align: center;
}
.head>div {
	display: inline-block;
}
.head>div:first-child {
	position: absolute;
	left: 0;
}
.head>div:nth-child(2) {
	border: 1px solid;
}
.head>div:last-child {
	position: absolute;
	right: 0;
}


</style>
