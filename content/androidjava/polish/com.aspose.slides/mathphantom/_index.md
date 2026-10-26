---
title: MathPhantom
second_title: Aspose.Slides dla Androida – dokumentacja API Java
description: Reprezentuje fantomowy obiekt matematyczny ltmphantgt, który wpływa na układ elementu podrzędnego, niekoniecznie go wyświetlając.
type: docs
url: /pl/com.aspose.slides/mathphantom/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

Reprezentuje fikcyjny obiekt matematyczny (<m:phant>), który wpływa na układ elementu podrzędnego, niekoniecznie wyświetlając go. Fikcyjny obiekt może ukrywać swoją podstawową ekspresję, zachowując jednocześnie szerokość, wysokość lub głębokość w celu wyrównania formuł lub zarezerwowania miejsca. Widoczność i zachowanie geometrii są kontrolowane przez właściwości takie jak Show, ZeroWid, ZeroAsc, ZeroDesc oraz Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Ukryj treść
>  phantom.setZeroWidth(false);     // Zachowaj szerokość
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Inicjalizuje nową instancję klasy [MathPhantom](../../com.aspose.slides/mathphantom) przy użyciu określonego podstawowego elementu matematycznego. |
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
| [getZeroDesc()](#getZeroDesc--) | Pobiera lub ustawia wartość określającą, czy opuszczenie (głębokość poniżej linii bazowej) elementu bazowego ma być traktowane jako zero. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Pobiera lub ustawia wartość określającą, czy opuszczenie (głębokość poniżej linii bazowej) elementu bazowego ma być traktowane jako zero. |
| [getTransp()](#getTransp--) | Pobiera lub ustawia wartość określającą, czy fikcyjny obiekt jest przezroczysty dla reguł odstępów opartych na klasie. |
| [setTransp(boolean value)](#setTransp-boolean-) | Pobiera lub ustawia wartość określającą, czy fikcyjny obiekt jest przezroczysty dla reguł odstępów opartych na klasie. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Właściwości znaku kontrolnego |
| [getChildren()](#getChildren--) | Pobierz elementy podrzędne |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

Inicjalizuje nową instancję klasy [MathPhantom](../../com.aspose.slides/mathphantom) przy użyciu określonego podstawowego elementu matematycznego.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Podstawowy [IMathElement](../../com.aspose.slides/imathelement), którego widoczność i układ będą kontrolowane przez fikcyjny obiekt. Ten element definiuje zawartość, którą można ukryć lub wyświetlić, jednocześnie wpływając na geometryczne wyrównanie otaczających go elementów matematycznych.

--------------------

Fikcyjny element służy do rezerwowania lub tłumienia widzialnej przestrzeni swojej podstawowej ekspresji, niekoniecznie ją wyświetlając. Odpowiada elementowi OMML <m:phant>. |
### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argument bazowy

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```

Pobiera lub ustawia wartość określającą, czy element bazowy jest wyświetlany.

--------------------

Gdy wartość jest fałszywa, element bazowy jest ukryty, ale może nadal zajmować miejsce w zależności od innych ustawień fikcyjnego obiektu. Odpowiada atrybutowi OMML m:show.

**Zwraca:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

Pobiera lub ustawia wartość określającą, czy element bazowy jest wyświetlany.

--------------------

Gdy wartość jest fałszywa, element bazowy jest ukryty, ale może nadal zajmować miejsce w zależności od innych ustawień fikcyjnego obiektu. Odpowiada atrybutowi OMML m:show.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

Pobiera lub ustawia wartość określającą, czy szerokość elementu bazowego ma być traktowana jako zero.

--------------------

Gdy wartość jest prawdziwa, fikcyjny obiekt nie rezerwuje poziomej przestrzeni dla swojego podstawowego elementu. Odpowiada atrybutowi OMML m:zeroWid.

**Zwraca:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

Pobiera lub ustawia wartość określającą, czy szerokość elementu bazowego ma być traktowana jako zero.

--------------------

Gdy wartość jest prawdziwa, fikcyjny obiekt nie rezerwuje poziomej przestrzeni dla swojego podstawowego elementu. Odpowiada atrybutowi OMML m:zeroWid.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

Pobiera lub ustawia wartość określającą, czy wzniesienie (wysokość powyżej linii bazowej) elementu bazowego ma być traktowane jako zero.

--------------------

Gdy wartość jest prawdziwa, fikcyjny obiekt nie podnosi linii bazowej otaczającej linii matematycznej. Odpowiada atrybutowi OMML m:zeroAsc.

**Zwraca:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

Pobiera lub ustawia wartość określającą, czy wzniesienie (wysokość powyżej linii bazowej) elementu bazowego ma być traktowane jako zero.

--------------------

Gdy wartość jest prawdziwa, fikcyjny obiekt nie podnosi linii bazowej otaczającej linii matematycznej. Odpowiada atrybutowi OMML m:zeroAsc.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

Pobiera lub ustawia wartość określającą, czy opuszczenie (głębokość poniżej linii bazowej) elementu bazowego ma być traktowane jako zero.

--------------------

Gdy wartość jest prawdziwa, fikcyjny obiekt nie obniża linii bazowej otaczającej linii matematycznej. Odpowiada atrybutowi OMML m:zeroDesc.

**Zwraca:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

Pobiera lub ustawia wartość określającą, czy opuszczenie (głębokość poniżej linii bazowej) elementu bazowego ma być traktowane jako zero.

--------------------

Gdy wartość jest prawdziwa, fikcyjny obiekt nie obniża linii bazowej otaczającej linii matematycznej. Odpowiada atrybutowi OMML m:zeroDesc.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

Pobiera lub ustawia wartość określającą, czy fikcyjny obiekt jest przezroczysty dla reguł odstępów opartych na klasie.

--------------------

Gdy wartość jest prawdziwa, operatory i symbole wewnątrz fikcyjnego obiektu nadal wpływają na odstępy matematyczne wokół niego (tak, jakby były widoczne). Gdy wartość jest fałszywa, reguły odstępów oparte na klasie są ignorowane. Odpowiada atrybutowi OMML m:transp.

**Zwraca:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

Pobiera lub ustawia wartość określającą, czy fikcyjny obiekt jest przezroczysty dla reguł odstępów opartych na klasie.

--------------------

Gdy wartość jest prawdziwa, operatory i symbole wewnątrz fikcyjnego obiektu nadal wpływają na odstępy matematyczne wokół niego (tak, jakby były widoczne). Gdy wartość jest fałszywa, reguły odstępów oparte na klasie są ignorowane. Odpowiada atrybutowi OMML m:transp.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Właściwości znaku kontrolnego

**Zwraca:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Pobierz elementy podrzędne

**Zwraca:**
com.aspose.slides.IMathElement[]