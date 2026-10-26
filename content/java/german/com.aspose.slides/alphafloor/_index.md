---
title: AlphaFloor
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Alpha Floor-Effekt dar.
type: docs
url: /de/com.aspose.slides/alphafloor/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Stellt einen Alpha-Floor-Effekt dar. Alpha- (Opazitäts-) Werte unter 100 % werden auf null gesetzt. Mit anderen Worten, alles, das teilweise transparent ist, wird vollständig transparent.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEffective()](#getEffective--) | Ruft effektive Alpha-Floor-Effektdaten mit angewendeter Vererbung ab. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [AlphaFloor](../../com.aspose.slides/alphafloor) gleich dem aktuellen [AlphaFloor](../../com.aspose.slides/alphafloor) ist. |
| [hashCode()](#hashCode--) | Dient als Hash-Funktion für einen bestimmten Typ. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```


Ruft effektive Alpha-Floor-Effektdaten mit angewendeter Vererbung ab.

**Rückgabe:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - A [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene [AlphaFloor](../../com.aspose.slides/alphafloor) gleich dem aktuellen [AlphaFloor](../../com.aspose.slides/alphafloor) ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das [AlphaFloor](../../com.aspose.slides/alphafloor) zum Vergleich. |

**Rückgabe:**
boolean - wahr, wenn Objekte gleich sind; andernfalls falsch.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als Hash-Funktion für einen bestimmten Typ.

**Rückgabe:**
int - Ein Hash-Code für das aktuelle Objekt.