<template id="MainHome">
    <el-container>
      <el-header id="MainHome_header">
        <div>EVPN 批量割接工具</div>
      </el-header>
      <el-main id="MainHome_main">
        <el-container id="MainHome_left" >
          <div>
            <ul>
              <li> 专线1 </li>
              <li> 专线2 </li>
              <li> 专线3  </li>
              <li> 专线4  </li>
              <li> 专线5  </li>
            </ul>
          </div>
        </el-container>

        <el-container id="MainHome_center">
          <div>成员属性1</div>
        </el-container>

        <el-container id="MainHome_right" >
          <div>成员属性2</div>
        </el-container>
      </el-main>

    </el-container>
</template>

<script>

</script>

<style>
  #MainHome_main{

  }
  #MainHome_right {
    background-color: rgba(16, 67, 105, 0.836);
    color: #333;
    text-align: center;
    margin-top: 0px;
    float: right;
    margin-right: 0px;
    height: 650px;
    width: 35%;
  }

  #MainHome_center {
    background-color: rgba(192, 162, 182, 0.836);
    float: left;
    margin-left: auto;
    margin-right: auto;
    height: 650px;
    width: 35%;
  }

  #MainHome_left {
    background-color: rgba(105, 16, 75, 0.836);
    float: left;
    margin-left: auto;
    margin-right: auto;
    height: 650px;
    width: 20%
  }

  #MainHome_header {
    background-color: rgb(27, 118, 230);
    color: #333;
    text-align: center;
    height: 150px;
    line-height: 60px;
    margin-left: 80px;
    margin-right: 80px;

  }

</style>
