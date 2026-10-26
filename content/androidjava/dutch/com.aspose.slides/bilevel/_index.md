---
title: BiLevel
second_title: Aspose.Slides voor Android via Java API-referentie
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

Stelt een Bi-Level (zwart/wit) effect voor. Invoerkleuren waarvan de luminantie lager is dan de opgegeven drempelwaarde worden veranderd in zwart. Invoerkleuren waarvan de luminantie groter dan of gelijk aan de opgegeven waarde is, worden ingesteld op wit. De alfa-effectwaarden blijven onaangedaan door dit effect.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getEffective()](#getEffective--) | Haalt effectieve Bi-Level effectgegevens op met de erfelijkheid toegepast. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de opgegeven [BiLevel](../../com.aspose.slides/bilevel) gelijk is aan de huidige [BiLevel](../../com.aspose.slides/bilevel). |
| [hashCode()](#hashCode--) | Dient als hash-functie voor een bepaald type. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```


Haalt effectieve Bi-Level effectgegevens op met de erfelijkheid toegepast.

**Retour:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - Een [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of de opgegeven [BiLevel](../../com.aspose.slides/bilevel) gelijk is aan de huidige [BiLevel](../../com.aspose.slides/bilevel).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | De [BiLevel](../../com.aspose.slides/bilevel) om te vergelijken.

**Retour:**
boolean - true als objecten gelijk zijn; anders false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als hash-functie voor een bepaald type.

**Retour:**
int - Een hashcode voor het huidige object.