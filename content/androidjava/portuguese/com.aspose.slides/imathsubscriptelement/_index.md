---
title: IMathSubscriptElement
second_title: Aspose.Slides para Android via Referência da API Java
description: Especifica o objeto subscrito que consiste em uma base e um subscrito de tamanho reduzido colocado abaixo e à direita.
type: docs
url: /pt/com.aspose.slides/imathsubscriptelement/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

Especifica o objeto subscrito, que consiste em uma base e um subscrito de tamanho reduzido colocado abaixo e à direita.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## Métodos

| Método | Descrição |
| --- | --- |
| [getBase()](#getBase--) | Argumento da base |
| [getSubscript()](#getSubscript--) | Subscrito |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argumento da base

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Subscrito

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)