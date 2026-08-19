---
title: AlphaCeiling
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een Alpha Ceiling-effect voor.
type: docs
url: /nl/com.aspose.slides/alphaceiling/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IAlphaCeiling](../../com.aspose.slides/ialphaceiling), com.aspose.slides.IVisualEffect
```
public final class AlphaCeiling extends ImageTransformOperation implements IAlphaCeiling, IVisualEffect
```

Stelt een Alpha Ceiling-effect voor. Alpha (opaciteit) waarden groter dan nul worden gewijzigd naar 100%. Met andere woorden, alles wat gedeeltelijk doorschijnend is, wordt volledig doorschijnend.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getEffective()](#getEffective--) | Krijgt effectieve Alpha Ceiling-effectgegevens met de geërfde instellingen toegepast. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de opgegeven [AlphaCeiling](../../com.aspose.slides/alphaceiling) gelijk is aan de huidige [AlphaCeiling](../../com.aspose.slides/alphaceiling). |
| [hashCode()](#hashCode--) | Dient als hash-functie voor een bepaald type. |
### getEffective() {#getEffective--}
```
public final IAlphaCeilingEffectiveData getEffective()
```


Krijgt effectieve Alpha Ceiling-effectgegevens met de geërfde instellingen toegepast.

**Retour:**
[IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata) - Een [IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of de opgegeven [AlphaCeiling](../../com.aspose.slides/alphaceiling) gelijk is aan de huidige [AlphaCeiling](../../com.aspose.slides/alphaceiling).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | De [AlphaCeiling](../../com.aspose.slides/alphaceiling) om te vergelijken. |

**Retour:**
boolean - true als objecten gelijk zijn; anders false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als hash-functie voor een bepaald type.

**Retour:**
int - Een hashcode voor het huidige object.