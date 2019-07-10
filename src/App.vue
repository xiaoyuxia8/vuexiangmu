<template>
  <div class="contant">
    123
    <mt-header fixed title="黑马程序员·Vue项目"></mt-header>

    <!-- 底部 Tabbar 区域 -->
    <!-- <nav data-v-7ba5bd90 class="mui-bar mui-bar-tab">
      <a data-v-7ba5bd90 href="#/home" class="mui-tab-item-llb router-link-exact-active mui-active">
        <span data-v-7ba5bd90 class="mui-icon mui-icon-home"></span>
        <span data-v-7ba5bd90 class="mui-tab-label">首页</span>
      </a>
      <a data-v-7ba5bd90 href="#/member" class="mui-tab-item-llb">
        <span data-v-7ba5bd90 class="mui-icon mui-icon-contact"></span>
        <span data-v-7ba5bd90 class="mui-tab-label">会员</span>
      </a>
      <a data-v-7ba5bd90 href="#/shopcar" class="mui-tab-item-llb">
        <span data-v-7ba5bd90 class="mui-icon mui-icon-extra mui-icon-extra-cart">
          <span data-v-7ba5bd90 id="badge" class="mui-badge">0</span>
        </span>
        <span data-v-7ba5bd90 class="mui-tab-label">购物车</span>
      </a>
      <a data-v-7ba5bd90 href="#/search" class="mui-tab-item-llb">
        <span data-v-7ba5bd90 class="mui-icon mui-icon-search"></span>
        <span data-v-7ba5bd90 class="mui-tab-label">搜索</span>
      </a>
    </nav> -->
    <nav class="mui-bar mui-bar-tab">
			<a class="mui-tab-item mui-active" href="#tabbar">
				<span class="mui-icon mui-icon-home"></span>
				<span class="mui-tab-label">首页</span>
			</a>
      <a class="mui-tab-item" href="#tabbar-with-contact">
				<span class="mui-icon mui-icon-contact"></span>
				<span class="mui-tab-label">会员</span>
			</a>
			<a class="mui-tab-item" href="#tabbar-with-chat">
				<span class="mui-icon mui-icon-extra mui-icon-extra-cart"><span class="mui-badge">0</span></span>
				<span class="mui-tab-label">购物车</span>
			</a>
			
			<a class="mui-tab-item" href="#tabbar-with-map">
				<span class="mui-icon mui-icon-search"></span>
				<span class="mui-tab-label">搜索</span>
			</a>
		</nav>
  </div>
</template>

<script>
export default {};
</script>


<style lang="scss" scoped>
body {
  background-color: pink;
  .contant {
    padding-top: 40px;
    padding-top: 40px;
    padding-bottom: 50px;
    overflow-x: hidden;
  }
}
</style>
