---
title: IMathSubscriptElement
second_title: Aspose.Slides dla Androida poprzez odwołanie API Java
description: Określa obiekt indeksu dolnego, który składa się z podstawy i zmniejszonego indeksu dolnego umieszczonego poniżej i po prawej stronie.
type: docs
url: /pl/com.aspose.slides/imathsubscriptelement/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

Określa obiekt indeksu dolnego, który składa się z podstawy i zmniejszonego indeksu dolnego umieszczonego poniżej i po prawej stronie.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
>  ```
## Metody

| Metoda | Opis |
| --- | --- |
| [getBase()](#getBase--) | Argument podstawy |
| [getSubscript()](#getSubscript--) | Indeks dolny |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argument podstawy

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Indeks dolny

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)