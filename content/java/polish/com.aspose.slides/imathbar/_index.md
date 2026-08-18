---
title: IMathBar
second_title: Aspose.Slides dla Java – odniesienie API
description: Określa funkcję kreski, składającą się z argumentu bazowego oraz kreski nad lub pod
type: docs
url: /pl/com.aspose.slides/imathbar/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Określa funkcję kreski, składającą się z argumentu bazowego oraz kreski nad lub pod

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
| [getPosition()](#getPosition--) | Pozycja linii kreski. |
| [setPosition(int value)](#setPosition-int-) | Pozycja linii kreski. |
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


Pozycja linii kreski. Domyślnie: Góra

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


Pozycja linii kreski. Domyślnie: Góra

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