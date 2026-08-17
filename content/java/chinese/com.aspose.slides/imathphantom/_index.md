---
title: IMathPhantom
second_title: Aspose.Slides 的 Java API 参考
description: 表示一个幻影数学对象 ltmphantgt，影响其子元素的布局，但不一定显示它。
type: docs
url: /zh/com.aspose.slides/imathphantom/
---
**所有实现的接口：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

表示一个幻影数学对象 (<m:phant>)，它会影响其子元素的布局，但不一定显示出来。幻影可以隐藏其基表达式，同时保留其宽度、高度或深度，以对齐公式或保留空间。可见性和几何行为由诸如 Show、ZeroWid、ZeroAsc、ZeroDesc 和 Transp 等属性控制。

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // 隐藏内容
>  phantom.setZeroWidth(false);     // 保持宽度
>  ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 基参数 |
| [getShow()](#getShow--) | 获取或设置一个值，以指示是否显示基元素。 |
| [setShow(boolean value)](#setShow-boolean-) | 获取或设置一个值，以指示是否显示基元素。 |
| [getZeroWidth()](#getZeroWidth--) | 获取或设置一个值，以指示基元素的宽度是否应视为零。 |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | 获取或设置一个值，以指示基元素的宽度是否应视为零。 |
| [getZeroAsc()](#getZeroAsc--) | 获取或设置一个值，以指示基元素的上升（基线以上的高度）是否应视为零。 |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | 获取或设置一个值，以指示基元素的上升（基线以上的高度）是否应视为零。 |
| [getZeroDesc()](#getZeroDesc--) | 获取或设置一个值，以指示基元素的下降（基线以下的深度）是否应视为零。 |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | 获取或设置一个值，以指示基元素的下降（基线以下的深度）是否应视为零。 |
| [getTransp()](#getTransp--) | 获取或设置一个值，以指示幻影是否对基于类的间距规则透明。 |
| [setTransp(boolean value)](#setTransp-boolean-) | 获取或设置一个值，以指示幻影是否对基于类的间距规则透明。 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

基参数

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
>  ```

**返回：**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```

获取或设置一个值，以指示是否显示基元素。

--------------------

当为 false 时，基元素被隐藏，但仍可能根据其他幻影设置占用空间。对应 OMML 属性 m:show。

**返回：**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

获取或设置一个值，以指示是否显示基元素。

--------------------

当为 false 时，基元素被隐藏，但仍可能根据其他幻影设置占用空间。对应 OMML 属性 m:show。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

获取或设置一个值，以指示基元素的宽度是否应视为零。

--------------------

当为 true 时，幻影不会为其基元素保留水平空间。对应 OMML 属性 m:zeroWid。

**返回：**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

获取或设置一个值，以指示基元素的宽度是否应视为零。

--------------------

当为 true 时，幻影不会为其基元素保留水平空间。对应 OMML 属性 m:zeroWid。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

获取或设置一个值，以指示基元素的上升（基线以上的高度）是否应视为零。

--------------------

当为 true 时，幻影不会提升周围数学行的基线。对应 OMML 属性 m:zeroAsc。

**返回：**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

获取或设置一个值，以指示基元素的上升（基线以上的高度）是否应视为零。

--------------------

当为 true 时，幻影不会提升周围数学行的基线。对应 OMML 属性 m:zeroAsc。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

获取或设置一个值，以指示基元素的下降（基线以下的深度）是否应视为零。

--------------------

当为 true 时，幻影不会降低周围数学行的基线。对应 OMML 属性 m:zeroDesc。

**返回：**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

获取或设置一个值，以指示基元素的下降（基线以下的深度）是否应视为零。

--------------------

当为 true 时，幻影不会降低周围数学行的基线。对应 OMML 属性 m:zeroDesc。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

获取或设置一个值，以指示幻影是否对基于类的间距规则透明。

--------------------

当为 true 时，幻影内部的运算符和符号仍会影响幻影周围的数学间距（如同可见）。当为 false 时，类基间距被忽略。对应 OMML 属性 m:transp。

**返回：**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

获取或设置一个值，以指示幻影是否对基于类的间距规则透明。

--------------------

当为 true 时，幻影内部的运算符和符号仍会影响幻影周围的数学间距（如同可见）。当为 false 时，类基间距被忽略。对应 OMML 属性 m:transp。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |