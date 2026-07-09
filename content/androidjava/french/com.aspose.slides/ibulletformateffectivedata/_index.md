---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective paragraph bullet formatting properties.
type: docs
url: /fr/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Objet immuable contenant les propriétés effectives de mise en forme des puces de paragraphe.

--------------------

Cette interface est utilisée comme partie de [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Renvoie le type de puce d'un paragraphe. |
| [getChar()](#getChar--) | Renvoie le caractère de puce d'un paragraphe. |
| [getActualBulletValue()](#getActualBulletValue--) | Renvoie la valeur réelle de la puce pour le paragraphe parent. |
| [getFont()](#getFont--) | Renvoie la police de puce d'un paragraphe. |
| [getHeight()](#getHeight--) | Renvoie la hauteur de la puce d'un paragraphe. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Renvoie le premier numéro utilisé pour le groupe de puces numérotées. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Renvoie le style d'une puce numérotée. |
| [isBulletHardColor()](#isBulletHardColor--) | Détermine si la puce possède sa propre couleur ou l'hérite de la première portion du paragraphe. |
| [isBulletHardFont()](#isBulletHardFont--) | Détermine si la puce possède sa propre police ou l'hérite de la première portion du paragraphe. |
| [getPicture()](#getPicture--) | Renvoie l'image utilisée comme puce dans le paragraphe. |
| [getFillFormat()](#getFillFormat--) | Renvoie le format de remplissage de la puce d'un paragraphe. |
### getType() {#getType--}
```
public abstract byte getType()
```


Renvoie le type de puce d'un paragraphe. Lecture seule [BulletType](../../com.aspose.slides/bullettype).

**Retourne :**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```


Renvoie le caractère de puce d'un paragraphe. Lecture seule char.

**Retourne :**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```


Renvoie la valeur réelle de la puce pour le paragraphe parent. Lecture seule String.

**Retourne :**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Renvoie la police de puce d'un paragraphe. Lecture seule [IFontData](../../com.aspose.slides/ifontdata).

**Retourne :**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Renvoie la hauteur de la puce d'un paragraphe. Lecture seule float.

**Retourne :**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


Renvoie le premier numéro utilisé pour le groupe de puces numérotées. Lecture seule short.

**Retourne :**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Renvoie le style d'une puce numérotée. Lecture seule [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Retourne :**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```


Détermine si la puce possède sa propre couleur ou l'hérite de la première portion du paragraphe. Retourne **true** si la puce a sa propre couleur et **false** si la puce hérite de la couleur de la première portion du paragraphe. Lecture seule boolean.

**Retourne :**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```


Détermine si la puce possède sa propre police ou l'hérite de la première portion du paragraphe. Retourne **true** si la puce a sa propre police et **true** si la puce hérite de la police de la première portion du paragraphe. Lecture seule boolean.

**Retourne :**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Renvoie l'image utilisée comme puce dans le paragraphe. Lecture seule [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Retourne :**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Renvoie le format de remplissage de la puce d'un paragraphe. Lecture seule [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Assume that the first shape on the first slide is AutoShape with some text...
>      // Output information about text paragraphs' bullets
>      AutoShape autoShape = (AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for (IParagraph para : autoShape.getTextFrame().getParagraphs())
>      {
>          IBulletFormatEffectiveData bulletFormatEffective = para.getParagraphFormat().getBullet().getEffective();
>          System.out.println("Bullet type: " + bulletFormatEffective.getType());
>          if (bulletFormatEffective.getType() != BulletType.None)
>          {
>              System.out.println("Bullet fill type: " + bulletFormatEffective.getFillFormat().getFillType());
>              switch (bulletFormatEffective.getFillFormat().getFillType())
>              {
>                  case FillType.Solid:
>                      System.out.println("Solid fill color: " + bulletFormatEffective.getFillFormat().getSolidFillColor());
>                      break;
>                  case FillType.Gradient:
>                      System.out.println("Gradient stops count: " + bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops().size());
>                      for (IGradientStopEffectiveData gradStop : bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops())
>                          System.out.println(gradStop.getPosition() + ": " + gradStop.getColor());
>                      break;
>                  case FillType.Pattern:
>                      System.out.println("Pattern style: " + bulletFormatEffective.getFillFormat().getPatternFormat().getPatternStyle());
>                      System.out.println("Fore color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getForeColor());
>                      System.out.println("Back color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getBackColor());
>                      break;
>              }
>          }
>          System.out.println();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourne :**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)