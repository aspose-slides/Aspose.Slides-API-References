---
title: IMathLimit
second_title: Aspose.Slides per Android via Riferimento API Java
description: Specifica l'oggetto Limit costituito da testo sulla linea di base e testo di dimensione ridotta immediatamente sopra o sotto di esso.
type: docs
url: /it/com.aspose.slides/imathlimit/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLimit extends IMathElement
```

Specifica l'oggetto Limit, costituito da testo sulla linea di base e testo di dimensione ridotta immediatamente sopra o sotto di esso.

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getLimit()](#getLimit--) | Limit argument |
| [getUpperLimit()](#getUpperLimit--) | Specifies upper or lower limit |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | Specifies upper or lower limit |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argomento base

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement baseArg = limitElement.getBase();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getLimit() {#getLimit--}
```
public abstract IMathElement getLimit()
```

Argomento limite

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement limitArg = limitElement.getLimit();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getUpperLimit() {#getUpperLimit--}
```
public abstract boolean getUpperLimit()
```

Specifica il limite superiore o inferiore

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**Restituisce:**
boolean
### setUpperLimit(boolean value) {#setUpperLimit-boolean-}
```
public abstract void setUpperLimit(boolean value)
```

Specifica il limite superiore o inferiore

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |