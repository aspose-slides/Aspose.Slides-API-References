---
title: BiLevel
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en Bi-Level svart/vitt-effekt.
type: docs
url: /sv/com.aspose.slides/bilevel/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Representerar en Bi-Level (svart/vitt) effekt. Inmatningsfärger vars luminans är mindre än det angivna tröskelvärdet ändras till svart. Inmatningsfärger vars luminans är större än eller lika med det angivna värdet sätts till vitt. Alfa-effektvärdena påverkas inte av denna effekt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Bi-Level effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [BiLevel](../../com.aspose.slides/bilevel) is equal to the current [BiLevel](../../com.aspose.slides/bilevel). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```


Gets effective Bi-Level effect data with the inheritance applied.

**Returnerar:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - A [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified [BiLevel](../../com.aspose.slides/bilevel) is equal to the current [BiLevel](../../com.aspose.slides/bilevel).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | The [BiLevel](../../com.aspose.slides/bilevel) to compare. |

**Returnerar:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returnerar:**
int - A hash code for the current object.