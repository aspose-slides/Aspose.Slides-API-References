---
title: IMathBar
second_title: Riferimento API Java di Aspose.Slides per Android
description: Specifica la funzione barra, costituita da un argomento di base e da una linea sopra o sotto
type: docs
url: /it/com.aspose.slides/imathbar/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Specifica la funzione barra, costituita da un argomento di base e da una linea sopra o sotto

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBase()](#getBase--) | Argomento di base |
| [getPosition()](#getPosition--) | Posizione della linea della barra. |
| [setPosition(int value)](#setPosition-int-) | Posizione della linea della barra. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argomento di base

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Posizione della linea della barra. Predefinito: In alto

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Restituisce:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Posizione della linea della barra. Predefinito: In alto

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |