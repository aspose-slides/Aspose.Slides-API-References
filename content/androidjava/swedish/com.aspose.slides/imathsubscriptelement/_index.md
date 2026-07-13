---
title: IMathSubscriptElement
second_title: Aspose.Slides för Android via Java API-referens
description: Specificerar subskriptobjektet som består av en bas och ett förminskat subskript placerat nedanför och till höger.
type: docs
url: /sv/com.aspose.slides/imathsubscriptelement/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

Specificerar subskriptobjektet, som består av en bas och ett förminskat subskript placerat nedanför och till höger.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBase()](#getBase--) | Basargument |
| [getSubscript()](#getSubscript--) | Subskript |
### getBase() {#getBase--}
``` 
public abstract IMathElement getBase()
```


Basargument

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Subskript

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)