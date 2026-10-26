---
title: IMathLimit
second_title: Aspose.Slides for Android Java API Referansı
description: Temel çizgideki metin ve hemen üstünde veya altında bulunan küçültülmüş metinden oluşan Limit nesnesini belirtir.
type: docs
url: /tr/com.aspose.slides/imathlimit/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLimit extends IMathElement
```

Limit nesnesini belirtir; bu nesne, temel çizgideki metin ile hemen üstünde veya altında bulunan daha küçük metinden oluşur.

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
> ```
## Metotlar

| Metod | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Base argümanı |
| [getLimit()](#getLimit--) | Limit argümanı |
| [getUpperLimit()](#getUpperLimit--) | Üst veya alt sınırı belirtir |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | Üst veya alt sınırı belirtir |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Base argümanı

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement baseArg = limitElement.getBase();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getLimit() {#getLimit--}
```
public abstract IMathElement getLimit()
```

Limit argümanı

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement limitArg = limitElement.getLimit();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getUpperLimit() {#getUpperLimit--}
```
public abstract boolean getUpperLimit()
```

Üst veya alt sınırı belirtir

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**Döndürür:**
boolean
### setUpperLimit(boolean value) {#setUpperLimit-boolean-}
```
public abstract void setUpperLimit(boolean value)
```

Üst veya alt sınırı belirtir

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |