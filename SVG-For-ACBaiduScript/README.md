本文件夹是为`AC-baidu`脚本修改的自定义图标库

[ViolentMonkey（暴力猴）扩展官网](https://violentmonkey.github.io/)  |  [暴力猴扩展 MS Edge 扩展商店](https://microsoftedge.microsoft.com/addons/detail/eeagobfjdenkkddmbclomhiblgggliao)  |  [AC-Baidu脚本地址](https://greasyfork.org/zh-TW/scripts/14178-ac-baidu-%E9%87%8D%E5%AE%9A%E5%90%91%E4%BC%98%E5%8C%96%E7%99%BE%E5%BA%A6%E6%90%9C%E7%8B%97%E8%B0%B7%E6%AD%8C%E5%BF%85%E5%BA%94%E6%90%9C%E7%B4%A2-favicon-%E5%8F%8C%E5%88%97)

扩展替代品：`Greasemonkey`、`Tampermonkey`

需在脚本设置的自定义样式里添加如下：

```css
/**计数器的颜色样式*/
div .AC-CounterT{
  background: #4285f4;
  font-size: 12px !important;
}

/**自动翻页箭头样式*/
.ac_sp_top {
    background-image: url('https://raw.githubusercontent.com/northword/img-bad/main/SVG-For-ACBaiduScript/Icon-goTop.svg')!important;
}
.ac_sp_pre_gray {
    background-image: url('https://raw.githubusercontent.com/northword/img-bad/main/SVG-For-ACBaiduScript/Icon-pre.svg')!important;
}
.ac_sp_next_gray {
    background-image: url('https://raw.githubusercontent.com/northword/img-bad/main/SVG-For-ACBaiduScript/Icon-next.svg')!important;
}
.ac_sp_bottom {
    background-image: url('https://raw.githubusercontent.com/northword/img-bad/main/SVG-For-ACBaiduScript/Icon-goBottom.svg')!important;
}
```


默认Fav图标：
```
https://raw.githubusercontent.com/northword/img-bad/main/SVG-For-ACBaiduScript/Icon-website-fav.svg
```


2020.11.10

Northword

