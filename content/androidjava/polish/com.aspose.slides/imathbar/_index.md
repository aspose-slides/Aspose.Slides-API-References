---
title: IMathBar
second_title: Aspose.Slides dla Androida przy użyciu interfejsu API Java
description: Określa funkcję paska składającą się z argumentu bazowego oraz górnego lub dolnego paska
type: docs
url: /pl/com.aspose.slides/imathbar/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Określa funkcję paska, składającą się z argumentu bazowego oraz górnego lub dolnego paska

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Metody

| Metoda | Opis |
| --- | --- |
| [getBase()](#getBase--) | Argument bazowy |
| [getPosition()](#getPosition--) | Pozycja linii paska. |
| [setPosition(int value)](#setPosition-int-) | Pozycja linii paska. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argument bazowy

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Pozycja linii paska. Domyślnie: Góra

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Zwraca:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Pozycja linii paska. Domyślnie: Góra

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |