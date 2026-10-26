---
title: ILineFillFormat
second_title: Référence API Java pour Aspose.Slides pour Android
description: Représente les propriétés de remplissage des lignes.
type: docs
url: /fr/com.aspose.slides/ilinefillformat/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

Représente les propriétés de remplissage des lignes.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Renvoie ou définit le type de remplissage. |
| [setFillType(byte value)](#setFillType-byte-) | Renvoie ou définit le type de remplissage. |
| [getSolidFillColor()](#getSolidFillColor--) | Renvoie la couleur d’un remplissage plein. |
| [getGradientFormat()](#getGradientFormat--) | Renvoie le format de remplissage dégradé. |
| [getPatternFormat()](#getPatternFormat--) | Renvoie le format de remplissage à motif. |
| [getRotateWithShape()](#getRotateWithShape--) | Détermine si le remplissage doit être tourné avec une forme. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Détermine si le remplissage doit être tourné avec une forme. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Renvoie ou définit le type de remplissage. Lecture/écriture [FillType](../../com.aspose.slides/filltype).

**Retour:**  
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


Renvoie ou définit le type de remplissage. Lecture/écriture [FillType](../../com.aspose.slides/filltype).

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


Renvoie la couleur d’un remplissage plein. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


Renvoie le format de remplissage dégradé. Lecture seule [IGradientFormat](../../com.aspose.slides/igradientformat).

**Retour:**  
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


Renvoie le format de remplissage à motif. Lecture seule [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Retour:**  
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


Détermine si le remplissage doit être tourné avec une forme. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**  
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


Détermine si le remplissage doit être tourné avec une forme. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |