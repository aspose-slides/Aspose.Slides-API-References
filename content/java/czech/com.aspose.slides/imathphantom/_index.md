---
title: IMathPhantom
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje fiktivní matematický objekt ltmphantgt, který ovlivňuje rozvržení svého podřízeného prvku, aniž by jej nutně zobrazoval.
type: docs
url: /cs/com.aspose.slides/imathphantom/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Zastupuje fantomový matematický objekt (<m:phant>), který ovlivňuje rozložení svého potomka, aniž by jej nutně zobrazoval. Fantom může skrýt svůj základní výraz a přitom zachovat jeho šířku, výšku nebo hloubku pro zarovnání vzorců nebo rezervaci místa. Viditelnost a geometrické chování jsou řízeny vlastnostmi jako Show, ZeroWid, ZeroAsc, ZeroDesc a Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Skrýt obsah
>  phantom.setZeroWidth(false);     // Zachovat šířku
>  ```
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Základní argument |
| [getShow()](#getShow--) | Získá nebo nastaví hodnotu, která určuje, zda je základní prvek zobrazen. |
| [setShow(boolean value)](#setShow-boolean-) | Získá nebo nastaví hodnotu, která určuje, či je základní prvek zobrazen. |
| [getZeroWidth()](#getZeroWidth--) | Získá nebo nastaví hodnotu, která určuje, zda má být šířka základního prvku považována za nulu. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Získá nebo nastaví hodnotu, která určuje, zda má být šířka základního prvku považována za nulu. |
| [getZeroAsc()](#getZeroAsc--) | Získá nebo nastaví hodnotu, která určuje, zda má být vzestup (výška nad základní čárou) základního prvku považován za nulu. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Získá nebo nastaví hodnotu, která určuje, zda má být vzestup (výška nad základní čárou) základního prvku považován za nulu. |
| [getZeroDesc()](#getZeroDesc--) | Získá nebo nastaví hodnotu, která určuje, zda má být sestup (hloubka pod základní čárou) základního prvku považován za nulu. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Získá nebo nastaví hodnotu, která určuje, zda má být sestup (hloubka pod základní čárou) základního prvku považován za nulu. |
| [getTransp()](#getTransp--) | Získá nebo nastaví hodnotu, která určuje, zda je fantom průhledný pro pravidla mezery založená na třídě. |
| [setTransp(boolean value)](#setTransp-boolean-) | Získá nebo nastaví hodnotu, která určuje, zda je fantom průhledný pro pravidla mezery založená na třídě. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Základní argument

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
>  ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```

Získá nebo nastaví hodnotu, která určuje, zda je základní prvek zobrazen.

--------------------

Když je false, základní prvek je skrytý, ale může stále zabírat místo v závislosti na dalších nastaveních fantomu. Odpovídá atributu OMML m:show.

**Vrací:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

Získá nebo nastaví hodnotu, která určuje, zda je základní prvek zobrazen.

--------------------

Když je false, základní prvek je skrytý, ale může stále zabírat místo v závislosti na dalších nastaveních fantomu. Odpovídá atributu OMML m:show.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

Získá nebo nastaví hodnotu, která určuje, zda má být šířka základního prvku považována za nulu.

--------------------

Když je true, fantom nevyhrazuje vodorovný prostor pro svůj základ. Odpovídá atributu OMML m:zeroWid.

**Vrací:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

Získá nebo nastaví hodnotu, která určuje, zda má být šířka základního prvku považována za nulu.

--------------------

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

Získá nebo nastaví hodnotu, která určuje, zda má být vzestup (výška nad základní čárou) základního prvku považován za nulu.

--------------------

Když je true, fantom nezvedá základní čáru okolní matematické řádky. Odpovídá atributu OMML m:zeroAsc.

**Vrací:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

Získá nebo nastaví hodnotu, která určuje, zda má být vzestup (výška nad základní čárou) základního prvku považován za nulu.

--------------------

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

Získá nebo nastaví hodnotu, která určuje, zda má být sestup (hloubka pod základní čárou) základního prvku považován za nulu.

--------------------

Když je true, fantom nesnižuje základní čáru okolní matematické řádky. Odpovídá atributu OMML m:zeroDesc.

**Vrací:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

Získá nebo nastaví hodnotu, která určuje, zda má být sestup (hloubka pod základní čárou) základního prvku považován za nulu.

--------------------

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

Získá nebo nastaví hodnotu, která určuje, zda je fantom průhledný pro pravidla mezery založená na třídě.

--------------------

Když je true, operátory a symboly uvnitř fantomu stále ovlivňují matematické mezery kolem fantomu (jako by byl viditelný). Když je false, mezery založené na třídě jsou ignorovány. Odpovídá atributu OMML m:transp.

**Vrací:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

Získá nebo nastaví hodnotu, která určuje, zda je fantom průhledný pro pravidla mezery založená na třídě.

--------------------

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |