---
title: MathPhantom
second_title: Aspose.Slides für Java API-Referenz
description: Stellt ein Phantom-Mathe-Objekt ltmphantgt dar, das das Layout seines Kindelements beeinflusst, ohne es unbedingt anzuzeigen.
type: docs
url: /de/com.aspose.slides/mathphantom/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

Stellt ein Phantom-Mathe-Objekt (<m:phant>) dar, das das Layout seines Kindelements beeinflusst, ohne es unbedingt anzuzeigen. Ein Phantom kann seinen Basisausdruck verbergen, während es Breite, Höhe oder Tiefe beibehält, um Formeln auszurichten oder Platz zu reservieren. Sichtbarkeit und geometrisches Verhalten werden durch Eigenschaften wie Show, ZeroWid, ZeroAsc, ZeroDesc und Transp gesteuert.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Versteckt den Inhalt
>  phantom.setZeroWidth(false);     // Behalte die Breite
```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Initialisiert eine neue Instanz der [MathPhantom](../../com.aspose.slides/mathphantom) Klasse mit dem angegebenen Basismathematik-Element. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getShow()](#getShow--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob das Basiselement angezeigt wird. |
| [setShow(boolean value)](#setShow-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob das Basiselement angezeigt wird. |
| [getZeroWidth()](#getZeroWidth--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob die Breite des Basiselements als null behandelt werden soll. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob die Breite des Basiselements als null behandelt werden soll. |
| [getZeroAsc()](#getZeroAsc--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob der Aufstieg (Höhe über der Grundlinie) des Basiselements als null behandelt werden soll. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob der Aufstieg (Höhe über der Grundlinie) des Basiselements als null behandelt werden soll. |
| [getZeroDesc()](#getZeroDesc--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob der Abstieg (Tiefe unter der Grundlinie) des Basiselements als null behandelt werden soll. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob der Abstieg (Tiefe unter der Grundlinie) des Basiselements als null behandelt werden soll. |
| [getTransp()](#getTransp--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob das Phantom für klassenbasierte Abstandsregeln transparent ist. |
| [setTransp(boolean value)](#setTransp-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob das Phantom für klassenbasierte Abstandsregeln transparent ist. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Steuerzeichen-Eigenschaften |
| [getChildren()](#getChildren--) | Gibt Kindelemente zurück |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

Initialisiert eine neue Instanz der [MathPhantom](../../com.aspose.slides/mathphantom) Klasse mit dem angegebenen Basismathematik-Element.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Das Basis-[IMathElement](../../com.aspose.slides/imathelement), dessen Sichtbarkeit und Layout vom Phantom gesteuert werden. Dieses Element definiert den Inhalt, der ausgeblendet oder angezeigt werden kann, während es dennoch die geometrische Ausrichtung der umgebenden Mathematik beeinflusst. |

Das Phantom-Element wird verwendet, um den visuellen Raum seines Basisausdrucks zu reservieren oder zu unterdrücken, ohne ihn unbedingt anzuzeigen. Es entspricht dem OMML-Element <m:phant>.

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Basisargument

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```

Ruft einen Wert ab oder legt ihn fest, der angibt, ob das Basiselement angezeigt wird.

--------------------

Wenn false, ist das Basiselement ausgeblendet, kann aber je nach anderen Phantom-Einstellungen weiterhin Raum einnehmen. Entspricht dem OMML-Attribut m:show.

**Rückgabewert:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

Ruft einen Wert ab oder legt ihn fest, der angibt, ob das Basiselement angezeigt wird.

--------------------

Wenn false, ist das Basiselement ausgeblendet, kann aber je nach anderen Phantom-Einstellungen weiterhin Raum einnehmen. Entspricht dem OMML-Attribut m:show.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

Ruft einen Wert ab oder legt ihn fest, der angibt, ob die Breite des Basiselements als null behandelt werden soll.

--------------------

Wenn true, reserviert das Phantom keinen horizontalen Raum für seine Basis. Entspricht dem OMML-Attribut m:zeroWid.

**Rückgabewert:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

Ruft einen Wert ab oder legt ihn fest, der angibt, ob die Breite des Basiselements als null behandelt werden soll.

--------------------

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

Ruft einen Wert ab oder legt ihn fest, der angibt, ob der Aufstieg (Höhe über der Grundlinie) des Basiselements als null behandelt werden soll.

--------------------

Wenn true, hebt das Phantom die Grundlinie der umgebenden mathematischen Zeile nicht an. Entspricht dem OMML-Attribut m:zeroAsc.

**Rückgabewert:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

Ruft einen Wert ab oder legt ihn fest, der angibt, ob der Aufstieg (Höhe über der Grundlinie) des Basiselements als null behandelt werden soll.

--------------------

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

Ruft einen Wert ab oder legt ihn fest, der angibt, ob der Abstieg (Tiefe unter der Grundlinie) des Basiselements als null behandelt werden soll.

--------------------

Wenn true, senkt das Phantom die Grundlinie der umgebenden mathematischen Zeile nicht ab. Entspricht dem OMML-Attribut m:zeroDesc.

**Rückgabewert:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

Ruft einen Wert ab oder legt ihn fest, der angibt, ob der Abstieg (Tiefe unter der Grundlinie) des Basiselements als null behandelt werden soll.

--------------------

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

Ruft einen Wert ab oder legt ihn fest, der angibt, ob das Phantom für klassenbasierte Abstandsregeln transparent ist.

--------------------

Wenn true, beeinflussen Operatoren und Symbole im Phantom weiterhin den mathematischen Abstand um das Phantom herum (wie wenn es sichtbar wäre). Wenn false, werden klassenbasierte Abstände ignoriert. Entspricht dem OMML-Attribut m:transp.

**Rückgabewert:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

Ruft einen Wert ab oder legt ihn fest, der angibt, ob das Phantom für klassenbasierte Abstandsregeln transparent ist.

--------------------

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Steuerzeichen-Eigenschaften

**Rückgabewert:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Gibt Kindelemente zurück

**Rückgabewert:**
com.aspose.slides.IMathElement[]