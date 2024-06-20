<template>
  <div class="w-full h-9 bg-purple-300">
    <span class="text-2xl font-thin px-5 float-left text-white">
      深圳出行计划
    </span>
    <span class="text-2xl font-thin px-5 float-right text-white">
      By AcboxLiu
    </span>
  </div>
  <div class="text-[15px] flex flex-col px-3">
    <h1 class="text-2xl text-center py-3">日程表</h1>
    <div>
      <table class="border border-gray-300 w-full">
        <tr class="border">
          <td class="border">运动</td>
          <td class="border">路径</td>
          <td class="border">时间</td>
        </tr>
        <tr class="border">
          <td class="border">去</td>
          <td class="border">金寨 => 武汉 => 深圳北</td>
          <td class="border">2024-07-04</td>
        </tr>
        <tr class="border">
          <td class="border">返</td>
          <td class="border">深圳北 => 汉口 => 金寨</td>
          <td class="border">2024-07-07</td>
        </tr>
      </table>
    </div>
    <hr />
    <div>
      <h1 class="text-2xl text-center py-3">列车安排</h1>
      <div class="border">
        <img class="p-1" src="./assets/1.png" />
      </div>
      <div class="border">
        <img class="p-1" src="./assets/2.png" />
      </div>
    </div>
    <div>
      <h1 class="text-2xl text-center py-3">大会地址</h1>
      <span class="text-center">Tips：用手拖动地图查看周边</span>
      <div class="border">
        <iframe class="w-full h-[500px]"
          src="https://m.amap.com/navi/?dest=114.060273,22.569759&destName=广东省深圳市福田区中康路126号卓悦汇购物中心&hideRouteIcon=1&key=584d85ce77e3a854180cd921c9a41977"></iframe>
      </div>
    </div>
    <div>
      <h1 class="text-2xl text-center py-3">酒店</h1>
      <h2 class="text-center">待选地址</h2>
      <ul>
        <li class="py-10">
          深圳理想之家公寓
          <img src="./assets/3.jpg">
          <iframe class="w-full h-[300px]"
            src="https://m.amap.com/navi/?dest=114.061391,22.570113&hideRouteIcon=1&key=584d85ce77e3a854180cd921c9a41977"></iframe>
          <span>距离商场145米，可步行</span>
        </li>
        <li class="py-10">
          维也纳酒店
          <img src="./assets/4.jpg"/>
          <iframe class="w-full h-[300px]"
            src="https://m.amap.com/navi/?dest=114.058803,22.567878&hideRouteIcon=1&key=584d85ce77e3a854180cd921c9a41977"></iframe>
          <span>距离商场417米，可步行</span>
        </li>
        <li class="py-10">
          梵西服务公寓
          <img src="./assets/5.jpg"/>
          <iframe class="w-full h-[300px]"
            src="https://m.amap.com/navi/?dest=114.057918,22.571066&hideRouteIcon=1&key=584d85ce77e3a854180cd921c9a41977"></iframe>
          <span>距离商场434米，可步行</span>
        </li>
      </ul>
    </div>
    <div>
      <h1 class="text-2xl text-center py-3">日程安排</h1>
      <h2>7月4日</h2>

      打车到酒店，休整

      <h2>7月5日</h2>

      爷爷奶奶：深圳1日游

      我：玩

      <h2>7月6日</h2>

      爷爷奶奶：香港1日游

      我：开会

      <h2>7月7日</h2>

      回家

    </div>
  </div>
</template>