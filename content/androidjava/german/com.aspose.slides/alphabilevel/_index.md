---
title: AlphaBiLevel
second_title: Aspose.Slides für Android über Java API Reference
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

Stellt einen Alpha-Bi-Level-Effekt dar. Alpha- (Opazitäts-) Werte, die kleiner als der Schwellenwert sind, werden zu 0 (vollständig transparent) geändert, und Alpha-Werte, die größer oder gleich dem Schwellenwert sind, werden zu 100 % (vollständig undurchsichtig) geändert.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getThreshold()](#getThreshold--) | Returns effect threshold. |
| [setThreshold(float value)](#setThreshold-float-) | Returns effect threshold. |
| [getEffective()](#getEffective--) | Gets effective Alpha Bi-Level effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaBiLevel](../../com.aspose.slides/alphabilevel) is equal to the current [AlphaBiLevel](../../com.aspose.slides/alphabilevel). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

Gibt den Effekt-Schwellwert zurück. Lese-/Schreibzugriff float.

**Rückgabewert:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

Gibt den Effekt-Schwellwert zurück. Lese-/Schreibzugriff float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

Ermittelt effektive Alpha-Bi-Level-Effektdaten mit angewendeter Vererbung.

**Rückgabewert:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - A [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestimmt, ob das angegebene [AlphaBiLevel](../../com.aspose.slides/alphabilevel) gleich dem aktuellen [AlphaBiLevel](../../com.aspose.slides/alphabilevel) ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das [AlphaBiLevel](../../com.aspose.slides/alphabilevel) zum Vergleich. |

**Rückgabewert:**
boolean – true, wenn Objekte gleich sind; andernfalls false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als Hash-Funktion für einen bestimmten Typ.

**Rückgabewert:**
int – Ein Hash-Code für das aktuelle Objekt.