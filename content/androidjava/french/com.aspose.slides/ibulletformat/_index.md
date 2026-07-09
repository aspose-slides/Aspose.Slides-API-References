---
title: IBulletFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Représente les propriétés de mise en forme des puces de paragraphe.
type: docs
url: /fr/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

Représente les propriétés de mise en forme des puces de paragraphe.
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
| [getPicture()](#getPicture--) | Renvoie l'image utilisée comme puce dans un paragraphe sans héritage. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Renvoie ou définit le premier numéro utilisé pour le groupe de puces numérotées sans héritage. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Renvoie ou définit le premier numéro utilisé pour le groupe de puces numérotées sans héritage. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Renvoie ou définit le style d'une puce numérotée sans héritage. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Renvoie ou définit le style d'une puce numérotée sans héritage. |
| [isBulletHardColor()](#isBulletHardColor--) | Détermine si la puce possède sa propre couleur ou l'hérite de la première portion du paragraphe. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Détermine si la puce possède sa propre couleur ou l'hérite de la première portion du paragraphe. |
| [isBulletHardFont()](#isBulletHardFont--) | Détermine si la puce possède sa propre police ou l'hérite de la première portion du paragraphe. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Détermine si la puce possède sa propre police ou l'hérite de la première portion du paragraphe. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Définit les décalages non nuls par défaut pour l'Indentation et la marge gauche du paragraphe effectif lorsque les puces sont activées (comme PowerPoint le fait si l'on active les puces/numérotation de paragraphe). |
| [getEffective()](#getEffective--) | Obtient les données de mise en forme de puce effectives avec l'héritage appliqué. |

### getType() {#getType--}
```
public abstract byte getType()
```

Renvoie ou définit le type de puce d'un paragraphe sans héritage. Lecture/écriture [BulletType](../../com.aspose.slides/bullettype).

**Renvoie :**
byte

### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Renvoie ou définit le type de puce d'un paragraphe sans héritage. Lecture/écriture [BulletType](../../com.aspose.slides/bullettype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public abstract char getChar()
```

Renvoie ou définit le caractère de puce d'un paragraphe sans héritage. Lecture/écriture char.

**Renvoie :**
char

### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

Renvoie ou définit le caractère de puce d'un paragraphe sans héritage. Lecture/écriture char.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Renvoie ou définit la police de puce d'un paragraphe sans héritage. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie :**
[IFontData](../../com.aspose.slides/ifontdata)

### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

Renvoie ou définit la police de puce d'un paragraphe sans héritage. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Renvoie ou définit la hauteur de puce d'un paragraphe sans héritage. La valeur Float.NaN indique que la puce hérite de la hauteur de la première portion du paragraphe. Lecture/écriture float.

**Renvoie :**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Renvoie ou définit la hauteur de puce d'un paragraphe sans héritage. La valeur Float.NaN indique que la puce hérite de la hauteur de la première portion du paragraphe. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Renvoie le format de couleur d'une puce d'un paragraphe sans héritage. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Renvoie l'image utilisée comme puce dans un paragraphe sans héritage. Lecture seule [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Renvoie :**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Renvoie ou définit le premier numéro utilisé pour le groupe de puces numérotées sans héritage. Lecture/écriture short.

**Renvoie :**
short

### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

Renvoie ou définit le premier numéro utilisé pour le groupe de puces numérotées sans héritage. Lecture/écriture short.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Renvoie ou définit le style d'une puce numérotée sans héritage. Lecture/écriture [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Renvoie :**
byte

### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

Renvoie ou définit le style d'une puce numérotée sans héritage. Lecture/écriture [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

Détermine si la puce possède sa propre couleur ou l'hérite de la première portion du paragraphe. **NullableBool\#True** si la puce possède sa propre couleur et **NullableBool\#False** si elle hérite de la couleur de la première portion du paragraphe. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte

### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

Détermine si la puce possède sa propre couleur ou l'hérite de la première portion du paragraphe. **NullableBool\#True** si la puce possède sa propre couleur et **NullableBool\#False** si elle hérite de la couleur de la première portion du paragraphe. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

Détermine si la puce possède sa propre police ou l'hérite de la première portion du paragraphe. **NullableBool\#True** si la puce possède sa propre police et **NullableBool\#False** si elle hérite de la police de la première portion du paragraphe. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte

### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

Détermine si la puce possède sa propre police ou l'hérite de la première portion du paragraphe. **NullableBool\#True** si la puce possède sa propre police et **NullableBool\#False** si elle hérite de la police de la première portion du paragraphe. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

Définit les décalages non nuls par défaut pour l'Indentation et la marge gauche du paragraphe effectif lorsque les puces sont activées (comme PowerPoint le fait si l'on active les puces/numérotation de paragraphe). Si les puces sont désactivées, réinitialise simplement l'Indentation et la marge gauche du paragraphe (comme PowerPoint le fait si l'on désactive les puces/numérotation). Les décalages d'indentation sont appliqués en fonction du contexte de la puce actuelle – IBulletFormat.Type, .NumberedBulletStyle et FontHeight de la première portion. Les décalages d'indentation non nuls sont appliqués à l'Indentation et à la marge gauche effectives du paragraphe courant (les valeurs résultantes deviennent des valeurs locales).

### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

Obtient les données de mise en forme de puce effectives avec l'héritage appliqué.

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
>  ```

**Renvoie :**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).