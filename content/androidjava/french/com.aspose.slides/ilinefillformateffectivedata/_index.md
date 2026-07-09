---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides pour Android via l'API Java
description: Objet immuable contenant les propriétés effectives de remplissage de ligne.
type: docs
url: /fr/com.aspose.slides/ilinefillformateffectivedata/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Objet immuable contenant les propriétés effectives de remplissage de ligne.

--------------------

Cette interface est utilisée comme partie de [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Retourne le type de remplissage. |
| [getSolidFillColor()](#getSolidFillColor--) | Retourne la couleur d'un remplissage uni. |
| [getGradientFormat()](#getGradientFormat--) | Retourne le format de remplissage en dégradé. |
| [getPatternFormat()](#getPatternFormat--) | Retourne le format de remplissage en motif. |
| [getRotateWithShape()](#getRotateWithShape--) | Détermine si le remplissage doit être pivoté avec une forme. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Retourne le type de remplissage. Lecture seule [FillType](../../com.aspose.slides/filltype).

**Retourne :**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


Retourne la couleur d'un remplissage uni. Lecture seule java.lang.Integer.

**Retourne :**
java.lang.Integer
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Retourne le format de remplissage en dégradé. Lecture seule [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Retourne :**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Retourne le format de remplissage en motif. Lecture seule [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Retourne :**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Détermine si le remplissage doit être pivoté avec une forme. Lecture seule boolean.

**Retourne :**
boolean