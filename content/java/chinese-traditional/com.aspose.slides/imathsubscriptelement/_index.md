---
title: IMathSubscriptElement
second_title: Aspose.Slides for Java API 參考
description: 指定下標物件，該物件由基底以及置於右下方的縮小尺寸的下標組成。
type: docs
url: /zh-hant/com.aspose.slides/imathsubscriptelement/
---
**所有已實作的介面:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

指定下標物件，該物件由基底和置於右下方的縮小尺寸的下標組成。

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
```
## 方法

| 方法 | 說明 |
| --- | --- |
| [getBase()](#getBase--) | 基底參數 |
| [getSubscript()](#getSubscript--) | 下標 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


基底參數

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
> ```

**返回:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


下標

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**返回:**  
[IMathElement](../../com.aspose.slides/imathelement)