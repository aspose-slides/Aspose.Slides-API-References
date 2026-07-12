---
title: ISmartArt
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt ein SmartArt-Diagramm dar.
type: docs
url: /de/com.aspose.slides/ismartart/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

Stellt ein SmartArt-Diagramm dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Gibt Sammlungen aller Knoten im SmartArt-Objekt zurück. |
| [getNodes()](#getNodes--) | Gibt Sammlungen von Wurzelknoten im SmartArt-Objekt zurück. |
| [getLayout()](#getLayout--) | Liefert oder setzt das Layout des SmartArt-Objekts. |
| [setLayout(int value)](#setLayout-int-) | Liefert oder setzt das Layout des SmartArt-Objekts. |
| [getQuickStyle()](#getQuickStyle--) | Liefert oder setzt den Schnellstil des SmartArt-Objekts. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Liefert oder setzt den Schnellstil des SmartArt-Objekts. |
| [getColorStyle()](#getColorStyle--) | Liefert oder setzt den Farbstil des SmartArt-Objekts. |
| [setColorStyle(int value)](#setColorStyle-int-) | Liefert oder setzt den Farbstil des SmartArt-Objekts. |
| [isReversed()](#isReversed--) | Liefert oder setzt den Zustand des SmartArt-Diagramms in Bezug auf (von links nach rechts) LTR oder (von rechts nach links) RTL, falls das Diagramm eine Umkehrung unterstützt. |
| [setReversed(boolean value)](#setReversed-boolean-) | Liefert oder setzt den Zustand des SmartArt-Diagramms in Bezug auf (von links nach rechts) LTR oder (von rechts nach links) RTL, falls das Diagramm eine Umkehrung unterstützt. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

Gibt Sammlungen aller Knoten im SmartArt-Objekt zurück. Nur lesbar [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Rückgabe:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

Gibt Sammlungen von Wurzelknoten im SmartArt-Objekt zurück. Nur lesbar [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Rückgabe:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

Liefert oder setzt das Layout des SmartArt-Objekts. Lesen/Schreiben [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Rückgabe:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

Liefert oder setzt das Layout des SmartArt-Objekts. Lesen/Schreiben [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

Liefert oder setzt den Schnellstil des SmartArt-Objekts. Lesen/Schreiben [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Rückgabe:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```

Liefert oder setzt den Schnellstil des SmartArt-Objekts. Lesen/Schreiben [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

Liefert oder setzt den Farbstil des SmartArt-Objekts. Lesen/Schreiben [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Rückgabe:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

Liefert oder setzt den Farbstil des SmartArt-Objekts. Lesen/Schreiben [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

Liefert oder setzt den Zustand des SmartArt-Diagramms in Bezug auf (von links nach rechts) LTR oder (von rechts nach links) RTL, falls das Diagramm eine Umkehrung unterstützt. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

Liefert oder setzt den Zustand des SmartArt-Diagramms in Bezug auf (von links nach rechts) LTR oder (von rechts nach links) RTL, falls das Diagramm eine Umkehrung unterstützt. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |