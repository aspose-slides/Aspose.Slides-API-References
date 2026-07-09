---
title: IFillFormat
second_title: Aspose.Slides pour Android via la référence API Java
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
| [getFillType()](#getFillType--) | Renvoie ou définit le type de remplissage. |
| [setFillType(byte value)](#setFillType-byte-) | Renvoie ou définit le type de remplissage. |
| [getSolidFillColor()](#getSolidFillColor--) | Renvoie la couleur de remplissage. |
| [getGradientFormat()](#getGradientFormat--) | Renvoie le format de remplissage en dégradé. |
| [getPatternFormat()](#getPatternFormat--) | Renvoie le format de remplissage de motif. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Renvoie le format de remplissage d'image. |
| [getRotateWithShape()](#getRotateWithShape--) | Détermine si le remplissage doit être pivoté avec la forme. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Détermine si le remplissage doit être pivoté avec la forme. |
| [getEffective()](#getEffective--) | Obtient les données de formatage de remplissage effectives avec l'héritage appliqué. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Renvoie ou définit le type de remplissage. Lecture/écriture [FillType](../../com.aspose.slides/filltype).

**Renvoie :**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

Renvoie ou définit le type de remplissage. Lecture/écriture [FillType](../../com.aspose.slides/filltype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

Renvoie la couleur de remplissage. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Renvoie le format de remplissage en dégradé. Lecture seule [IGradientFormat](../../com.aspose.slides/igradientformat).

**Renvoie :**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Renvoie le format de remplissage de motif. Lecture seule [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Renvoie :**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

Renvoie le format de remplissage d'image. Lecture seule [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Renvoie :**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Détermine si le remplissage doit être pivoté avec la forme. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
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

**Renvoie :**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - Un [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).