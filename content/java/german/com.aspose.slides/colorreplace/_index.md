---
title: ColorReplace
second_title: Aspose.Slides für Java API Referenz
description: Stellt einen Color Replacement-Effekt dar.
type: docs
url: /de/com.aspose.slides/colorreplace/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

Stellt einen Color Replacement-Effekt dar. Alle Effektfarben werden in eine feste Farbe geändert. Alphawerte bleiben unverändert.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColor()](#getColor--) | Gibt das Farbformat zurück, das die Farbe jedes Pixels ersetzt. |
| [getEffective()](#getEffective--) | Ruft die wirksamen Daten des Color Replacement-Effekts mit angewandter Vererbung ab. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [ColorReplace](../../com.aspose.slides/colorreplace) gleich dem aktuellen [ColorReplace](../../com.aspose.slides/colorreplace) ist. |
| [hashCode()](#hashCode--) | Dient als Hashfunktion für einen bestimmten Typ. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Gibt das Farbformat zurück, das die Farbe jedes Pixels ersetzt. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

Ruft die wirksamen Daten des Color Replacement-Effekts mit angewandter Vererbung ab.

**Rückgabe:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - A [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur lesbar long.

**Rückgabe:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestimmt, ob das angegebene [ColorReplace](../../com.aspose.slides/colorreplace) gleich dem aktuellen [ColorReplace](../../com.aspose.slides/colorreplace) ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das [ColorReplace](../../com.aspose.slides/colorreplace) zum Vergleichen. |

**Rückgabe:**
boolean - true, wenn Objekte gleich sind; andernfalls false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als Hashfunktion für einen bestimmten Typ.

**Rückgabe:**
int - Ein Hashcode für das aktuelle Objekt.