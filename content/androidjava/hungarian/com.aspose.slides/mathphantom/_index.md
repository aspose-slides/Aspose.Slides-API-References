---
title: MathPhantom
second_title: Aspose.Slides Androidra Java API hivatkozás
description: Egy fantom matematikai objektumot ltmphantgt, amely befolyásolja a gyermekeleme elrendezését anélkül, hogy kötelezően megjelenítené azt.
type: docs
url: /hu/com.aspose.slides/mathphantom/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Minden megvalósított interfész:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

Egy fantom matematikai objektum (<m:phant>) ábrázol, amely befolyásolja a gyermekeleme elrendezését anélkül, hogy kötelezően megjelenítené azt. A fantom elrejtheti az alapkifejezést, miközben megőrzi a szélességét, magasságát vagy mélységét a képletek igazításához vagy hely lefoglalásához. A láthatóságot és a geometriai viselkedést olyan tulajdonságok szabályozzák, mint a Show, ZeroWid, ZeroAsc, ZeroDesc és a Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // A tartalom elrejtése
>  phantom.setZeroWidth(false);     // A szélesség megtartása
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Új példányt hoz létre a(z) [MathPhantom](../../com.aspose.slides/mathphantom) osztályból a megadott alap matematikai elemmel. |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getShow()](#getShow--) | Értéket ad vissza vagy állít be, amely azt jelzi, hogy az alap elem megjelenik-e. |
| [setShow(boolean value)](#setShow-boolean-) | Értéket ad vissza vagy állít be, amely azt jelzi, hogy az alap elem megjelenik-e. |
| [getZeroWidth()](#getZeroWidth--) | Értéket ad vissza vagy állít be, amely azt jelzi, hogy az alap elem szélességét nullaként kell kezelni. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Értéket ad vissza vagy állít be, amely azt jelzi, hogy az alap elem szélességét nullaként kell kezelni. |
| [getZeroAsc()](#getZeroAsc--) | Értéket ad vissza vagy állít be, amely azt jelzi, hogy az alap elem emelkedése (a vonal fölötti magasság) nullaként kell kezelni. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Értéket ad vissza vagy állít be, amely azt jelzi, hogy az alap elem emelkedése (a vonal fölötti magasság) nullaként kell kezelni. |
| [getZeroDesc()](#getZeroDesc--) | Értéket ad vissza vagy állít be, amely azt jelzi, hogy az alap elem leereszkedése (a vonal alatti mélység) nullaként kell kezelni. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Értéket ad vissza vagy állít be, amely azt jelzi, hogy az alap elem leereszkedése (a vonal alatti mélység) nullaként kell kezelni. |
| [getTransp()](#getTransp--) | Értéket ad vissza vagy állít be, amely azt jelzi, hogy a fantom átlátszó-e az osztályalapú szóközszabályok számára. |
| [setTransp(boolean value)](#setTransp-boolean-) | Értéket ad vissza vagy állít be, amely azt jelzi, hogy a fantom átlátszó-e az osztályalapú szóközszabályok számára. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontroll karakter tulajdonságok |
| [getChildren()](#getChildren--) | Gyermek elemek lekérése |

### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

Új példányt hoz létre a(z) [MathPhantom](../../com.aspose.slides/mathphantom) osztályból a megadott alap matematikai elemmel.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | A base [IMathElement](../../com.aspose.slides/imathelement), amelynek láthatóságát és elrendezését a fantom szabályozza. Ez az elem meghatározza a tartalmat, amely elrejthető vagy megjeleníthető, miközben továbbra is befolyásolja a környező matematika geometriai igazítását. |

A fantom elemet arra használják, hogy lefoglalja vagy elnyomja a base kifejezés vizuális helyét anélkül, hogy kötelezően megjelenítenék azt. Az OMML <m:phant> elemnek felel meg. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Alap argumentum

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```

Értéket ad vissza vagy állít be, amely azt jelzi, hogy az alap elem megjelenik-e.

Amikor hamis, az alap elem rejtett, de a többi fantom beállítástól függően továbbra is elfoglalhat helyet. Az OMML m:show attribútumának felel meg.

**Visszatérési érték:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

Értéket ad vissza vagy állít be, amely azt jelzi, hogy az alap elem megjelenik-e.

Amikor hamis, az alap elem rejtett, de a többi fantom beállítástól függően továbbra is elfoglalhat helyet. Az OMML m:show attribútumának felel meg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

Értéket ad vissza vagy állít be, amely azt jelzi, hogy az alap elem szélességét nullaként kell kezelni.

Amikor igaz, a fantom nem foglal helyet a vízszintes térben az alap számára. Az OMML m:zeroWid attribútumának felel meg.

**Visszatérési érték:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

Értéket ad vissza vagy állít be, amely azt jelzi, hogy az alap elem szélességét nullaként kell kezelni.

Amikor igaz, a fantom nem foglal helyet a vízszintes térben az alap számára. Az OMML m:zeroWid attribútumának felel meg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

Értéket ad vissza vagy állít be, amely azt jelzi, hogy az alap elem emelkedése (a vonal fölötti magasság) nullaként kell kezelni.

Amikor igaz, a fantom nem emeli a környező matematikai sor alapvonalát. Az OMML m:zeroAsc attribútumának felel meg.

**Visszatérési érték:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

Értéket ad vissza vagy állít be, amely azt jelzi, hogy az alap elem emelkedése (a vonal fölötti magasság) nullaként kell kezelni.

Amikor igaz, a fantom nem emeli a környező matematikai sor alapvonalát. Az OMML m:zeroAsc attribútumának felel meg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

Értéket ad vissza vagy állít be, amely azt jelzi, hogy az alap elem leereszkedése (a vonal alatti mélység) nullaként kell kezelni.

Amikor igaz, a fantom nem süllyeszti le a környező matematikai sor alapvonalát. Az OMML m:zeroDesc attribútumának felel meg.

**Visszatérési érték:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

Értéket ad vissza vagy állít be, amely azt jelzi, hogy az alap elem leereszkedése (a vonal alatti mélység) nullaként kell kezelni.

Amikor igaz, a fantom nem süllyeszti le a környező matematikai sor alapvonalát. Az OMML m:zeroDesc attribútumának felel meg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

Értéket ad vissza vagy állít be, amely azt jelzi, hogy a fantom átlátszó-e az osztályalapú szóközszabályok számára.

Amikor igaz, a fantomon belüli operátorok és szimbólumok továbbra is befolyásolják a matematikai szóközöket (mintha láthatóak lennének). Hamis esetén az osztályalapú szóköz figyelmen kívül marad. Az OMML m:transp attribútumának felel meg.

**Visszatérési érték:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

Értéket ad vissza vagy állít be, amely azt jelzi, hogy a fantom átlátszó-e az osztályalapú szóközszabályok számára.

Amikor igaz, a fantomon belüli operátorok és szimbólumok továbbra is befolyásolják a matematikai szóközöket (mintha láthatóak lennének). Hamis esetén az osztályalapú szóköz figyelmen kívül marad. Az OMML m:transp attribútumának felel meg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Kontroll karakter tulajdonságok

**Visszatérési érték:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Gyermek elemek lekérése

**Visszatérési érték:**
com.aspose.slides.IMathElement[]