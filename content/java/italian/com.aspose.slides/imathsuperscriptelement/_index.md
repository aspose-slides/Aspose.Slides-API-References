---
title: IMathSuperscriptElement
second_title: Riferimento API di Aspose.Slides per Java
description: Specifica l'oggetto apice, che consiste in una base e un apice di dimensioni ridotte posizionato sopra e a destra
type: docs
url: /it/com.aspose.slides/imathsuperscriptelement/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

Specifica l'oggetto apice, che consiste in una base e un apice di dimensioni ridotte posizionato sopra e a destra

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBase()](#getBase--) | Argomento base |
| [getSuperscript()](#getSuperscript--) | Apice |
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
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Apice

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)