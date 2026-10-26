---
title: IMathLimit
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يحدد كائن Limit المكوّن من النص على الخط الأساسي والنص المصغّر مباشرةً فوقه أو تحته.
type: docs
url: /ar/com.aspose.slides/imathlimit/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLimit extends IMathElement
```

يحدد كائن Limit، المكوّن من النص على الخط الأساسي والنص المصغّر مباشرةً فوقه أو تحته.

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  ```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | وسيط القاعدة |
| [getLimit()](#getLimit--) | وسيط الحد |
| [getUpperLimit()](#getUpperLimit--) | يحدد الحد العلوي أو السفلي |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | يحدد الحد العلوي أو السفلي |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


وسيط القاعدة

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement baseArg = limitElement.getBase();
>  ```


**القيمة المرجعة:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getLimit() {#getLimit--}
```
public abstract IMathElement getLimit()
```


وسيط الحد

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement limitArg = limitElement.getLimit();
>  ```

**القيمة المرجعة:**  
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
>  ```


**القيمة المرجعة:**  
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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |