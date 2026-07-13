---
title: IMathPhantom
second_title: Aspose.Slides pro Android - reference Java API
description: Representuje phantomský matematický objekt ltmphantgt, který ovlivňuje rozložení svého podřízeného prvku, aniž by jej nutně zobrazoval.
type: docs
url: /cs/com.aspose.slides/imathphantom/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Representuje phantomský matematický objekt (<m:phant>), který ovlivňuje rozložení svého podřízeného prvku, aniž by jej nutně zobrazoval. Phantoms může skrýt svůj základní výraz a přitom zachovat jeho šířku, výšku nebo hloubku pro zarovnání vzorců nebo rezervaci místa. Viditelnost a geometrické chování jsou řízeny vlastnostmi jako Show, ZeroWid, ZeroAsc, ZeroDesc a Transp.

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
| [getShow()](#getShow--) | Získá nebo nastaví hodnotu určující, zda je základní prvek zobrazen. |
| [setShow(boolean value)](#setShow-boolean-) | Získá nebo nastaví hodnotu určující, zda je základní prvek zobrazen. |
| [getZeroWidth()](#getZeroWidth--) | Získá nebo nastaví hodnotu určující, zda má být šířka základního prvku považována za nulu. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Získá nebo nastaví hodnotu určující, zda má být šířka základního prvku považována za nulu. |
| [getZeroAsc()](#getZeroAsc--) | Získá nebo nastaví hodnotu určující, zda má být výška (ascent) základního prvku považována za nulu. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Získá nebo nastaví hodnotu určující, zda má být výška (ascent) základního prvku považována za nulu. |
| [getZeroDesc()](#getZeroDesc--) | Získá nebo nastaví hodnotu určující, zda má být hloubka (descent) základního prvku považována za nulu. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Získá nebo nastaví hodnotu určující, zda má být hloubka (descent) základního prvku považována za nulu. |
| [getTransp()](#getTransp--) | Získá nebo nastaví hodnotu určující, zda je phantoms transparentní pro pravidla mezery založená na třídách. |
| [setTransp(boolean value)](#setTransp-boolean-) | Získá nebo nastaví hodnotu určující, zda je phantoms transparentní pro pravidla mezery založená na třídách. |
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
> ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```

Získá nebo nastaví hodnotu určující, zda je základní prvek zobrazen.

--------------------

Když je nastaveno na false, základní prvek je skryt, ale může stále zabírat místo v závislosti na dalších nastaveních phantomů. Odpovídá atributu OMML m:show.

**Vrací:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

Získá nebo nastaví hodnotu určující, zda je základní prvek zobrazen.

--------------------

Když je nastaveno na false, základní prvek je skryt, ale může stále zabírat místo v závislosti na dalších nastaveních phantomů. Odpovídá atributu OMML m:show.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

Získá nebo nastaví hodnotu určující, zda má být šířka základního prvku považována za nulu.

--------------------

Když je true, phantoms nevyhrazuje vodorovný prostor pro svůj základ. Odpovídá atributu OMML m:zeroWid.

**Vrací:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

Získá nebo nastaví hodnotu určující, zda má být šířka základního prvku považována za nulu.

--------------------

Když je true, phantoms nevyhrazuje vodorovný prostor pro svůj základ. Odpovídá atributu OMML m:zeroWid.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

Získá nebo nastaví hodnotu určující, zda má být výška (ascent) základního prvku považována za nulu.

--------------------

Když je true, phantoms nezvedá základní čáru okolní matematické řádky. Odpovídá atributu OMML m:zeroAsc.

**Vrací:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

Získá nebo nastaví hodnotu určující, zda má být výška (ascent) základního prvku považována za nulu.

--------------------

Když je true, phantoms nezvedá základní čáru okolní matematické řádky. Odpovídá atributu OMML m:zeroAsc.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

Získá nebo nastaví hodnotu určující, zda má být hloubka (descent) základního prvku považována za nulu.

--------------------

Když je true, phantoms nesnižuje základní čáru okolní matematické řádky. Odpovídá atributu OMML m:zeroDesc.

**Vrací:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

Získá nebo nastaví hodnotu určující, zda má být hloubka (descent) základního prvku považována za nulu.

--------------------

Když je true, phantoms nesnižuje základní čáru okolní matematické řádky. Odpovídá atributu OMML m:zeroDesc.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

Získá nebo nastaví hodnotu určující, zda je phantoms transparentní pro pravidla mezery založená na třídách.

--------------------

Když je true, operátory a symboly uvnitř phantomů stále ovlivňují matematické mezery kolem phantomů (jako by byly viditelné). Když je false, pravidla mezery založená na třídách jsou ignorována. Odpovídá atributu OMML m:transp.

**Vrací:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

Získá nebo nastaví hodnotu určující, zda je phantoms transparentní pro pravidla mezery založená na třídách.

--------------------

Když je true, operátory a symboly uvnitř phantomů stále ovlivňují matematické mezery kolem phantomů (jako by byly viditelné). Když je false, pravidla mezery založená na třídách jsou ignorována. Odpovídá atributu OMML m:transp.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |