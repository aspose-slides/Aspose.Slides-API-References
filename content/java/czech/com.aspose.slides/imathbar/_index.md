---
title: IMathBar
second_title: Aspose.Slides pro Java referenční příručka API
description: Určuje funkci bar, skládající se ze základního argumentu a nadčáry nebo podčáry
type: docs
url: /cs/com.aspose.slides/imathbar/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Určuje funkci bar, skládající se ze základního argumentu a nadčáry nebo podčáry

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Základní argument |
| [getPosition()](#getPosition--) | Pozice čáry baru. |
| [setPosition(int value)](#setPosition-int-) | Pozice čáry baru. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Základní argument

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Pozice čáry baru. Výchozí: Horní

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Vrací:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Pozice čáry baru. Výchozí: Horní

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |