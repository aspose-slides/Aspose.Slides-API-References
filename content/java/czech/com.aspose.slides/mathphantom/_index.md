---
title: MathPhantom
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje fantomový matematický objekt ltmphantgt, který ovlivňuje rozložení svého podřízeného prvku, aniž by jej nutně zobrazoval.
type: docs
url: /cs/com.aspose.slides/mathphantom/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

Reprezentuje fantomový matematický objekt (<m:phant>), který ovlivňuje rozložení svého podřízeného prvku, aniž by jej nutně zobrazoval. Fantom může skrýt svůj základní výraz a přitom zachovat šířku, výšku nebo hloubku pro zarovnání vzorců nebo vyhrazení místa. Viditelnost a geometrické chování jsou řízeny vlastnostmi jako Show, ZeroWid, ZeroAsc, ZeroDesc a Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Skrýt obsah
>  phantom.setZeroWidth(false);     // Zachovat šířku
> ```
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Inicializuje novou instanci třídy [MathPhantom](../../com.aspose.slides/mathphantom) pomocí zadaného základního matematického prvku. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Základní argument |
| [getShow()](#getShow--) | Získá nebo nastaví hodnotu určující, zda je základní prvek zobrazen. |
| [setShow(boolean value)](#setShow-boolean-) | Získá nebo nastaví hodnotu určující, zda je základní prvek zobrazen. |
| [getZeroWidth()](#getZeroWidth--) | Získá nebo nastaví hodnotu určující, zda má být šířka základního prvku považována za nulu. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Získá nebo nastaví hodnotu určující, či má být šířka základního prvku považována za nulu. |
| [getZeroAsc()](#getZeroAsc--) | Získá nebo nastaví hodnotu určující, zda má být výška (ascent) základního prvku považována za nulu. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Získá nebo nastaví hodnotu určující, zda má být výška (ascent) základního prvku považována za nulu. |
| [getZeroDesc()](#getZeroDesc--) | Získá nebo nastaví hodnotu určující, zda má být hloubka (descent) základního prvku považována za nulu. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Získá nebo nastaví hodnotu určující, zda má být hloubka (descent) základního prvku považována za nulu. |
| [getTransp()](#getTransp--) | Získá nebo nastaví hodnotu určující, zda je fantom transparentní pro pravidla mezery založená na třídě. |
| [setTransp(boolean value)](#setTransp-boolean-) | Získá nebo nastaví hodnotu určující, zda je fantom transparentní pro pravidla mezery založená na třídě. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vlastnosti řídícího znaku |
| [getChildren()](#getChildren--) | Získá podřízené prvky |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```


Inicializuje novou instanci třídy [MathPhantom](../../com.aspose.slides/mathphantom) pomocí zadaného základního matematického prvku.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Základní [IMathElement](../../com.aspose.slides/imathelement), jehož viditelnost a rozložení bude řízeno fantomem. Tento prvek definuje obsah, který může být skryt nebo zobrazen, přičemž stále ovlivňuje geometrické zarovnání okolní matematiky.

--------------------

Fantomový prvek se používá k vyhrazení nebo potlačení vizuálního prostoru svého základního výrazu, aniž by jej nutně zobrazoval. Odpovídá elementu OMML <m:phant>. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Základní argument

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```


Získá nebo nastaví hodnotu určující, zda je základní prvek zobrazen.

--------------------

Když je false, základní prvek je skryt, ale může stále zabírat místo v závislosti na ostatních nastaveních fantomu. Odpovídá atributu OMML m:show.

**Vrací:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```


Získá nebo nastaví hodnotu určující, zda je základní prvek zobrazen.

--------------------

Když je false, základní prvek je skryt, ale může stále zabírat místo v závislosti na ostatních nastaveních fantomu. Odpovídá atributu OMML m:show.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```


Získá nebo nastaví hodnotu určující, zda má být šířka základního prvku považována za nulu.

--------------------

Když je true, fantom nevyhrazuje horizontální prostor pro svůj základ. Odpovídá atributu OMML m:zeroWid.

**Vrací:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```


Získá nebo nastaví hodnotu určující, zda má být šířka základního prvku považována za nulu.

--------------------

Když je true, fantom nevyhrazuje horizontální prostor pro svůj základ. Odpovídá atributu OMML m:zeroWid.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```


Získá nebo nastaví hodnotu určující, zda má být výška (ascent) základního prvku považována za nulu.

--------------------

Když je true, fantom nezvýší základní linii okolní matematické řádky. Odpovídá atributu OMML m:zeroAsc.

**Vrací:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```


Získá nebo nastaví hodnotu určující, zda má být výška (ascent) základního prvku považována za nulu.

--------------------

Když je true, fantom nezvýší základní linii okolní matematické řádky. Odpovídá atributu OMML m:zeroAsc.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```


Získá nebo nastaví hodnotu určující, zda má být hloubka (descent) základního prvku považována za nulu.

--------------------

Když je true, fantom nesníží základní linii okolní matematické řádky. Odpovídá atributu OMML m:zeroDesc.

**Vrací:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```


Získá nebo nastaví hodnotu určující, zda má být hloubka (descent) základního prvku považována za nulu.

--------------------

Když je true, fantom nesníží základní linii okolní matematické řádky. Odpovídá atributu OMML m:zeroDesc.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```


Získá nebo nastaví hodnotu určující, zda je fantom transparentní pro pravidla mezery založená na třídě.

--------------------

Když je true, operátory a symboly uvnitř fantomu stále ovlivňují matematické mezery kolem fantomu (jako by byly viditelné). Když je false, pravidla mezery založená na třídě jsou ignorována. Odpovídá atributu OMML m:transp.

**Vrací:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```


Získá nebo nastaví hodnotu určující, zda je fantom transparentní pro pravidla mezery založená na třídě.

--------------------

Když je true, operátory a symboly uvnitř fantomu stále ovlivňují matematické mezery kolem fantomu (jako by byly viditelné). Když je false, pravidla mezery založená na třídě jsou ignorována. Odpovídá atributu OMML m:transp.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Vlastnosti řídícího znaku

**Vrací:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Získá podřízené prvky

**Vrací:**
com.aspose.slides.IMathElement[]