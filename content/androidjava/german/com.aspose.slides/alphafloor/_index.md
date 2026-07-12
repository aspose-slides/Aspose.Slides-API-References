---
title: AlphaFloor
second_title: Aspose.Slides für Android über Java-API-Referenz
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

Stellt einen Alpha-Floor-Effekt dar. Alpha (Opazität)-Werte unter 100% werden auf null gesetzt. Mit anderen Worten wird alles, das teilweise transparent ist, vollständig transparent.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEffective()](#getEffective--) | Ruft die wirksamen Alpha-Floor-Effektdaten mit angewandter Vererbung ab. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [AlphaFloor](../../com.aspose.slides/alphafloor) dem aktuellen [AlphaFloor](../../com.aspose.slides/alphafloor) entspricht. |
| [hashCode()](#hashCode--) | Dient als Hashfunktion für einen bestimmten Typ. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```

Ruft die wirksamen Alpha-Floor-Effektdaten mit angewandter Vererbung ab.

**Rückgabewert:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - Ein [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestimmt, ob das angegebene [AlphaFloor](../../com.aspose.slides/alphafloor) dem aktuellen [AlphaFloor](../../com.aspose.slides/alphafloor) entspricht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das [AlphaFloor](../../com.aspose.slides/alphafloor) zum Vergleichen. |

**Rückgabewert:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als Hashfunktion für einen bestimmten Typ.

**Rückgabewert:**
int - A hash code for the current object.