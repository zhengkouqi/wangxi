# CSS

## 卡券

``` javascript
.coupon {
  width: 300px;
  height: 100px;
  line-height: 100px;
  margin: 50px auto;
  text-align: center;
  position: relative;
  background: radial-gradient(circle at right bottom, transparent 10px, #ffffff 0) top right /50% 51px no-repeat,
  radial-gradient(circle at left bottom, transparent 10px, #ffffff 0) top left / 50% 51px no-repeat,
  radial-gradient(circle at right top, transparent 10px, #ffffff 0) bottom right / 50% 51px no-repeat,
  radial-gradient(circle at left top, transparent 10px, #ffffff 0) bottom left / 50% 51px no-repeat;
  filter: drop-shadow(2px 2px 2px rgba(0, 0, 0, .2));
}
.coupon span {
  display: inline-block;
  vertical-align: middle;
  margin-right: 10px;
  color: red;
  font-size: 50px;
  font-weight: 400;
}

<p class="coupon">
    <span>200</span>优惠券
</p>
```
[![20210323092946.jpg](https://i.postimg.cc/yY2PvQkv/20210323092946.jpg)](https://postimg.cc/XpcdvgKC)

## 超过长度显示...
``` javascript
一行文本超过显示...
overflow:hidden;
text-overflow:ellipsis;
write-space:nowrap;
word-break: break-all;

多行文本超过显示...
overflow:hidden;
display:-webkit-box;
-webkit-box-orient:vertical;
-webkit-box-clamp:3;
```