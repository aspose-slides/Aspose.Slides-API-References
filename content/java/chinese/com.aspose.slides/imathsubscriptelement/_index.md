---
title: IMathSubscriptElement
second_title: Aspose.Slides for Java API 参考
description: 指定下标对象，该对象由基准和放置在右下方的缩小尺寸下标组成。
type: docs
url: /zh/com.aspose.slides/imathsubscriptelement/
---
**所有实现的接口：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

指定下标对象，该对象由基准和放置在右下方的缩小尺寸下标组成。

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 基准参数 |
| [getSubscript()](#getSubscript--) | 下标 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


基准参数

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
> ```

**返回：**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


下标

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**返回：**
[IMathElement](../../com.aspose.slides/imathelement)