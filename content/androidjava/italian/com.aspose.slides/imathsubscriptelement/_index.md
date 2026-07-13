---
title: IMathSubscriptElement
second_title: Riferimento API Java di Aspose.Slides per Android
description: Specifica l'oggetto pedice, che è composto da una base e da un pedice di dimensioni ridotte posizionato sotto e a destra.
type: docs
url: /it/com.aspose.slides/imathsubscriptelement/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

Specifica l'oggetto pedice, che è composto da una base e un pedice di dimensione ridotta posizionato sotto e a destra.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBase()](#getBase--) | Argomento base |
| [getSubscript()](#getSubscript--) | Pedice |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argomento base

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Pedice

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)