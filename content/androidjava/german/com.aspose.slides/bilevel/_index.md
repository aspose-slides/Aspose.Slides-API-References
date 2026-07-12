---
title: BiLevel
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Stellt einen Bi-Level Schwarz/Weiß-Effekt dar.
type: docs
url: /de/com.aspose.slides/bilevel/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Stellt einen Bi-Level (schwarz/weiß) Effekt dar. Eingabefarben, deren Luminanz kleiner als der angegebene Schwellenwert ist, werden zu Schwarz geändert. Eingabefarben, deren Luminanz größer als oder gleich dem angegebenen Wert ist, werden zu Weiß gesetzt. Die Alpha-Effektwerte bleiben von diesem Effekt unberührt.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEffective()](#getEffective--) | Ermittelt effektive Bi-Level-Effektdaten mit der angewandten Vererbung. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [BiLevel](../../com.aspose.slides/bilevel) gleich dem aktuellen [BiLevel](../../com.aspose.slides/bilevel) ist. |
| [hashCode()](#hashCode--) | Dient als Hash-Funktion für einen bestimmten Typ. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

Ermittelt effektive Bi-Level-Effektdaten mit der angewandten Vererbung.

**Rückgabewert:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - Ein [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestimmt, ob das angegebene [BiLevel](../../com.aspose.slides/bilevel) gleich dem aktuellen [BiLevel](../../com.aspose.slides/bilevel) ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Der [BiLevel](../../com.aspose.slides/bilevel) zum Vergleich. |

**Rückgabewert:**
boolean - true wenn Objekte gleich sind; sonst false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als Hash-Funktion für einen bestimmten Typ.

**Rückgabewert:**
int - Ein Hashcode für das aktuelle Objekt.