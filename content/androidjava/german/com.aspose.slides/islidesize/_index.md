---
title: ISlideSize
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the size and orientation of a slide.
type: docs
url: /de/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

Stellt die Größe und Ausrichtung einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSize()](#getSize--) | Liest die Folienabmessungen in Punkten. |
| [getType()](#getType--) | Liest den Foliengrößentyp. |
| [getOrientation()](#getOrientation--) | Liest oder legt die Folienausrichtung fest. |
| [setOrientation(int value)](#setOrientation-int-) | Liest oder legt die Folienausrichtung fest. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Legt die Foliengröße anhand des Typs fest und skaliert vorhandenen Inhalt. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Legt die Folienabmessungen explizit fest und skaliert vorhandenen Inhalt. |
### getSize() {#getSize--}
```
public abstract SizeF getSize()
```


Liest die Folienabmessungen in Punkten.

--------------------

Durch Zuweisen eines neuen Werts wird die #getType.getType Eigenschaft auf [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) zurückgesetzt und die #getOrientation.getOrientation/#setOrientation(int).setOrientation(int) festgelegt.

**Rückgabewert:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public abstract int getType()
```


Liest den Foliengrößentyp.

--------------------

Durch Zuweisen eines beliebigen Werts außer [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) wird #getSize.getSize gemäß den vordefinierten Abmessungen angepasst, während die aktuelle #getOrientation.getOrientation/#setOrientation(int).setOrientation(int) beibehalten wird.

**Rückgabewert:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```


Liest oder legt die Folienausrichtung fest.

--------------------

Durch Ändern dieses Werts werden die Breite und Höhe der Folie vertauscht.

**Rückgabewert:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```


Liest oder legt die Folienausrichtung fest.

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


Legt die Foliengröße anhand des Typs fest und skaliert vorhandenen Inhalt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der anzuwendende vordefinierte Foliengrößentyp. |
| scaleType | int | Der zu verwendende Modus zum Skalieren des Inhalts. |

--------------------

Durch Zuweisen eines beliebigen Werts außer [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) wird #getSize.getSize basierend auf dem ausgewählten Typ angepasst, während #getOrientation.getOrientation/#setOrientation(int).setOrientation(int) erhalten bleibt. |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```


Legt die Folienabmessungen explizit fest und skaliert vorhandenen Inhalt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | float | Die neue Folienbreite in Punkten. |
| height | float | Die neue Folienhöhe in Punkten. |
| scaleType | int | Der zu verwendende Modus zum Skalieren des Inhalts. |

--------------------

Dies setzt die #getType.getType Eigenschaft auf [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) zurück und legt {\#getOrientation.getOrientation/#setOrientation(int).setOrientation(int) fest. |