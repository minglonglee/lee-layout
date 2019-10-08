
# 语法说明


### 关于单位
以纯数字结尾的，默认单位是px，例：5表示5px；以p结尾的，是百分数单位，例：10p表示10%；数字前有“-”表示负数单位，例-5表示-5px，-10p表示-10%。

## 一、布局

### 浮动、清浮动 fl、fr、clear

fl、fr分别代表左、右浮动，css语法 { float: left }、{ float: right }

clear 为清浮动，用于浮动元素的父元素清除浮动影响(高度丢失)

### 圆角 border-radius
br全称为border-radius，后面的数字代表px值，例：br5 表示 border-radius: 5px

### 字号 font-size
#####f代表font-size，后面数字代表px值，例：f12 表示 font-size: 12px
##### f取值范围 (12 - 60)，+1递增(12 - 60)

### 宽度、最小宽度、最大宽度 width、min-width、max-width
##### w为width的缩写，例：w100 表示 width: 100px，w50p 表示 width: 50%
##### min-w是min-width的缩写，例：min-w100 表示 min-width: 100px，min-w50p 表示 min-width: 50%
##### max-w是max-width的缩写，例：max-w100 表示 max-width: 100px，max-w50p 表示 max-width: 50%
##### w取值范围 (0 - 1200)，+1 递增(0 - 60)，+2 递增(62 - 120)，+10 递增(130-600)，+20 递增(620 - 1200)

### 高度、最小高度、最大高度 height、min-height、max-height
##### h为height的缩写，例：h100 表示 height: 100px，h50p 表示 height: 50%
##### h取值范围 (0 - 1200)，+1 递增(0 - 50)，+2 递增(52 - 100)，+10 递增(100-600)

##### min-h是min-height的缩写，例：min-h100 表示 min-height: 100px，min-h50p 表示 min-height: 50%
##### max-h是max-height的缩写，例：max-h100 表示 max-height: 100px，max-h50p 表示 max-height: 50%

### 行高 line-height
##### lh为line-height的缩写，例：lh30 表示 line-height: 30px
##### lh取值范围 (18 - 120)，+2 递增(18 - 120)

### 外边距 margin-top、margin-bottom、margin-left、margin-right
##### mg-t、mg-b、mg-l、mg-r 分别表示 margin-top、margin-bottom、margin-left、margin-right，例：mg-t10 表示 margin-top: 10px；组合用法 mg-tb10、mg-lr10 分别表示 { margin-top: 10px; margin-bottom: 10px; }、{ margin-left: 10px; margin-right: 10px; }

### 内边距 padding-top、padding-bottom、padding-left、padding-right
##### pd-t、pd-b、pd-l、pd-r 分别表示 padding-top、padding-bottom、padding-left、padding-right，例：pd-t10 表示 padding-top: 10px；组合用法 pd-tb10、pd-lr10 分别表示 { padding-top: 10px; padding-bottom: 10px; }、{ padding-left: 10px; padding-right: 10px; }

### 定位 position
#### 4种类型 static、relative、absolute、fixed
##### pos-static 表示 position: static
##### pos-relative 表示 position: relative
##### pos-abs 表示 position: absolute
##### pos-fix 表示 position: fixed

#### 位置控制 top、bottom、left、right
##### t、b、l、r 分别表示 top、bottom、left、right
##### 例：t10 表示 top: 10px，r20 表示 right: 20px，l50p 表示 left: 50%，t-20 表示 top: -20px，l-10p 表示 left: -10%
##### t、b取值范围(0 - 300)，+1 递增(1 - 50)，+2 递增(52 - 100)，+10 递增 (110 - 300)
##### l、r取值范围(0 - 600)，+1 递增(1 - 50)，+2 递增(52 - 100)，+10 递增 (110 - 600)

#### 层级控制 z-index
##### z 表示 z-index
##### z-10 表示 z-index: 10
##### z取值范围(0 - 10000) +1递增(1～10)，+10 递增(10 - 100)，+100递增 100-1000，+1000 递增 1000-10000
##### 注：层级单位为纯数字，并且为正整数
