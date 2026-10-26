---
title: IMathPhantom
second_title: Aspose.Slides dla Java – dokumentacja API
description: Reprezentuje fantomowy obiekt matematyczny ltmphantgt, który wpływa na układ elementu potomnego, niekoniecznie go wyświetlając.
type: docs
url: /pl/com.aspose.slides/imathphantom/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Reprezentuje obiekt matematyczny typu phantom (<m:phant>), który wpływa na układ swojego elementu potomnego, niekoniecznie go wyświetlając. Phantom może ukrywać wyrażenie bazowe, zachowując jego szerokość, wysokość lub głębokość, aby wyrównać formuły lub zarezerwować miejsce. Widoczność i zachowanie geometrii są kontrolowane przez właściwości takie jak Show, ZeroWid, ZeroAsc, ZeroDesc oraz Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Ukryj zawartość
>  phantom.setZeroWidth(false);     // Zachowaj szerokość
>  ```
## Metody

| Metoda | Opis |
| --- | --- |
| [getBase()](#getBase--) | Argument bazowy |
| [getShow()](#getShow--) | Pobiera lub ustawia wartość określającą, czy element bazowy jest wyświetlany. |
| [setShow(boolean value)](#setShow-boolean-) | Pobiera lub ustawia wartość określającą, czy element bazowy jest wyświetlany. |
| [getZeroWidth()](#getZeroWidth--) | Pobiera lub ustawia wartość określającą, czy szerokość elementu bazowego ma być traktowana jako zero. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Pobiera lub ustawia wartość określającą, czy szerokość elementu bazowego ma być traktowana jako zero. |
| [getZeroAsc()](#getZeroAsc--) | Pobiera lub ustawia wartość określającą, czy wzniesienie (wysokość powyżej linii bazowej) elementu bazowego ma być traktowane jako zero. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Pobiera lub ustawia wartość określającą, czy wzniesienie (wysokość powyżej linii bazowej) elementu bazowego ma być traktowane jako zero. |
| [getZeroDesc()](#getZeroDesc--) | Pobiera lub ustawia wartość określającą, czy opad (głębokość poniżej linii bazowej) elementu bazowego ma być traktowane jako zero. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Pobiera lub ustawia wartość określającą, czy opad (głębokość poniżej linii bazowej) elementu bazowego ma być traktowane jako zero. |
| [getTransp()](#getTransp--) | Pobiera lub ustawia wartość określającą, czy phantom jest przezroczysty dla reguł odstępów opartych na klasach. |
| [setTransp(boolean value)](#setTransp-boolean-) | Pobiera lub ustawia wartość określającą, czy phantom jest przezroczysty dla reguł odstępów opartych na klasach. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argument bazowy

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
>  ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```

Pobiera lub ustawia wartość określającą, czy element bazowy jest wyświetlany.

--------------------

Gdy wartość jest false, element bazowy jest ukryty, ale może nadal zajmować miejsce w zależności od innych ustawień phantom. Odpowiada atrybutowi OMML m:show.

**Zwraca:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

Pobiera lub ustawia wartość określającą, czy element bazowy jest wyświetlany.

--------------------

Gdy wartość jest false, element bazowy jest ukryty, ale może nadal zajmować miejsce w zależności od innych ustawień phantom. Odpowiada atrybutowi OMML m:show.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

Pobiera lub ustawia wartość określającą, czy szerokość elementu bazowego ma być traktowana jako zero.

--------------------

Gdy wartość jest true, phantom nie rezerwuje poziomego miejsca dla swojego elementu bazowego. Odpowiada atrybutowi OMML m:zeroWid.

**Zwraca:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

Pobiera lub ustawia wartość określającą, czy szerokość elementu bazowego ma być traktowana jako zero.

--------------------

Gdy wartość jest true, phantom nie rezerwuje poziomego miejsca dla swojego elementu bazowego. Odpowiada atrybutowi OMML m:zeroWid.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

Pobiera lub ustawia wartość określającą, czy wzniesienie (wysokość powyżej linii bazowej) elementu bazowego ma być traktowane jako zero.

--------------------

Gdy wartość jest true, phantom nie podnosi linii bazowej otaczającej linii matematycznej. Odpowiada atrybutowi OMML m:zeroAsc.

**Zwraca:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

Pobiera lub ustawia wartość określającą, czy wzniesienie (wysokość powyżej linii bazowej) elementu bazowego ma być traktowane jako zero.

--------------------

Gdy wartość jest true, phantom nie podnosi linii bazowej otaczającej linii matematycznej. Odpowiada atrybutowi OMML m:zeroAsc.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

Pobiera lub ustawia wartość określającą, czy opad (głębokość poniżej linii bazowej) elementu bazowego ma być traktowane jako zero.

--------------------

Gdy wartość jest true, phantom nie obniża linii bazowej otaczającej linii matematycznej. Odpowiada atrybutowi OMML m:zeroDesc.

**Zwraca:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

Pobiera lub ustawia wartość określającą, czy opad (głębokość poniżej linii bazowej) elementu bazowego ma być traktowane jako zero.

--------------------

Gdy wartość jest true, phantom nie obniża linii bazowej otaczającej linii matematycznej. Odpowiada atrybutowi OMML m:zeroDesc.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

Pobiera lub ustawia wartość określającą, czy phantom jest przezroczysty dla reguł odstępów opartych na klasach.

--------------------

Gdy wartość jest true, operatory i symbole wewnątrz phantom nadal wpływają na odstępy matematyczne wokół phantom (tak jakby były widoczne). Gdy wartość jest false, reguły odstępów oparte na klasach są ignorowane. Odpowiada atrybutowi OMML m:transp.

**Zwraca:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

Pobiera lub ustawia wartość określającą, czy phantom jest przezroczysty dla reguł odstępów opartych na klasach.

--------------------

Gdy wartość jest true, operatory i symbole wewnątrz phantom nadal wpływają na odstępy matematyczne wokół phantom (tak jakby były widoczne). Gdy wartość jest false, reguły odstępów oparte na klasach są ignorowane. Odpowiada atrybutowi OMML m:transp.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |