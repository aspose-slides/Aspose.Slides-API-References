---
title: IMathLimit
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يحدد كائن Limit المكوّن من نص على الخط الأساسي ونص مصغر مباشرةً فوقه أو تحته.
type: docs
url: /ar/com.aspose.slides/imathlimit/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLimit extends IMathElement
```

يحدد كائن Limit، المكوّن من نص على الخط الأساسي ونص مصغر مباشرةً فوقه أو تحته.

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
> ```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getLimit()](#getLimit--) | Limit argument |
| [getUpperLimit()](#getUpperLimit--) | Specifies upper or lower limit |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | Specifies upper or lower limit |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


معامل القاعدة

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement baseArg = limitElement.getBase();
>  ```


**الإرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)
### getLimit() {#getLimit--}
```
public abstract IMathElement getLimit()
```


معامل الحد

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement limitArg = limitElement.getLimit();
> ```

**الإرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)
### getUpperLimit() {#getUpperLimit--}
```
public abstract boolean getUpperLimit()
```


يحدد الحد العلوي أو السفلي

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**الإرجاع:**
boolean
### setUpperLimit(boolean value) {#setUpperLimit-boolean-}
```
public abstract void setUpperLimit(boolean value)
```


يحدد الحد العلوي أو السفلي

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |