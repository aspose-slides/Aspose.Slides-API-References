---
title: ILineFillFormatEffectiveData
second_title: Référence de l'API Aspose.Slides pour Java
description: Objet immuable qui contient les propriétés de remplissage de ligne effectives.
type: docs
url: /fr/com.aspose.slides/ilinefillformateffectivedata/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Objet immuable qui contient les propriétés de remplissage de ligne effectives.

--------------------

Cette interface est utilisée comme partie de [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

## Méthodes

| Méthode | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Renvoie le type de remplissage. |
| [getSolidFillColor()](#getSolidFillColor--) | Renvoie la couleur d'un remplissage plein. |
| [getGradientFormat()](#getGradientFormat--) | Renvoie le format de remplissage dégradé. |
| [getPatternFormat()](#getPatternFormat--) | Renvoie le format de remplissage en motif. |
| [getRotateWithShape()](#getRotateWithShape--) | Détermine si le remplissage doit être tourné avec une forme. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Renvoie le type de remplissage. Lecture seule [FillType](../../com.aspose.slides/filltype).

**Retourne :**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```

Renvoie la couleur d'un remplissage plein. Lecture seule java.awt.Color.

**Retourne :**
java.awt.Color
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

Renvoie le format de remplissage dégradé. Lecture seule [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Retourne :**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

Renvoie le format de remplissage en motif. Lecture seule [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Retourne :**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

Détermine si le remplissage doit être tourné avec une forme. Lecture seule boolean.

**Retourne :**
boolean