---
title: IMathPhantom
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt ein Phantom-Mathe-Objekt ltmphantgt dar, das das Layout seines Kind-Elements beeinflusst, ohne es zwingend anzuzeigen.
type: docs
url: /de/com.aspose.slides/imathphantom/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Stellt ein Phantom-Mathe-Objekt (<m:phant>) dar, das das Layout seines Kind-Elements beeinflusst, ohne es zwingend anzuzeigen. Ein Phantom kann seinen Basisausdruck verbergen, während es Breite, Höhe oder Tiefe beibehält, um Formeln auszurichten oder Platz zu reservieren. Sichtbarkeits- und Geometriesteuerung werden durch Eigenschaften wie Show, ZeroWid, ZeroAsc, ZeroDesc und Transp kontrolliert.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Inhalt verbergen
>  phantom.setZeroWidth(false);     // Breite beibehalten
```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getShow()](#getShow--) | Liest oder setzt einen Wert, der angibt, ob das Basiselement angezeigt wird. |
| [setShow(boolean value)](#setShow-boolean-) | Liest oder setzt einen Wert, der angibt, ob das Basiselement angezeigt wird. |
| [getZeroWidth()](#getZeroWidth--) | Liest oder setzt einen Wert, der angibt, ob die Breite des Basiselements als Null behandelt werden soll. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Liest oder setzt einen Wert, der angibt, ob die Breite des Basiselements als Null behandelt werden soll. |
| [getZeroAsc()](#getZeroAsc--) | Liest oder setzt einen Wert, der angibt, ob der Aufstieg (Höhe über der Grundlinie) des Basiselements als Null behandelt werden soll. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Liest oder setzt einen Wert, der angibt, ob der Aufstieg (Höhe über der Grundlinie) des Basiselements als Null behandelt werden soll. |
| [getZeroDesc()](#getZeroDesc--) | Liest oder setzt einen Wert, der angibt, ob der Abstieg (Tiefe unter der Grundlinie) des Basiselements als Null behandelt werden soll. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Liest oder setzt einen Wert, der angibt, ob der Abstieg (Tiefe unter der Grundlinie) des Basiselements als Null behandelt werden soll. |
| [getTransp()](#getTransp--) | Liest oder setzt einen Wert, der angibt, ob das Phantom für klassenbasierte Abstandregeln transparent ist. |
| [setTransp(boolean value)](#setTransp-boolean-) | Liest oder setzt einen Wert, der angibt, ob das Phantom für klassenbasierte Abstandregeln transparent ist. |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Basisargument

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Rückgabe:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```

Liest oder setzt einen Wert, der angibt, ob das Basiselement angezeigt wird.

--------------------

Wenn false, ist das Basiselement verborgen, kann aber je nach anderen Phantom-Einstellungen weiterhin Platz einnehmen. Entspricht dem OMML-Attribut m:show.

**Rückgabe:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

Liest oder setzt einen Wert, der angibt, ob das Basiselement angezeigt wird.

--------------------

Wenn false, ist das Basiselement verborgen, kann aber je nach anderen Phantom-Einstellungen weiterhin Platz einnehmen. Entspricht dem OMML-Attribut m:show.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

Liest oder setzt einen Wert, der angibt, ob die Breite des Basiselements als Null behandelt werden soll.

--------------------

Wenn true, reserviert das Phantom keinen horizontalen Platz für seine Basis. Entspricht dem OMML-Attribut m:zeroWid.

**Rückgabe:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

Liest oder setzt einen Wert, der angibt, ob die Breite des Basiselements als Null behandelt werden soll.

--------------------

Wenn true, reserviert das Phantom keinen horizontalen Platz für seine Basis. Entspricht dem OMML-Attribut m:zeroWid.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

Liest oder setzt einen Wert, der angibt, ob der Aufstieg (Höhe über der Grundlinie) des Basiselements als Null behandelt werden soll.

--------------------

Wenn true, hebt das Phantom die Grundlinie der umgebenden mathematischen Zeile nicht an. Entspricht dem OMML-Attribut m:zeroAsc.

**Rückgabe:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

Liest oder setzt einen Wert, der angibt, ob der Aufstieg (Höhe über der Grundlinie) des Basiselements als Null behandelt werden soll.

--------------------

Wenn true, hebt das Phantom die Grundlinie der umgebenden mathematischen Zeile nicht an. Entspricht dem OMML-Attribut m:zeroAsc.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

Liest oder setzt einen Wert, der angibt, ob der Abstieg (Tiefe unter der Grundlinie) des Basiselements als Null behandelt werden soll.

--------------------

Wenn true, senkt das Phantom die Grundlinie der umgebenden mathematischen Zeile nicht ab. Entspricht dem OMML-Attribut m:zeroDesc.

**Rückgabe:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

Liest oder setzt einen Wert, der angibt, ob der Abstieg (Tiefe unter der Grundlinie) des Basiselements als Null behandelt werden soll.

--------------------

Wenn true, senkt das Phantom die Grundlinie der umgebenden mathematischen Zeile nicht ab. Entspricht dem OMML-Attribut m:zeroDesc.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

Liest oder setzt einen Wert, der angibt, ob das Phantom für klassenbasierte Abstandregeln transparent ist.

--------------------

Wenn true, beeinflussen Operatoren und Symbole im Phantom weiterhin den mathematischen Abstand um das Phantom (als wäre es sichtbar). Wenn false, werden klassenbasierte Abstände ignoriert. Entspricht dem OMML-Attribut m:transp.

**Rückgabe:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

Liest oder setzt einen Wert, der angibt, ob das Phantom für klassenbasierte Abstandregeln transparent ist.

--------------------

Wenn true, beeinflussen Operatoren und Symbole im Phantom weiterhin den mathematischen Abstand um das Phantom (als wäre es sichtbar). Wenn false, werden klassenbasierte Abstände ignoriert. Entspricht dem OMML-Attribut m:transp.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |