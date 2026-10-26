---
title: LineFillFormat
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente les propriétés pour le remplissage des lignes.
type: docs
url: /fr/com.aspose.slides/linefillformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

Représente les propriétés pour le remplissage des lignes.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Renvoie ou définit le type de remplissage. |
| [setFillType(byte value)](#setFillType-byte-) | Renvoie ou définit le type de remplissage. |
| [getRotateWithShape()](#getRotateWithShape--) | Détermine si le remplissage doit être pivoté avec une forme. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Détermine si le remplissage doit être pivoté avec une forme. |
| [getSolidFillColor()](#getSolidFillColor--) | Renvoie la couleur d'un remplissage plein. |
| [getGradientFormat()](#getGradientFormat--) | Renvoie le format de remplissage en dégradé. |
| [getPatternFormat()](#getPatternFormat--) | Renvoie le format de remplissage en motif. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Renvoie:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

Renvoie ou définit le type de remplissage. Lecture/écriture [FillType](../../com.aspose.slides/filltype).

**Renvoie:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

Renvoie ou définit le type de remplissage. Lecture/écriture [FillType](../../com.aspose.slides/filltype).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

Détermine si le remplissage doit être pivoté avec une forme. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

Détermine si le remplissage doit être pivoté avec une forme. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

Renvoie la couleur d'un remplissage plein. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

Renvoie le format de remplissage en dégradé. Lecture seule [IGradientFormat](../../com.aspose.slides/igradientformat).

**Renvoie:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

Renvoie le format de remplissage en motif. Lecture seule [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Renvoie:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)