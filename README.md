# vue-flipcard

Vue flip card component

## demo
[https://edwardorz.github.io/vue-flipcard/](https://edwardorz.github.io/vue-flipcard/)

## Install | 安装
```bash
yarn add vue-flipcard
```
or
```bash
npm i vue-flipcard
```

## Usage | 用法
```javascript
import VueFlipcard from 'vue-flipcard'

Vue.component('vue-flipcard', VueFlipcard)
```

```html
<vue-flipcard
  :width="300"
  :height="240"
  direction="vertical"
  @flip="onFlip"
>
</vue-flipcard>
```

## Props | 属性

| 参数/prop | 描述/desc | 数据类型/type | 是否必填/required | 默认值/default |
| :-- | :-- | :------ | :----- | :---- |
| witdh | 宽度 | number | No | 300 |
| height | 高度 | number | No | 300 |
| direction | 方向 | string | No | horizontal |
| disable | 是否禁用 | boolean | No | false |

## Events | 事件

| 名称/name | 描述/desc |
| :-- | :-- |
| flip | 翻转时触发/emit on flipping |

## Methods | 方法

| 名称/name | 用法/usage |
| :-- | :-- |
| flip | this.$refs.flipcard.flip() |

## License

[MIT](http://opensource.org/licenses/MIT)


