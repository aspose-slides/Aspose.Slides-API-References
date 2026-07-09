---
title: IFillFormatEffectiveData
second_title: Référence de l'API Java pour Aspose.Slides sur Android
description: Objet immuable qui contient les propriétés de formatage de remplissage effectif.
type: docs
url: /fr/com.aspose.slides/ifillformateffectivedata/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Objet immuable qui contient les propriétés de formatage de remplissage effectif.

--------------------

Cette interface est utilisée conjointement avec l'interface [IFillFormat](../../com.aspose.slides/ifillformat) pour renvoyer les valeurs de formatage effectives avec l'héritage appliqué.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Renvoie le type de remplissage. |
| [getSolidFillColor()](#getSolidFillColor--) | Renvoie la couleur de remplissage. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Obtient la couleur de remplissage définie par un jeu de couleurs. |
| [getGradientFormat()](#getGradientFormat--) | Renvoie le format de remplissage en dégradé. |
| [getPatternFormat()](#getPatternFormat--) | Renvoie le format de remplissage en motif. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Renvoie le format de remplissage d'image. |
| [getRotateWithShape()](#getRotateWithShape--) | Détermine si le remplissage doit être pivoté avec la forme. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Renvoie le type de remplissage. Lecture seule [FillType](../../com.aspose.slides/filltype).

**Renvoie :**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


Renvoie la couleur de remplissage. Lecture seule java.lang.Integer.

**Renvoie :**
java.lang.Integer
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


Obtient la couleur de remplissage définie par un jeu de couleurs. La valeur [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) indique que le SolidFillColor (\#getSolidFillColor.getSolidFillColor) n'est pas une couleur de jeu. Lecture seule [SchemeColor](../../com.aspose.slides/schemecolor).

**Renvoie :**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Renvoie le format de remplissage en dégradé. Lecture seule [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Renvoie :**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Renvoie le format de remplissage en motif. Lecture seule [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Renvoie :**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```


Renvoie le format de remplissage d'image. Lecture seule [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Renvoie :**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Détermine si le remplissage doit être pivoté avec la forme. Lecture seule boolean.

**Renvoie :**
boolean