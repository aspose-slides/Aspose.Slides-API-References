---
title: AlphaCeiling
second_title: Aspose.Slides für Android über die Java-API-Referenz
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

Stellt einen Alpha Ceiling-Effekt dar. Alpha (Undurchsichtigkeit) Werte größer als null werden auf 100 % geändert. Mit anderen Worten, alles, das teilweise undurchsichtig ist, wird vollständig undurchsichtig.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEffective()](#getEffective--) | Ruft effektive Alpha Ceiling-Effektdaten ab, wobei die Vererbung angewendet wird. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [AlphaCeiling](../../com.aspose.slides/alphaceiling) dem aktuellen [AlphaCeiling](../../com.aspose.slides/alphaceiling) entspricht. |
| [hashCode()](#hashCode--) | Dient als Hash-Funktion für einen bestimmten Typ. |
### getEffective() {#getEffective--}
```
public final IAlphaCeilingEffectiveData getEffective()
```


Ruft effektive Alpha Ceiling-Effektdaten ab, wobei die Vererbung angewendet wird.

**Rückgabe:**
[IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata) - A [IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene [AlphaCeiling](../../com.aspose.slides/alphaceiling) dem aktuellen [AlphaCeiling](../../com.aspose.slides/alphaceiling) entspricht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das [AlphaCeiling](../../com.aspose.slides/alphaceiling) zum Vergleichen. |

**Rückgabe:**
boolean - true, wenn die Objekte gleich sind; andernfalls false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als Hash-Funktion für einen bestimmten Typ.

**Rückgabe:**
int - Ein Hash-Code für das aktuelle Objekt.