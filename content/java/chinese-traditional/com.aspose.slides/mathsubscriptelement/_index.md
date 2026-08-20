---
title: MathSubscriptElement
second_title: Aspose.Slides for Java API 參考
description: 指定下標物件，此物件由基底以及放置在右下方的縮小尺寸下標組成。
type: docs
url: /zh-hant/com.aspose.slides/mathsubscriptelement/
---
**繼承:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**所有實作的介面:**
[com.aspose.slides.IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
```
public final class MathSubscriptElement extends BaseScript implements IMathSubscriptElement
```

指定下標物件，此物件由基底與放置在右下方的縮小尺寸下標組成。

--------------------

> ```
> 範例：
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
```
## 建構子

| 建構子 | 說明 |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 初始化 MathSubscriptElement 類別的新實例。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getSubscript()](#getSubscript--) | 下標 |
| [getChildren()](#getChildren--) | 取得子元素 |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```


初始化 MathSubscriptElement 類別的新實例。

--------------------

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


下標

--------------------

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**傳回值:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


取得子元素

**傳回值:**
com.aspose.slides.IMathElement[]