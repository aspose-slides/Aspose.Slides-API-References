---
title: MathPhantom
second_title: Aspose.Slides Java API 参考
description: 表示一个幻影数学对象 ltmphantgt，它影响其子元素的布局，但不一定显示它。
type: docs
url: /zh/com.aspose.slides/mathphantom/
---
**继承:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有实现的接口:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

表示一个幻影数学对象 (<m:phant>)，它影响其子元素的布局，而不一定显示它。幻影可以隐藏其基表达式，同时保留其宽度、高度或深度，以对齐公式或预留空间。可见性和几何行为由属性如 Show、ZeroWid、ZeroAsc、ZeroDesc 和 Transp 控制。

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // 隐藏内容
>  phantom.setZeroWidth(false);     // 保留宽度
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | 使用指定的基数学元素初始化 [MathPhantom](../../com.aspose.slides/mathphantom) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 基参数 |
| [getShow()](#getShow--) | 获取或设置一个值，指示是否显示基元素。 |
| [setShow(boolean value)](#setShow-boolean-) | 获取或设置一个值，指示是否显示基元素。 |
| [getZeroWidth()](#getZeroWidth--) | 获取或设置一个值，指示是否将基元素的宽度视为零。 |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | 获取或设置一个值，指示是否将基元素的宽度视为零。 |
| [getZeroAsc()](#getZeroAsc--) | 获取或设置一个值，指示是否将基元素的上升（基线以上的高度）视为零。 |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | 获取或设置一个值，指示是否将基元素的上升（基线以上的高度）视为零。 |
| [getZeroDesc()](#getZeroDesc--) | 获取或设置一个值，指示是否将基元素的下降（基线以下的深度）视为零。 |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | 获取或设置一个值，指示是否将基元素的下降（基线以下的深度）视为零。 |
| [getTransp()](#getTransp--) | 获取或设置一个值，指示幻影是否对基于类的间距规则透明。 |
| [setTransp(boolean value)](#setTransp-boolean-) | 获取或设置一个值，指示幻影是否对基于类的间距规则透明。 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 控制字符属性 |
| [getChildren()](#getChildren--) | 获取子元素 |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

使用指定的基数学元素初始化 [MathPhantom](../../com.aspose.slides/mathphantom) 类的一个新实例。

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 被幻影控制其可见性和布局的基 [IMathElement](../../com.aspose.slides/imathelement)。该元素定义可能被隐藏或显示的内容，同时仍影响周围数学的几何对齐。 |

--------------------

幻影元素用于在不必显示的情况下保留或抑制其基表达式的可视空间。它对应于 OMML 元素 <m:phant>. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

基参数

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**返回:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```

获取或设置一个值，指示是否显示基元素。

--------------------

当为 false 时，基元素被隐藏，但可能仍占用空间，取决于其他幻影设置。对应于 OMML 属性 m:show。

**返回:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

获取或设置一个值，指示是否显示基元素。

--------------------

当为 false 时，基元素被隐藏，但可能仍占用空间，取决于其他幻影设置。对应于 OMML 属性 m:show。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

获取或设置一个值，指示是否将基元素的宽度视为零。

--------------------

当为 true 时，幻影不为其基元素保留水平空间。对应于 OMML 属性 m:zeroWid。

**返回:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

获取或设置一个值，指示是否将基元素的宽度视为零。

--------------------

当为 true 时，幻影不为其基元素保留水平空间。对应于 OMML 属性 m:zeroWid。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

获取或设置一个值，指示是否将基元素的上升（基线以上的高度）视为零。

--------------------

当为 true 时，幻影不会提升周围数学行的基线。对应于 OMML 属性 m:zeroAsc。

**返回:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

获取或设置一个值，指示是否将基元素的上升（基线以上的高度）视为零。

--------------------

当为 true 时，幻影不会提升周围数学行的基线。对应于 OMML 属性 m:zeroAsc。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

获取或设置一个值，指示是否将基元素的下降（基线以下的深度）视为零。

--------------------

当为 true 时，幻影不会降低周围数学行的基线。对应于 OMML 属性 m:zeroDesc。

**返回:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

获取或设置一个值，指示是否将基元素的下降（基线以下的深度）视为零。

--------------------

当为 true 时，幻影不会降低周围数学行的基线。对应于 OMML 属性 m:zeroDesc。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

获取或设置一个值，指示幻影是否对基于类的间距规则透明。

--------------------

当为 true 时，幻影内部的运算符和符号仍会影响其周围的数学间距（如同可见）。当为 false 时，基于类的间距被忽略。对应于 OMML 属性 m:transp。

**返回:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

获取或设置一个值，指示幻影是否对基于类的间距规则透明。

--------------------

当为 true 时，幻影内部的运算符和符号仍会影响其周围的数学间距（如同可见）。当为 false 时，基于类的间距被忽略。对应于 OMML 属性 m:transp。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

控制字符属性

**返回:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

获取子元素

**返回:**
com.aspose.slides.IMathElement[]