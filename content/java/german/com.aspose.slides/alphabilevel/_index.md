---
title: AlphaBiLevel
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Alpha Bi-Level Effekt dar.
type: docs
url: /de/com.aspose.slides/alphabilevel/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Stellt einen Alpha-Bi-Level-Effekt dar. Alpha-(Opacity)-Werte, die kleiner als der Schwellenwert sind, werden auf 0 (vollständig transparent) geändert, und Alpha-Werte, die größer oder gleich dem Schwellenwert sind, werden auf 100 % (vollständig undurchsichtig) geändert.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getThreshold()](#getThreshold--) | Gibt den Schwellenwert des Effekts zurück. |
| [setThreshold(float value)](#setThreshold-float-) | Gibt den Schwellenwert des Effekts zurück. |
| [getEffective()](#getEffective--) | Ruft wirksame Alpha-Bi-Level-Effekt-Daten mit angewandter Vererbung ab. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [AlphaBiLevel](../../com.aspose.slides/alphabilevel) dem aktuellen [AlphaBiLevel](../../com.aspose.slides/alphabilevel) entspricht. |
| [hashCode()](#hashCode--) | Dient als Hash-Funktion für einen bestimmten Typ. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

Gibt den Schwellenwert des Effekts zurück. Lesen/Schreiben float.

**Rückgabe:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

Gibt den Schwellenwert des Effekts zurück. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

Ruft wirksame Alpha-Bi-Level-Effekt-Daten mit angewandter Vererbung ab.

**Rückgabe:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - Ein [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestimmt, ob das angegebene [AlphaBiLevel](../../com.aspose.slides/alphabilevel) dem aktuellen [AlphaBiLevel](../../com.aspose.slides/alphabilevel) entspricht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Der [AlphaBiLevel](../../com.aspose.slides/alphabilevel) zum Vergleich. |

**Rückgabe:**
boolean – wahr, wenn Objekte gleich sind; andernfalls falsch.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als Hash-Funktion für einen bestimmten Typ.

**Rückgabe:**
int – Ein Hashcode für das aktuelle Objekt.