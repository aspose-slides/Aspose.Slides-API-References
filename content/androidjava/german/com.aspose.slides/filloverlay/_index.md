---
title: FillOverlay
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt einen Fill Overlay-Effekt dar.
type: docs
url: /de/com.aspose.slides/filloverlay/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Stellt einen Fill Overlay-Effekt dar. Ein Fill Overlay kann verwendet werden, um eine zusätzliche Füllung für ein Objekt anzugeben und die beiden Füllungen zu mischen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Fill format. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Ruft die effektiven Fill Overlay-Effekt-Daten mit angewendeter Vererbung ab. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [FillOverlay](../../com.aspose.slides/filloverlay) dem aktuellen [FillOverlay](../../com.aspose.slides/filloverlay) entspricht. |
| [hashCode()](#hashCode--) | Dient als Hash-Funktion für einen bestimmten Typ. |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Fill format. Nur lesbar [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabewert:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```


FillBlendMode. Lese-/Schreibzugriff [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Rückgabewert:**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```


FillBlendMode. Lese-/Schreibzugriff [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```


Ruft die effektiven Fill Overlay-Effekt-Daten mit angewendeter Vererbung ab.

**Rückgabewert:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - A [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Nur lesbarer long.

**Rückgabewert:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene [FillOverlay](../../com.aspose.slides/filloverlay) dem aktuellen [FillOverlay](../../com.aspose.slides/filloverlay) entspricht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das [FillOverlay](../../com.aspose.slides/filloverlay) zum Vergleich. |

**Rückgabewert:**
boolean - true, wenn die Objekte gleich sind; sonst false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als Hash-Funktion für einen bestimmten Typ.

**Rückgabewert:**
int - Ein Hashcode für das aktuelle Objekt.