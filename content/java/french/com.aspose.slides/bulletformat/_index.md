---
title: BulletFormat
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente les propriétés de formatage des puces de paragraphe.
type: docs
url: /fr/com.aspose.slides/bulletformat/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

Représente les propriétés de formatage des puces de paragraphe.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Renvoie ou définit le type de puce d'un paragraphe sans héritage. |
| [setType(byte value)](#setType-byte-) | Renvoie ou définit le type de puce d'un paragraphe sans héritage. |
| [getChar()](#getChar--) | Renvoie ou définit le caractère de puce d'un paragraphe sans héritage. |
| [setChar(char value)](#setChar-char-) | Renvoie ou définit le caractère de puce d'un paragraphe sans héritage. |
| [getFont()](#getFont--) | Renvoie ou définit la police de puce d'un paragraphe sans héritage. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Renvoie ou définit la police de puce d'un paragraphe sans héritage. |
| [getHeight()](#getHeight--) | Renvoie ou définit la hauteur de puce d'un paragraphe sans héritage. |
| [setHeight(float value)](#setHeight-float-) | Renvoie ou définit la hauteur de puce d'un paragraphe sans héritage. |
| [getColor()](#getColor--) | Renvoie le format de couleur d'une puce d'un paragraphe sans héritage. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Renvoie ou définit le premier numéro utilisé pour le groupe de puces numérotées sans héritage. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Renvoie ou définit le premier numéro utilisé pour le groupe de puces numérotées sans héritage. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Renvoie ou définit le style d'une puce numérotée sans héritage. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Renvoie ou définit le style d'une puce numérotée sans héritage. |
| [isBulletHardColor()](#isBulletHardColor--) | Détermine si la puce possède une couleur propre ou l'hérite de la première portion du paragraphe. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Détermine si la puce possède une couleur propre ou l'hérite de la première portion du paragraphe. |
| [isBulletHardFont()](#isBulletHardFont--) | Détermine si la puce possède une police propre ou l'hérite de la première portion du paragraphe. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Détermine si la puce possède une police propre ou l'hérite de la première portion du paragraphe. |
| [getPicture()](#getPicture--) | Renvoie l'image utilisée comme puce dans un paragraphe sans héritage. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Définit les décalages non nuls par défaut pour l'Indent et le MarginLeft effectifs du paragraphe lorsque les puces sont activées (comme PowerPoint le fait lorsqu'on active les puces/numérotation de paragraphe). |
| [getEffective()](#getEffective--) | Obtient les données de formatage de puce effectives avec l'héritage appliqué. |
| [getVersion()](#getVersion--) |  |
### getType() {#getType--}
```
public final byte getType()
```


Renvoie ou définit le type de puce d'un paragraphe sans héritage. Lecture/écriture [BulletType](../../com.aspose.slides/bullettype).

**Retour :**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```


Renvoie ou définit le type de puce d'un paragraphe sans héritage. Lecture/écriture [BulletType](../../com.aspose.slides/bullettype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public final char getChar()
```


Renvoie ou définit le caractère de puce d'un paragraphe sans héritage. Lecture/écriture char .

**Retour :**
char
### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```


Renvoie ou définit le caractère de puce d'un paragraphe sans héritage. Lecture/écriture char .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public final IFontData getFont()
```


Renvoie ou définit la police de puce d'un paragraphe sans héritage. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Retour :**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```


Renvoie ou définit la police de puce d'un paragraphe sans héritage. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Renvoie ou définit la hauteur de puce d'un paragraphe sans héritage. La valeur Float.NaN indique que la puce hérite de la hauteur de la première portion du paragraphe. Lecture/écriture float .

--------------------

Une valeur de hauteur négative signifie que la hauteur est exprimée en points et une valeur positive signifie que la hauteur est un pourcentage du texte environnant.

**Retour :**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Renvoie ou définit la hauteur de puce d'un paragraphe sans héritage. La valeur Float.NaN indique que la puce hérite de la hauteur de la première portion du paragraphe. Lecture/écriture float .

--------------------

Une valeur de hauteur négative signifie que la hauteur est exprimée en points et une valeur positive signifie que la hauteur est un pourcentage du texte environnant.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Renvoie le format de couleur d'une puce d'un paragraphe sans héritage. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```


Renvoie ou définit le premier numéro utilisé pour le groupe de puces numérotées sans héritage. Lecture/écriture short .

**Retour :**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```


Renvoie ou définit le premier numéro utilisé pour le groupe de puces numérotées sans héritage. Lecture/écriture short .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```


Renvoie ou définit le style d'une puce numérotée sans héritage. Lecture/écriture [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Retour :**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```


Renvoie ou définit le style d'une puce numérotée sans héritage. Lecture/écriture [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```


Détermine si la puce possède une couleur propre ou l'hérite de la première portion du paragraphe. **NullableBool.True** si la puce possède une couleur propre et **NullableBool.False** si la puce hérite de la couleur de la première portion du paragraphe. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Retour :**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```


Détermine si la puce possède une couleur propre ou l'hérite de la première portion du paragraphe. **NullableBool.True** si la puce possède une couleur propre et **NullableBool.False** si la puce hérite de la couleur de la première portion du paragraphe. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```


Détermine si la puce possède une police propre ou l'hérite de la première portion du paragraphe. **NullableBool.True** si la puce possède une police propre et **NullableBool.False** si la puce hérite de la police de la première portion du paragraphe. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Retour :**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```


Détermine si la puce possède une police propre ou l'hérite de la première portion du paragraphe. **NullableBool.True** si la puce possède une police propre et **NullableBool.False** si la puce hérite de la police de la première portion du paragraphe. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```


Renvoie l'image utilisée comme puce dans un paragraphe sans héritage. Lecture seule [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Retour :**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```


Définit les décalages non nuls par défaut pour l'Indent et le MarginLeft effectifs du paragraphe lorsque les puces sont activées (comme PowerPoint le fait lorsqu'on active les puces/numérotation de paragraphe). Si les puces sont désactivées, réinitialise simplement l'Indent et le MarginLeft du paragraphe (comme PowerPoint le fait lorsqu'on désactive les puces/numérotation). Les décalages d'indentation sont appliqués en fonction du contexte de puce actuel – IBulletFormat.Type, .NumberedBulletStyle et FontHeight de la première portion. Les décalages d'indentation non nuls sont appliqués à l'Indent et au MarginLeft effectifs du paragraphe actuel (les valeurs résultantes deviennent locales).

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```


Obtient les données de formatage de puce effectives avec l'héritage appliqué.

--------------------

> ```
> This example demonstrates getting some effective bullet format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IBulletFormatEffectiveData effectiveBulletFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getBullet().getEffective();
>      System.out.println("Bullet type: " + effectiveBulletFormat.getType());
>      if (effectiveBulletFormat.getType() == BulletType.Numbered)
>      {
>          System.out.println("Numbered style: " + effectiveBulletFormat.getNumberedBulletStyle());
>          System.out.println("Starting number: " + effectiveBulletFormat.getNumberedBulletStartWith());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retour :**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - Un [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Lecture seule long.

**Retour :**
long