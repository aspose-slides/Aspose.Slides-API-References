---
title: IFillFormat
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente des options de formatage de remplissage.
type: docs
url: /fr/com.aspose.slides/ifillformat/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Représente des options de formatage de remplissage.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Retourne ou définit le type de remplissage. |
| [setFillType(byte value)](#setFillType-byte-) | Retourne ou définit le type de remplissage. |
| [getSolidFillColor()](#getSolidFillColor--) | Retourne la couleur de remplissage. |
| [getGradientFormat()](#getGradientFormat--) | Retourne le format de remplissage en dégradé. |
| [getPatternFormat()](#getPatternFormat--) | Retourne le format de remplissage en motif. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Retourne le format de remplissage d'image. |
| [getRotateWithShape()](#getRotateWithShape--) | Détermine si le remplissage doit être pivoté avec la forme. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Détermine si le remplissage doit être pivoté avec la forme. |
| [getEffective()](#getEffective--) | Obtient les données de formatage de remplissage effectives avec l'héritage appliqué. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Retourne ou définit le type de remplissage. Lecture/écriture [FillType](../../com.aspose.slides/filltype).

**Valeur retournée :**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


Retourne ou définit le type de remplissage. Lecture/écriture [FillType](../../com.aspose.slides/filltype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


Retourne la couleur de remplissage. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Valeur retournée :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


Retourne le format de remplissage en dégradé. Lecture seule [IGradientFormat](../../com.aspose.slides/igradientformat).

**Valeur retournée :**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


Retourne le format de remplissage en motif. Lecture seule [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Valeur retournée :**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```


Retourne le format de remplissage d'image. Lecture seule [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Valeur retournée :**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


Détermine si le remplissage doit être pivoté avec la forme. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Valeur retournée :**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


Détermine si le remplissage doit être pivoté avec la forme. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```


Obtient les données de formatage de remplissage effectives avec l'héritage appliqué.

**Valeur retournée :**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - Un [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).