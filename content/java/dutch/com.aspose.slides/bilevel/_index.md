---
title: BiLevel
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een Bi-Level zwart/wit effect voor.
type: docs
url: /nl/com.aspose.slides/bilevel/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Vertegenwoordigt een Bi-Level (zwart/wit) effect. Invoerkleuren waarvan de luminantie kleiner is dan de gespecificeerde drempelwaarde worden gewijzigd in zwart. Invoerkleuren waarvan de luminantie groter of gelijk is aan de gespecificeerde waarde worden ingesteld op wit. De alfa-effectwaarden blijven door dit effect onaangetast.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getEffective()](#getEffective--) | Haalt effectieve Bi-Level-effectgegevens op met de erfenis toegepast. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de opgegeven [BiLevel](../../com.aspose.slides/bilevel) gelijk is aan de huidige [BiLevel](../../com.aspose.slides/bilevel). |
| [hashCode()](#hashCode--) | Dient als hashfunctie voor een bepaald type. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```


Haalt effectieve Bi-Level-effectgegevens op met de erfenis toegepast.

**Retour:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - een [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of de opgegeven [BiLevel](../../com.aspose.slides/bilevel) gelijk is aan de huidige [BiLevel](../../com.aspose.slides/bilevel).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | De [BiLevel](../../com.aspose.slides/bilevel) om te vergelijken. |

**Retour:**
boolean - true als objecten gelijk zijn; anders false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als hashfunctie voor een bepaald type.

**Retour:**
int - Een hashcode voor het huidige object.