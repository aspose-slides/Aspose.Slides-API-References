---
title: IMathSubscriptElement
second_title: Aspose.Slides for Android Java API referencia
description: Meghatározza az alsó index objektumot, amely egy bázist és egy kisebb méretű, jobbra és alul elhelyezett alsó indexet tartalmaz.
type: docs
url: /hu/com.aspose.slides/imathsubscriptelement/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

Meghatározza az alsó index objektumot, amely egy bázist és egy kisebb méretű, jobbra és alul elhelyezett alsó indexet tartalmaz.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
>  ```
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Bázis argumentum |
| [getSubscript()](#getSubscript--) | Alsó index |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Bázis argumentum

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
> ```

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Alsó index

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)