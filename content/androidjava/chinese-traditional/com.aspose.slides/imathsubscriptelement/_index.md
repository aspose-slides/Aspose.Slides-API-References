---
title: IMathSubscriptElement
second_title: Aspose.Slides for Android 之 Java API 參考
description: 指定下標物件，該物件由基礎和放置於右下方的縮小尺寸下標組成。
type: docs
url: /zh-hant/com.aspose.slides/imathsubscriptelement/
---
**全部實作的介面：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

指定下標物件，其由基礎與放置在右下方的縮小尺寸下標組成。

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 基礎參數 |
| [getSubscript()](#getSubscript--) | 下標 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

基礎參數

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

**返回：**
[IMathElement](../../com.aspose.slides/imathelement)