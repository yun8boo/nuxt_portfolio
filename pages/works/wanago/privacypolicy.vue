<template>
  <section class="container">
    <div>
      <img
        class="icon"
        src="~/assets/icon_m.png" 
        alt="wanago">
      <h2 class="wanago-title">Wanago</h2>
      <h2 class="wanago-title">プライバシーポリシー</h2>
    </div>
    <div class="privacy-policy-wrapper">
      <p>本アプリケーション端末の位置情報（GPS、ネットワークを利用した位置情報）を取得します。</p>
      <p>利用目的：位置情報を利用した飲食店情報の提供</p>
      <p>お問い合わせはwanago.info@gmail.comまでお願いいたします。</p>
    </div>
  </section>
</template>

<style>
.container {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.wanago-title {
  font-size: 32px;
}

.icon {
  width: 100px;
}

.privacy-policy-wrapper {
  margin-top: 20px;
}
</style>
