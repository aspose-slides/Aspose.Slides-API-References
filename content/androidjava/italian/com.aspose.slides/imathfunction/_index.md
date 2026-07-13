---
title: IMathFunction
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Specifica una funzione di un argomento.
type: docs
url: /it/com.aspose.slides/imathfunction/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

Specifica una funzione di un argomento.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
>  ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getName()](#getName--) | Nome della funzione Per esempio, i nomi delle funzioni sono sin e cos |
| [getBase()](#getBase--) | Argomento della funzione |
### getName() {#getName--}
```
public abstract IMathElement getName()
```

Nome della funzione Per esempio, i nomi delle funzioni sono sin e cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
>  ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argomento della funzione

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)