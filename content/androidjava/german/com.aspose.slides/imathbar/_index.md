---
title: IMathBar
second_title: Aspose.Slides für Android über Java API Referenz
description: Gibt die Balkenfunktion an, bestehend aus einem Basisargument und einem Über- oder Unterbalken
type: docs
url: /de/com.aspose.slides/imathbar/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Gibt die Balkenfunktion an, bestehend aus einem Basisargument und einem Über- oder Unterbalken

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getPosition()](#getPosition--) | Position der Balkenlinie. |
| [setPosition(int value)](#setPosition-int-) | Position der Balkenlinie. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Basisargument

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Rückgabe:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Position der Balkenlinie. Standard: Oben

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Rückgabe:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Position der Balkenlinie. Standard: Oben

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |