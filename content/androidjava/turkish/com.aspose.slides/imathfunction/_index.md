---
title: IMathFunction
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Bir argümanın fonksiyonunu belirler.
type: docs
url: /tr/com.aspose.slides/imathfunction/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

Bir argümanın fonksiyonunu belirler.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getName()](#getName--) | Fonksiyon adı Örneğin, fonksiyon adları sin ve cos |
| [getBase()](#getBase--) | Fonksiyon Argümanı |
### getName() {#getName--}
```
public abstract IMathElement getName()
```

Fonksiyon adı Örneğin, fonksiyon adları sin ve cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Fonksiyon Argümanı

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)