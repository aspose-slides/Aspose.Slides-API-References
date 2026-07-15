---
title: IMathSuperscriptElement
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 指定上標物件，此物件由基底以及放置於右上方且尺寸較小的上標組成
type: docs
url: /zh-hant/com.aspose.slides/imathsuperscriptelement/
---
**所有已實作的介面：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

指定上標物件，此物件由基底與放置於右上方且尺寸較小的上標組成

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
>  ```

## 方法

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | 基底參數 |
| [getSuperscript()](#getSuperscript--) | 上標 |
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
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**回傳值:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


上標

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```


**回傳值:**
[IMathElement](../../com.aspose.slides/imathelement)