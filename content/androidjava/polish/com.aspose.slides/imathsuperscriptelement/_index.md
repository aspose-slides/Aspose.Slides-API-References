---
title: IMathSuperscriptElement
second_title: Aspose.Slides dla Androida - referencja API Java
description: Określa obiekt indeksu górnego, który składa się z podstawy i zmniejszonego indeksu górnego umieszczonego powyżej i po prawej stronie
type: docs
url: /pl/com.aspose.slides/imathsuperscriptelement/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

Określa obiekt indeksu górnego, który składa się z podstawy i zmniejszonego indeksu górnego umieszczonego powyżej i po prawej stronie

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## Metody

| Metoda | Opis |
| --- | --- |
| [getBase()](#getBase--) | Argument bazowy |
| [getSuperscript()](#getSuperscript--) | Indeks górny |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argument bazowy

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Indeks górny

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)