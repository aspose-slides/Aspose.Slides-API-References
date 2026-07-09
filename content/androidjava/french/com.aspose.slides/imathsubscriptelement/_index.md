---
title: IMathSubscriptElement
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Spécifie l'objet indice qui se compose d'une base et d'un indice de taille réduite placé en dessous et à droite.
type: docs
url: /fr/com.aspose.slides/imathsubscriptelement/
---
**Toutes les interfaces implémentées:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

Spécifie l'objet indice, qui se compose d'une base et d'un indice de taille réduite placé en dessous et à droite.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getSubscript()](#getSubscript--) | Subscript |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Base argument

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()

Subscript

--------------------

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**Renvoie:**  
[IMathElement](../../com.aspose.slides/imathelement)