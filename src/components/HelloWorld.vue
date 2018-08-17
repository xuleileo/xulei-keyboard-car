<template>
  <div class="keyboard">
    <div class="row">
      <button >京</button>
      <button >沪</button>
      <button >鄂</button>
      <button >湘</button>
      <button >川</button>
      <button >渝</button>
      <button >粤</button>
      <button >闽</button>
      <button >晋</button>
      <button >黑</button>
    </div>
    <div class="row">
      <button >津</button>
      <button >浙</button>
      <button >豫</button>
      <button >赣</button>
      <button >贵</button>
      <button >青</button>
      <button >琼</button>
      <button >宁</button>
      <button >吉</button>
      <button >蒙</button>
    </div>
    <div class="row">
      <button >冀</button>
      <button >苏</button>
      <button >皖</button>
      <button >桂</button>
      <button >云</button>
      <button >陕</button>
      <button >甘</button>
      <button >藏</button>
      <button >新</button>
      <button >辽</button>
    </div>
    <div class="row">
      <button >鲁</button>
      <button class="blank"> </button>
      <button class="del">删除</button>
      <button class="ok">完成</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .keyboard{
    position: fixed;
    padding-top: 2vw;
    bottom: 0px;
    width: 100vw;
    height: 53vw;
    background: #e3e3e3;
  }
  .row{
    width: 96vw;
    height: 13vw;
    display: flex;
    align-items: center;
    justify-content:space-between;
    margin-left: 2vw;
    margin-right: 2vw;
  }
  .row button{
    height: 10vw;
    width:8vw;
    border-radius: 5px; 
    background: #fff;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .row .blank{
    width: 46vw;
  }
  .row .del{
    width: 18vw;
  }
  .row .ok{
    width: 18vw;
  }

</style>
