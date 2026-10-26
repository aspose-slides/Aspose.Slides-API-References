---
title: AlphaCeiling
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Alpha Ceiling-Effekt dar.
type: docs
url: /de/com.aspose.slides/alphaceiling/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IAlphaCeiling](../../com.aspose.slides/ialphaceiling), com.aspose.slides.IVisualEffect
```
public final class AlphaCeiling extends ImageTransformOperation implements IAlphaCeiling, IVisualEffect
```

Stellt einen Alpha Ceiling-Effekt dar. Alpha- (Opazitäts-) Werte, die größer als null sind, werden auf 100 % geändert. Mit anderen Worten: Alles, das teilweise undurchsichtig ist, wird vollständig undurchsichtig.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEffective()](#getEffective--) | Retrieves effective Alpha Ceiling effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaCeiling](../../com.aspose.slides/alphaceiling) is equal to the current [AlphaCeiling](../../com.aspose.slides/alphaceiling). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |

### getEffective() {#getEffective--}
```
public final IAlphaCeilingEffectiveData getEffective()
```

Ermittelt die wirksamen Alpha Ceiling-Effektdaten mit angewandter Vererbung.

**Rückgabe:**
[IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata) - ein [IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestimmt, ob das angegebene [AlphaCeiling](../../com.aspose.slides/alphaceiling) dem aktuellen [AlphaCeiling](../../com.aspose.slides/alphaceiling) entspricht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das [AlphaCeiling](../../com.aspose.slides/alphaceiling) zum Vergleich. |

**Rückgabe:**
boolean - true, wenn Objekte gleich sind; andernfalls false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als Hash-Funktion für einen bestimmten Typ.

**Rückgabe:**
int - Ein Hashcode für das aktuelle Objekt.