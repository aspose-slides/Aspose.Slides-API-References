---
title: IMathSubscriptElement
second_title: Aspose.Slides for Android için Java API Referansı
description: Alt simge nesnesini belirtir; bu nesne, bir taban ve aşağıya ve sağa konumlandırılmış küçültülmüş bir alt simgeden oluşur.
type: docs
url: /tr/com.aspose.slides/imathsubscriptelement/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

Alt simge nesnesini belirtir; bu nesne, bir taban ve aşağıya ve sağa konumlandırılmış küçültülmüş bir alt simgeden oluşur.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## Yöntemler

| Method | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Taban argümanı |
| [getSubscript()](#getSubscript--) | Alt simge |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Taban argümanı

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Alt simge

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)