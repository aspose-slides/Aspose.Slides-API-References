---
title: MathPhantom
second_title: Aspose.Slides a Java API hivatkozása
description: Egy fantom matematikai objektumot (<m:phant>) reprezentál, amely befolyásolja a gyermekeleme elrendezését anélkül, hogy szükségszerűen megjelenítené azt.
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

Egy fantom matematikai objektumot (<m:phant>) reprezentál, amely befolyásolja a gyermekeleme elrendezését anélkül, hogy szükségszerűen megjelenítené azt. A fantom elrejtheti az alapkifejezését, miközben megőrzi a szélességét, magasságát vagy mélységét a képletek igazításához vagy hely lefoglalásához. A láthatóságot és a geometriai viselkedést olyan tulajdonságok szabályozzák, mint a Show, ZeroWid, ZeroAsc, ZeroDesc és a Transp.

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
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Új példányt hoz létre a [MathPhantom](../../com.aspose.slides/mathphantom) osztályból a megadott alap matematikai elemmel. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getShow()](#getShow--) | Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy az alap elem megjelenik-e. |
| [setShow(boolean value)](#setShow-boolean-) | Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy az alap elem megjelenik-e. |
| [getZeroWidth()](#getZeroWidth--) | Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy az alap elem szélességét nullának kell tekinteni. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy az alap elem szélességét nullának kell tekinteni. |
| [getZeroAsc()](#getZeroAsc--) | Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy az alap elem felemelkedése (a baseline fölötti magasság) nullának kell tekinteni. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy az alap elem felemelkedése (a baseline fölötti magasság) nullának kell tekinteni. |
| [getZeroDesc()](#getZeroDesc--) | Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy az alap elem süllyedése (a baseline alatti mélység) nullának kell tekinteni. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy az alap elem süllyedése (a baseline alatti mélység) nullának kell tekinteni. |
| [getTransp()](#getTransp--) | Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy a fantom átlátszó-e az osztályalapú szóközszabályoknál. |
| [setTransp(boolean value)](#setTransp-boolean-) | Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy a fantom átlátszó-e az osztályalapú szóközszabályoknál. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vezérlőkarakter tulajdonságok |
| [getChildren()](#getChildren--) | Gyermek elemek lekérése |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

Új példányt hoz létre a [MathPhantom](../../com.aspose.slides/mathphantom) osztályból a megadott alap matematikai elemmel.

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
| element | [IMathElement](../../com.aspose.slides/imathelement) | Az alap [IMathElement](../../com.aspose.slides/imathelement), amelynek láthatóságát és elrendezését a fantom szabályozza. Ez az elem határozza meg a tartalmat, amely elrejthető vagy megjeleníthető, miközben továbbra is befolyásolja a környező matematikai elemek geometriai igazítását. |

A fantom elem arra szolgál, hogy lefoglalja vagy elnyomja az alap kifejezés vizuális helyét anélkül, hogy szükségszerűen megjelenítené azt. Ennek megfelelője az OMML <m:phant> elem.

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

Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy az alap elem megjelenik-e.

--------------------

Amikor hamis, az alap elem rejtve marad, de a többi fantom beállítástól függően még mindig elfoglalhat helyet. Az OMML attribútumnak megfelelően m:show.

**Visszatérési érték:** boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy az alap elem megjelenik-e.

--------------------

Amikor hamis, az alap elem rejtve marad, de a többi fantom beállítástól függően még mindig elfoglalhat helyet. Az OMML attribútumnak megfelelően m:show.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy az alap elem szélességét nullának kell tekinteni.

--------------------

Amikor igaz, a fantom nem foglal helyet vízszintesen az alap számára. Az OMML attribútumnak megfelelően m:zeroWid.

**Visszatérési érték:** boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy az alap elem szélességét nullának kell tekinteni.

--------------------

Amikor igaz, a fantom nem foglal helyet vízszintesen az alap számára. Az OMML attribútumnak megfelelően m:zeroWid.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy az alap elem felemelkedése (a baseline fölötti magasság) nullának kell tekinteni.

--------------------

Amikor igaz, a fantom nem emeli meg a környező matematikai sor baseline-ját. Az OMML attribútumnak megfelelően m:zeroAsc.

**Visszatérési érték:** boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy az alap elem felemelkedése (a baseline fölötti magasság) nullának kell tekinteni.

--------------------

Amikor igaz, a fantom nem emeli meg a környező matematikai sor baseline-ját. Az OMML attribútumnak megfelelően m:zeroAsc.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy az alap elem süllyedése (a baseline alatti mélység) nullának kell tekinteni.

--------------------

Amikor igaz, a fantom nem csökkenti le a környező matematikai sor baseline-ját. Az OMML attribútumnak megfelelően m:zeroDesc.

**Visszatérési érték:** boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy az alap elem süllyedése (a baseline alatti mélység) nullának kell tekinteni.

--------------------

Amikor igaz, a fantom nem csökkenti le a környező matematikai sor baseline-ját. Az OMML attribútumnak megfelelően m:zeroDesc.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy a fantom átlátszó-e az osztályalapú szóközszabályoknál.

--------------------

Amikor igaz, a fantomon belül lévő operátorok és szimbólumok továbbra is befolyásolják a matematikai szóközöket körülötte (mintha láthatóak lennének). Hamis esetén az osztályalapú szóközök figyelmen kívül maradnak. Az OMML attribútumnak megfelelően m:transp.

**Visszatérési érték:** boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy a fantom átlátszó-e az osztályalapú szóközszabályoknál.

--------------------

Amikor igaz, a fantomon belül lévő operátorok és szimbólumok továbbra is befolyásolják a matematikai szóközöket körülötte (mintha láthatóak lennének). Hamis esetén az osztályalapú szóközök figyelmen kívül maradnak. Az OMML attribútumnak megfelelően m:transp.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Vezérlőkarakter tulajdonságok

**Visszatérési érték:** com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Gyermek elemek lekérése

**Visszatérési érték:** com.aspose.slides.IMathElement[]