---
title: ISlideSize
second_title: Aspose.Slides for Java API Reference
description: Stellt die Größe und Ausrichtung einer Folie dar.
type: docs
url: /de/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

Stellt die Größe und Ausrichtung einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSize()](#getSize--) | Gibt die Folienabmessungen in Punkten zurück. |
| [getType()](#getType--) | Gibt den Foliengrößentyp zurück. |
| [getOrientation()](#getOrientation--) | Liest oder setzt die Folienausrichtung. |
| [setOrientation(int value)](#setOrientation-int-) | Liest oder setzt die Folienausrichtung. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Setzt die Foliengröße nach Typ und skaliert den vorhandenen Inhalt. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Setzt die Folienabmessungen explizit und skaliert den vorhandenen Inhalt. |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```

Gibt die Folienabmessungen in Punkten zurück.

--------------------

Durch Zuweisen eines neuen Wertes wird die Eigenschaft \#getType.getType auf [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) zurückgesetzt und die \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) gesetzt.

**Rückgabe:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public abstract int getType()
```

Gibt den Foliengrößentyp zurück.

--------------------

Durch Zuweisen eines beliebigen Wertes außer [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) wird die \#getSize.getSize gemäß den vordefinierten Abmessungen angepasst, wobei die aktuelle \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) beibehalten wird.

**Rückgabe:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```

Liest oder setzt die Folienausrichtung.

--------------------

Durch Ändern dieses Werts werden die Breite und Höhe der Folie vertauscht.

**Rückgabe:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```

Liest oder setzt die Folienausrichtung.

--------------------

Durch Ändern dieses Werts werden die Breite und Höhe der Folie vertauscht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```

Setzt die Foliengröße nach Typ und skaliert den vorhandenen Inhalt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Die anzuwendende vordefinierte Foliengröße. |
| scaleType | int | Der zu verwendende Inhalts-Skalierungsmodus. |

--------------------

Durch Zuweisen eines beliebigen Wertes außer [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) wird die \#getSize.getSize basierend auf dem ausgewählten Typ angepasst, wobei die \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) erhalten bleibt. |
### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```

Setzt die Folienabmessungen explizit und skaliert den vorhandenen Inhalt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | float | Die neue Folienbreite in Punkten. |
| height | float | Die neue Folienhöhe in Punkten. |
| scaleType | int | Der zu verwendende Inhalts-Skalierungsmodus. |

--------------------

Dies setzt die Eigenschaft \#getType.getType auf [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) zurück und setzt die \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |