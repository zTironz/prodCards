<template>
  <div class="main">
    <div class="main__fist-column">
      <h3 class="main__fist-column-heading">Добавление товара</h3>
      <div class="main__fist-column-item">
        <h6 class="main__fist-column-title">Наименование товара</h6>
        <input type="text" placeholder="Введите наименование товара">
        <h6 class="main__fist-column-description">Описание товара</h6>
        <input type="text" placeholder="Введите описание товара">
        <h6 class="main__fist-column-img">Ссылка на изображение товара</h6>
        <input type="text" placeholder="Введите ссылку">
        <h6 class="main__fist-column-price">Цена товара</h6>
        <input type="text" placeholder="Введите цену">
        <button class="button" @click="say('hi')">Добавить товар</button>
      </div>
    </div>
    <div class="main__second-column">

    </div>
  </div>
</template>

<style>

.main {
  display: flex;
  height: 100vh;
  border: 1px solid red;
  padding: 32px;
  margin: 0;
  box-sizing: border-box;
}

.main__fist-column {
  display: flex;
  flex-direction: column;
  height: 100%;
  width: 332px;
  border: 1px solid red;
}

.main__second-column {
  display: flex;
  flex-direction: column;
  height: 100%;
  width: 100%;
  border: 1px solid red;
}

.main__fist-column-heading {
  margin: 0;
  padding: 0;
  font-family: Source Sans Pro;
font-style: normal;
font-weight: 600;
font-size: 28px;
line-height: 35px;

color: #3F3F3F;
}

.main__fist-column-item {
  display: flex;
  flex-direction: column;
  margin-top: 16px;
  padding: 24px;
  width: 332px;
  height: 440px;
  border: 1px solid red;
  box-sizing: border-box;

background: #FFFEFB;
box-shadow: 0px 20px 30px rgba(0, 0, 0, 0.04), 0px 6px 10px rgba(0, 0, 0, 0.02);
border-radius: 4px;
}

.main__fist-column-title {

font-family: Source Sans Pro;
font-style: normal;
font-weight: normal;
font-size: 10px;
line-height: 13px;
/* identical to box height */
letter-spacing: -0.02em;

/* Temp / Darks / Lesser */
color: #49485E;
}
.main__fist-column-description {

font-family: Source Sans Pro;
font-style: normal;
font-weight: normal;
font-size: 10px;
line-height: 13px;
/* identical to box height */
letter-spacing: -0.02em;

/* Temp / Darks / Lesser */
color: #49485E;
}

.main__fist-column-img {

font-family: Source Sans Pro;
font-style: normal;
font-weight: normal;
font-size: 10px;
line-height: 13px;
/* identical to box height */
letter-spacing: -0.02em;

/* Temp / Darks / Lesser */
color: #49485E;
}

.main__fist-column-price {

font-family: Source Sans Pro;
font-style: normal;
font-weight: normal;
font-size: 10px;
line-height: 13px;
/* identical to box height */
letter-spacing: -0.02em;

/* Temp / Darks / Lesser */
color: #49485E;
}


</style>



<script>
export default {
  methods: {
    say: function (message) {
      alert(message)
    }
  }
}
</script>
