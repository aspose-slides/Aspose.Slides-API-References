---
title: MathPhantom
second_title: Aspose.Slides pro Android prostřednictvím referenční dokumentace Java API
description: Representuje fiktivní matematický objekt ltmphantgt, který ovlivňuje rozvržení svého podřízeného prvku, aniž by jej nutně zobrazoval.
type: docs
url: /cs/com.aspose.slides/mathphantom/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Všechny implementované rozhraní:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

Reprezentuje fiktivní matematický objekt (<m:phant>), který ovlivňuje rozvržení svého podřízeného prvku, aniž by jej nutně zobrazoval. Fiktivní objekt může skrýt svůj základní výraz a přitom zachovat jeho šířku, výšku nebo hloubku pro zarovnání vzorců nebo rezervaci místa. Viditelnost a geometrické chování jsou řízeny vlastnostmi jako Show, ZeroWid, ZeroAsc, ZeroDesc a Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Skrýt obsah
>  phantom.setZeroWidth(false);     // Zachovat šířku
> ```
## Konstruktoři

| Konstruktor | Popis |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Inicializuje novou instanci třídy [MathPhantom](../../com.aspose.slides/mathphantom) pomocí specifikovaného základního matematického prvku. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getShow()](#getShow--) | Získá nebo nastaví hodnotu určující, zda je základní prvek zobrazen. |
| [setShow(boolean value)](#setShow-boolean-) | Získá nebo nastaví hodnotu určující, zda je základní prvek zobrazen. |
| [getZeroWidth()](#getZeroWidth--) | Získá nebo nastaví hodnotu určující, zda má být šířka základního prvku považována za nulu. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Získá nebo nastaví hodnotu určující, zda má být šířka základního prvku považována za nulu. |
| [getZeroAsc()](#getZeroAsc--) | Získá nebo nastaví hodnotu určující, zda má být vzestup (výška nad základní čárou) základního prvku považován za nulu. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Získá nebo nastaví hodnotu určující, zda má být vzestup (výška nad základní čárou) základního prvku považován za nulu. |
| [getZeroDesc()](#getZeroDesc--) | Získá nebo nastaví hodnotu určující, zda má být sestup (hloubka pod základní čárou) základního prvku považován za nulu. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Získá nebo nastaví hodnotu určující, zda má být sestup (hloubka pod základní čárou) základního prvku považován za nulu. |
| [getTransp()](#getTransp--) | Získá nebo nastaví hodnotu určující, zda je fiktivní objekt transparentní pro pravidla mezery založená na třídě. |
| [setTransp(boolean value)](#setTransp-boolean-) | Získá nebo nastaví hodnotu určující, zda je fiktivní objekt transparentní pro pravidla mezery založená na třídě. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vlastnosti řídících znaků |
| [getChildren()](#getChildren--) | Získat podřízené prvky |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```


Inicializuje novou instanci třídy [MathPhantom](../../com.aspose.slides/mathphantom) pomocí specifikovaného základního matematického prvku.

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
| element | [IMathElement](../../com.aspose.slides/imathelement) | Základní [IMathElement](../../com.aspose.slides/imathelement), jehož viditelnost a rozvržení bude řízeno fiktivním objektem. Tento prvek definuje obsah, který může být skryt nebo zobrazen, přičemž i nadále ovlivňuje geometrické zarovnání okolní matematiky.

--------------------

Fiktivní element se používá k rezervaci nebo potlačení vizuálního prostoru svého základního výrazu, aniž by jej nutně zobrazoval. Odpovídá elementu OMML <m:phant>. |

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

**Návratová hodnota:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```


Získá nebo nastaví hodnotu určující, zda je základní prvek zobrazen.

--------------------

Pokud je false, základní prvek je skryt, ale může stále zabírat místo v závislosti na dalších nastaveních fiktivního objektu. Odpovídá atributu OMML m:show.

**Návratová hodnota:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```


Získá nebo nastaví hodnotu určující, zda je základní prvek zobrazen.

--------------------

Pokud je false, základní prvek je skryt, ale může stále zabírat místo v závislosti na dalších nastaveních fiktivního objektu. Odpovídá atributu OMML m:show.

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

Když je true, fiktivní objekt nevyhrazuje vodorovný prostor pro svůj základ. Odpovídá atributu OMML m:zeroWid.

**Návratová hodnota:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```


Získá nebo nastaví hodnotu určující, zda má být šířka základního prvku považována za nulu.

--------------------

Když je true, fiktivní objekt nevyhrazuje vodorovný prostor pro svůj základ. Odpovídá atributu OMML m:zeroWid.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```


Získá nebo nastaví hodnotu určující, zda má být vzestup (výška nad základní čárou) základního prvku považován za nulu.

--------------------

Když je true, fiktivní objekt nezvedá základní čáru okolní řádky matematiky. Odpovídá atributu OMML m:zeroAsc.

**Návratová hodnota:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```


Získá nebo nastaví hodnotu určující, zda má být vzestup (výška nad základní čárou) základního prvku považován za nulu.

--------------------

Když je true, fiktivní objekt nezvedá základní čáru okolní řádky matematiky. Odpovídá atributu OMML m:zeroAsc.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```


Získá nebo nastaví hodnotu určující, zda má být sestup (hloubka pod základní čárou) základního prvku považován za nulu.

--------------------

Když je true, fiktivní objekt nesnižuje základní čáru okolní řádky matematiky. Odpovídá atributu OMML m:zeroDesc.

**Návratová hodnota:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```


Získá nebo nastaví hodnotu určující, zda má být sestup (hloubka pod základní čárou) základního prvku považován za nulu.

--------------------

Když je true, fiktivní objekt nesnižuje základní čáru okolní řádky matematiky. Odpovídá atributu OMML m:zeroDesc.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getTransp() {#getTransp--}
```
public final boolean getTransp()
```


Získá nebo nastaví hodnotu určující, zda je fiktivní objekt transparentní pro pravidla mezery založená na třídě.

--------------------

Když je true, operátory a symboly uvnitř fiktivního objektu stále ovlivňují matematické mezery kolem něj (jako by byl viditelný). Když je false, pravidla mezery založená na třídě jsou ignorována. Odpovídá atributu OMML m:transp.

**Návratová hodnota:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```


Získá nebo nastaví hodnotu určující, zda je fiktivní objekt transparentní pro pravidla mezery založená na třídě.

--------------------

Když je true, operátory a symboly uvnitř fiktivního objektu stále ovlivňují matematické mezery kolem něj (jako by byl viditelný). Když je false, pravidla mezery založená na třídě jsou ignorována. Odpovídá atributu OMML m:transp.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Vlastnosti řídících znaků

**Návratová hodnota:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Získat podřízené prvky

**Návratová hodnota:**
com.aspose.slides.IMathElement[]