---
title: MathPhantom
second_title: Referencja API Aspose.Slides dla Java
description: Reprezentuje fantomowy obiekt matematyczny <m:phant>, który wpływa na układ elementu potomnego, niekoniecznie go wyświetlając.
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

Reprezentuje fantomowy obiekt matematyczny (<m:phant>), który wpływa na układ swojego elementu potomnego, niekoniecznie go wyświetlając. Fantom może ukrywać swoją bazową wyrażenie, zachowując jednocześnie jego szerokość, wysokość lub głębokość, aby wyrównać formuły lub zarezerwować miejsce. Widoczność i zachowanie geometrii są kontrolowane przez właściwości takie jak Show, ZeroWid, ZeroAsc, ZeroDesc i Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Ukryj zawartość
>  phantom.setZeroWidth(false);     // Zachowaj szerokość
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Inicjalizuje nową instancję klasy [MathPhantom](../../com.aspose.slides/mathphantom) przy użyciu określonego bazowego elementu matematycznego. |
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
| [getZeroDesc()](#getZeroDesc--) | Pobiera lub ustawia wartość określającą, czy opuszczenie (głębokość pod linią bazową) elementu bazowego ma być traktowane jako zero. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Pobiera lub ustawia wartość określającą, czy opuszczenie (głębokość pod linią bazową) elementu bazowego ma być traktowane jako zero. |
| [getTransp()](#getTransp--) | Pobiera lub ustawia wartość określającą, czy fantom jest przezroczysty dla reguł odstępów opartych na klasie. |
| [setTransp(boolean value)](#setTransp-boolean-) | Pobiera lub ustawia wartość określającą, czy fantom jest przezroczysty dla reguł odstępów opartych na klasie. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Właściwości znaku kontrolnego |
| [getChildren()](#getChildren--) | Pobierz elementy potomne |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```


Inicjalizuje nową instancję klasy [MathPhantom](../../com.aspose.slides/mathphantom) przy użyciu określonego bazowego elementu matematycznego.

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
| element | [IMathElement](../../com.aspose.slides/imathelement) | Bazowy [IMathElement](../../com.aspose.slides/imathelement), którego widoczność i układ będą kontrolowane przez fantom. Ten element definiuje zawartość, którą można ukrywać lub pokazywać, jednocześnie wpływając na geometryczne wyrównanie otaczającej matematyki.

--------------------

Element fantomu jest używany do zarezerwowania lub zablokowania wizualnej przestrzeni wyrażenia bazowego bez konieczności jego wyświetlania. Odpowiada elementowi OMML <m:phant>. |
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

Gdy wartość jest false, element bazowy jest ukryty, ale może nadal zajmować przestrzeń w zależności od innych ustawień fantomu. Odpowiada atrybutowi OMML m:show.

**Zwraca:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```


Pobiera lub ustawia wartość określającą, czy element bazowy jest wyświetlany.

--------------------

Gdy wartość jest false, element bazowy jest ukryty, ale może nadal zajmować przestrzeń w zależności od innych ustawień fantomu. Odpowiada atrybutowi OMML m:show.

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

Gdy wartość jest true, fantom nie rezerwuje miejsca poziomego dla swojej podstawy. Odpowiada atrybutowi OMML m:zeroWid.

**Zwraca:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```


Pobiera lub ustawia wartość określającą, czy szerokość elementu bazowego ma być traktowana jako zero.

--------------------

Gdy wartość jest true, fantom nie rezerwuje miejsca poziomego dla swojej podstawy. Odpowiada atrybutowi OMML m:zeroWid.

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

Gdy wartość jest true, fantom nie podnosi linii bazowej otaczającej linii matematycznej. Odpowiada atrybutowi OMML m:zeroAsc.

**Zwraca:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```


Pobiera lub ustawia wartość określającą, czy wzniesienie (wysokość powyżej linii bazowej) elementu bazowego ma być traktowane jako zero.

--------------------

Gdy wartość jest true, fantom nie podnosi linii bazowej otaczającej linii matematycznej. Odpowiada atrybutowi OMML m:zeroAsc.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```


Pobiera lub ustawia wartość określającą, czy opuszczenie (głębokość pod linią bazową) elementu bazowego ma być traktowane jako zero.

--------------------

Gdy wartość jest true, fantom nie obniża linii bazowej otaczającej linii matematycznej. Odpowiada atrybutowi OMML m:zeroDesc.

**Zwraca:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```


Pobiera lub ustawia wartość określającą, czy opuszczenie (głębokość pod linią bazową) elementu bazowego ma być traktowane jako zero.

--------------------

Gdy wartość jest true, fantom nie obniża linii bazowej otaczającej linii matematycznej. Odpowiada atrybutowi OMML m:zeroDesc.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```


Pobiera lub ustawia wartość określającą, czy fantom jest przezroczysty dla reguł odstępów opartych na klasie.

--------------------

Gdy wartość jest true, operatory i symbole wewnątrz fantomu nadal wpływają na odstępy matematyczne wokół fantomu (tak jakby były widoczne). Gdy wartość jest false, reguły odstępów oparte na klasie są ignorowane. Odpowiada atrybutowi OMML m:transp.

**Zwraca:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```


Pobiera lub ustawia wartość określającą, czy fantom jest przezroczysty dla reguł odstępów opartych na klasie.

--------------------

Gdy wartość jest true, operatory i symbole wewnątrz fantomu nadal wpływają na odstępy matematyczne wokół fantomu (tak jakby były widoczne). Gdy wartość jest false, reguły odstępów oparte na klasie są ignorowane. Odpowiada atrybutowi OMML m:transp.

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


Pobierz elementy potomne

**Zwraca:**
com.aspose.slides.IMathElement[]