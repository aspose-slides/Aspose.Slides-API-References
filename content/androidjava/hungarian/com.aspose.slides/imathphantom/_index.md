---
title: IMathPhantom
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Egy fantom matematikai objektumot (ltmphantgt) reprezentál, amely befolyásolja a gyermekeleme elrendezését anélkül, hogy feltétlenül megjelenítené azt.
type: docs
url: /hu/com.aspose.slides/imathphantom/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Egy fantom matematikai objektumot (<m:phant>) reprezentál, amely befolyásolja a gyermekeleme elrendezését anélkül, hogy feltétlenül megjelenítené azt. A fantom elrejtheti az alapkifejezést, miközben megőrzi a szélességét, magasságát vagy mélységét a képletek igazításához vagy hely lefoglalásához. A láthatóságot és a geometriai viselkedést a Show, ZeroWid, ZeroAsc, ZeroDesc és Transp tulajdonságok szabályozzák.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // A tartalom elrejtése
>  phantom.setZeroWidth(false);     // A szélesség megtartása
```
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getShow()](#getShow--) | Értéket kap vagy állít be, amely meghatározza, hogy az alapelem megjelenik-e. |
| [setShow(boolean value)](#setShow-boolean-) | Értéket kap vagy állít be, amely meghatározza, hogy az alapelem megjelenik-e. |
| [getZeroWidth()](#getZeroWidth--) | Értéket kap vagy állít be, amely meghatározza, hogy az alapelem szélességét nullának kell-e tekinteni. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Értéket kap vagy állít be, amely meghatározza, hogy az alapelem szélességét nullának kell-e tekinteni. |
| [getZeroAsc()](#getZeroAsc--) | Értéket kap vagy állít be, amely meghatározza, hogy az alapelem emelkedését (alapvonal feletti magasság) nullának kell-e tekinteni. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Értéket kap vagy állít be, amely meghatározza, hogy az alapelem emelkedését (alapvonal feletti magasság) nullának kell-e tekinteni. |
| [getZeroDesc()](#getZeroDesc--) | Értéket kap vagy állít be, amely meghatározza, hogy az alapelem süllyedését (alapvonal alatti mélység) nullának kell-e tekinteni. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Értéket kap vagy állít be, amely meghatározza, hogy az alapelem süllyedését (alapvonal alatti mélység) nullának kell-e tekinteni. |
| [getTransp()](#getTransp--) | Értéket kap vagy állít be, amely meghatározza, hogy a fantom átlátszó-e az osztályalapú távolságszabályok számára. |
| [setTransp(boolean value)](#setTransp-boolean-) | Értéket kap vagy állít be, amely meghatározza, hogy a fantom átlátszó-e az osztályalapú távolságszabályok számára. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Alap argumentum

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```

Értéket kap vagy állít be, amely meghatározza, hogy az alapelem megjelenik-e.

--------------------

Amikor hamis, az alapelem rejtve van, de a többi fantombeállítástól függően továbbra is foglalhat helyet. Az OMML attribútum m:show-nak felel meg.

**Visszatér:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

Értéket kap vagy állít be, amely meghatározza, hogy az alapelem megjelenik-e.

--------------------

Amikor hamis, az alapelem rejtve van, de a többi fantombeállítástól függően továbbra is foglalhat helyet. Az OMML attribútum m:show-nak felel meg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

Értéket kap vagy állít be, amely meghatározza, hogy az alapelem szélességét nullának kell-e tekinteni.

--------------------

Amikor igaz, a fantom nem foglal vízszintes helyet az alapelemnek. Az OMML attribútum m:zeroWid-nek felel meg.

**Visszatér:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

Értéket kap vagy állít be, amely meghatározza, hogy az alapelem szélességét nullának kell-e tekinteni.

--------------------

Amikor igaz, a fantom nem foglal vízszintes helyet az alapelemnek. Az OMML attribútum m:zeroWid-nek felel meg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

Értéket kap vagy állít be, amely meghatározza, hogy az alapelem emelkedését (alapvonal feletti magasság) nullának kell-e tekinteni.

--------------------

Amikor igaz, a fantom nem emeli meg a körülötte lévő matematikai sor alapvonalát. Az OMML attribútum m:zeroAsc-nek felel meg.

**Visszatér:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

Értéket kap vagy állít be, amely meghatározza, hogy az alapelem emelkedését (alapvonal feletti magasság) nullának kell-e tekinteni.

--------------------

Amikor igaz, a fantom nem emeli meg a körülötte lévő matematikai sor alapvonalát. Az OMML attribútum m:zeroAsc-nek felel meg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

Értéket kap vagy állít be, amely meghatározza, hogy az alapelem süllyedését (alapvonal alatti mélység) nullának kell-e tekinteni.

--------------------

Amikor igaz, a fantom nem süllyeszti le a körülötte lévő matematikai sor alapvonalát. Az OMML attribútum m:zeroDesc-nek felel meg.

**Visszatér:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

Értéket kap vagy állít be, amely meghatározza, hogy az alapelem süllyedését (alapvonal alatti mélység) nullának kell-e tekinteni.

--------------------

Amikor igaz, a fantom nem süllyeszti le a körülötte lévő matematikai sor alapvonalát. Az OMML attribútum m:zeroDesc-nek felel meg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

Értéket kap vagy állít be, amely meghatározza, hogy a fantom átlátszó-e az osztályalapú távolságszabályok számára.

--------------------

Amikor igaz, a fantomon belüli operátorok és szimbólumok továbbra is befolyásolják a környező matematikai távolságot (mintha láthatóak lennének). Hamis esetén az osztályalapú távolságot figyelmen kívül hagyja. Az OMML attribútum m:transp-nek felel meg.

**Visszatér:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

Értéket kap vagy állít be, amely meghatározza, hogy a fantom átlátszó-e az osztályalapú távolságszabályok számára.

--------------------

Amikor igaz, a fantomon belüli operátorok és szimbólumok továbbra is befolyásolják a környező matematikai távolságot (mintha láthatóak lennének). Hamis esetén az osztályalapú távolságot figyelmen kívül hagyja. Az OMML attribútum m:transp-nek felel meg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |