---
title: SlideSize
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt die Größe und Ausrichtung einer Folie dar.
type: docs
url: /de/com.aspose.slides/slidesize/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

Stellt die Größe und Ausrichtung einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSize()](#getSize--) | Liefert die Folienabmessungen in Punkten. |
| [getType()](#getType--) | Liefert den Foliengrößentyp. |
| [getOrientation()](#getOrientation--) | Liefert oder setzt die Folienausrichtung. |
| [setOrientation(int value)](#setOrientation-int-) | Liefert oder setzt die Folienausrichtung. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Setzt die Foliengröße nach Typ und skaliert den vorhandenen Inhalt. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Setzt die Folienabmessungen explizit und skaliert den vorhandenen Inhalt. |
### getSize() {#getSize--}}
```
public final SizeF getSize()
```


Liefert die Folienabmessungen in Punkten.

--------------------

Durch Zuweisen eines neuen Werts wird die \#getType.getType Eigenschaft auf [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) zurückgesetzt und die \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) gesetzt.

**Rückgabe:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}}
```
public final int getType()
```


Liefert den Foliengrößentyp.

--------------------

Durch Zuweisen eines beliebigen Werts, der nicht [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ist, wird die \#getSize.getSize gemäß den vordefinierten Abmessungen angepasst, wobei die aktuelle \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) beibehalten wird.

**Rückgabe:**
int
### getOrientation() {#getOrientation--}}
```
public final int getOrientation()
```


Liefert oder setzt die Folienausrichtung.

--------------------

Durch Ändern dieses Werts werden die Breite und Höhe der Folie vertauscht.

**Rückgabe:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```


Liefert oder setzt die Folienausrichtung.

--------------------

Durch Ändern dieses Werts werden die Breite und Höhe der Folie vertauscht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```


Setzt die Foliengröße nach Typ und skaliert den vorhandenen Inhalt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Die anzuwendende vordefinierte Foliengröße. |
| scaleType | int | Der zu verwendende Skalierungsmodus für den Inhalt. |
--------------------

Durch Zuweisen eines beliebigen Werts, der nicht [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ist, wird die \#getSize.getSize basierend auf dem ausgewählten Typ angepasst, während die \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) erhalten bleibt. |
### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```


Setzt die Folienabmessungen explizit und skaliert den vorhandenen Inhalt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | float | Die neue Folienbreite in Punkten. |
| height | float | Die neue Folienhöhe in Punkten. |
| scaleType | int | Der zu verwendende Skalierungsmodus für den Inhalt. |
--------------------

Dies setzt die \#getType.getType Eigenschaft auf [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) und die \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |