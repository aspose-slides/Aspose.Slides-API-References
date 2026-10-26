---
title: AlphaModulate
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt einen Alpha-Modulate-Effekt dar.
type: docs
url: /de/com.aspose.slides/alphamodulate/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IAlphaModulate](../../com.aspose.slides/ialphamodulate), com.aspose.slides.IVisualEffect
```
public final class AlphaModulate extends ImageTransformOperation implements IAlphaModulate, IVisualEffect
```

Stellt einen Alpha-Modulate-Effekt dar. Die Alpha- (Deckkraft-)Werte des Effekts werden mit einem festen Prozentsatz multipliziert. Der Effekt-Container gibt einen Effekt an, der Alpha-Werte zum Modulieren enthält.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEffective()](#getEffective--) | Ruft effektive Alpha Modulate-Effektdaten ab, wobei die Vererbung angewendet wird. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [AlphaModulate](../../com.aspose.slides/alphamodulate) gleich dem aktuellen [AlphaModulate](../../com.aspose.slides/alphamodulate) ist. |
| [hashCode()](#hashCode--) | Dient als Hashfunktion für einen bestimmten Typ. |
### getEffective() {#getEffective--}
```
public final IAlphaModulateEffectiveData getEffective()
```


Ruft effektive Alpha Modulate-Effektdaten ab, wobei die Vererbung angewendet wird.

**Rückgabewert:**
[IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata) - Ein [IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene [AlphaModulate](../../com.aspose.slides/alphamodulate) gleich dem aktuellen [AlphaModulate](../../com.aspose.slides/alphamodulate) ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das [AlphaModulate](../../com.aspose.slides/alphamodulate) zum Vergleich. |

**Rückgabewert:**
boolean - true wenn Objekte gleich sind; andernfalls false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als Hashfunktion für einen bestimmten Typ.

**Rückgabewert:**
int - Ein Hashcode für das aktuelle Objekt.