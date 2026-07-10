---
title: IMathPhantom
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个 phantom math 对象 ltmphantgt，它影响其子元素的布局，但不一定显示它。
type: docs
url: /zh/com.aspose.slides/imathphantom/
---
**所有实现的接口：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

表示一个 phantom math 对象 (<m:phant>)，它影响其子元素的布局，而不一定显示它。phantom 可以隐藏其基表达式，同时保留其宽度、高度或深度，以对齐公式或保留空间。可见性和几何行为由属性如 Show、ZeroWid、ZeroAsc、ZeroDesc 和 Transp 控制。

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // 隐藏内容
>  phantom.setZeroWidth(false);     // 保持宽度
> ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getShow()](#getShow--) | Gets or sets a value indicating whether the base element is displayed. |
| [setShow(boolean value)](#setShow-boolean-) | Gets or sets a value indicating whether the base element is displayed. |
| [getZeroWidth()](#getZeroWidth--) | Gets or sets a value indicating whether the width of the base element should be treated as zero. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Gets or sets a value indicating whether the width of the base element should be treated as zero. |
| [getZeroAsc()](#getZeroAsc--) | Gets or sets a value indicating whether the ascent (height above baseline) of the base element should be treated as zero. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Gets or sets a value indicating whether the ascent (height above baseline) of the base element should be treated as zero. |
| [getZeroDesc()](#getZeroDesc--) | Gets or sets a value indicating whether the descent (depth below baseline) of the base element should be treated as zero. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Gets or sets a value indicating whether the descent (depth below baseline) of the base element should be treated as zero. |
| [getTransp()](#getTransp--) | Gets or sets a value indicating whether the phantom is transparent for class-based spacing rules. |
| [setTransp(boolean value)](#setTransp-boolean-) | Gets or sets a value indicating whether the phantom is transparent for class-based spacing rules. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Base argument

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```

Gets or sets a value indicating whether the base element is displayed.

--------------------

When false, the base element is hidden but may still occupy space depending on other phantom settings. Corresponds to the OMML attribute m:show.

**Returns:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

Gets or sets a value indicating whether the base element is displayed.

--------------------

When false, the base element is hidden but may still occupy space depending on other phantom settings. Corresponds to the OMML attribute m:show.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

Gets or sets a value indicating whether the width of the base element should be treated as zero.

--------------------

When true, the phantom does not reserve horizontal space for its base. Corresponds to the OMML attribute m:zeroWid.

**Returns:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

Gets or sets a value indicating whether the width of the base element should be treated as zero.

--------------------

When true, the phantom does not reserve horizontal space for its base. Corresponds to the OMML attribute m:zeroWid.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

Gets or sets a value indicating whether the ascent (height above baseline) of the base element should be treated as zero.

--------------------

When true, the phantom does not raise the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroAsc.

**Returns:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

Gets or sets a value indicating whether the ascent (height above baseline) of the base element should be treated as zero.

--------------------

When true, the phantom does not raise the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroAsc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

Gets or sets a value indicating whether the descent (depth below baseline) of the base element should be treated as zero.

--------------------

When true, the phantom does not lower the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroDesc.

**Returns:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

Gets or sets a value indicating whether the descent (depth below baseline) of the base element should be treated as zero.

--------------------

When true, the phantom does not lower the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroDesc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

Gets or sets a value indicating whether the phantom is transparent for class-based spacing rules.

--------------------

When true, operators and symbols inside the phantom still affect mathematical spacing around the phantom (as if visible). When false, class-based spacing is ignored. Corresponds to the OMML attribute m:transp.

**Returns:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)

获取或设置一个值，指示 phantom 是否对基于类的间距规则透明。

--------------------

当为 true 时，phantom 中的运算符和符号仍会影响 phantom 周围的数学间距（如同可见）。当为 false 时，基于类的间距将被忽略。对应于 OMML 属性 m:transp。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |