---
title: ISmartArt
second_title: Aspose.Slides für Java API-Referenz
description: Stellt ein SmartArt-Diagramm dar.
type: docs
url: /de/com.aspose.slides/ismartart/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

Stellt ein SmartArt-Diagramm dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Gibt Sammlungen aller Knoten im SmartArt-Objekt zurück. |
| [getNodes()](#getNodes--) | Gibt Sammlungen der Wurzelknoten im SmartArt-Objekt zurück. |
| [getLayout()](#getLayout--) | Gibt das Layout des SmartArt-Objekts zurück oder legt es fest. |
| [setLayout(int value)](#setLayout-int-) | Gibt das Layout des SmartArt-Objekts zurück oder legt es fest. |
| [getQuickStyle()](#getQuickStyle--) | Gibt den Quick-Style des SmartArt-Objekts zurück oder legt ihn fest. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Gibt den Quick-Style des SmartArt-Objekts zurück oder legt ihn fest. |
| [getColorStyle()](#getColorStyle--) | Gibt den Color-Style des SmartArt-Objekts zurück oder legt ihn fest. |
| [setColorStyle(int value)](#setColorStyle-int-) | Gibt den Color-Style des SmartArt-Objekts zurück oder legt ihn fest. |
| [isReversed()](#isReversed--) | Gibt den Zustand des SmartArt-Diagramms in Bezug auf (von links nach rechts) LTR oder (von rechts nach links) RTL zurück bzw. legt ihn fest, falls das Diagramm eine Umkehrung unterstützt. |
| [setReversed(boolean value)](#setReversed-boolean-) | Gibt den Zustand des SmartArt-Diagramms in Bezug auf (von links nach rechts) LTR oder (von rechts nach links) RTL zurück bzw. legt ihn fest, falls das Diagramm eine Umkehrung unterstützt. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```


Gibt Sammlungen aller Knoten im SmartArt-Objekt zurück. Nur-Lesen [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Rückgabe:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```


Gibt Sammlungen der Wurzelknoten im SmartArt-Objekt zurück. Nur-Lesen [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Rückgabe:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Gibt das Layout des SmartArt-Objekts zurück oder legt es fest. Schreib/Lese [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Rückgabe:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```


Gibt das Layout des SmartArt-Objekts zurück oder legt es fest. Schreib/Lese [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```


Gibt den Quick-Style des SmartArt-Objekts zurück oder legt ihn fest. Schreib/Lese [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Rückgabe:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```


Gibt den Quick-Style des SmartArt-Objekts zurück oder legt ihn fest. Schreib/Lese [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```


Gibt den Color-Style des SmartArt-Objekts zurück oder legt ihn fest. Schreib/Lese [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Rückgabe:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```


Gibt den Color-Style des SmartArt-Objekts zurück oder legt ihn fest. Schreib/Lese [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```


Gibt den Zustand des SmartArt-Diagramms in Bezug auf (von links nach rechts) LTR oder (von rechts nach links) RTL zurück bzw. legt ihn fest, falls das Diagramm eine Umkehrung unterstützt. Schreib/Lese boolean.

**Rückgabe:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```


Gibt den Zustand des SmartArt-Diagramms in Bezug auf (von links nach rechts) LTR oder (von rechts nach links) RTL zurück bzw. legt ihn fest, falls das Diagramm eine Umkehrung unterstützt. Schreib/Lese boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |