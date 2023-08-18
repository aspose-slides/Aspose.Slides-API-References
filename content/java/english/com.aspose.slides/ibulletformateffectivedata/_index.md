---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective paragraph bullet formatting properties.
type: docs
url: /com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Immutable object which contains effective paragraph bullet formatting properties.

--------------------

This interface is used as a part of [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Returns the bullet type of a paragraph. |
| [getChar()](#getChar--) | Returns the bullet char of a paragraph. |
| [getActualBulletValue()](#getActualBulletValue--) | Returns actual bullet value for parent paragraph. |
| [getFont()](#getFont--) | Returns the bullet font of a paragraph. |
| [getHeight()](#getHeight--) | Returns the bullet height of a paragraph. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Returns the first number which is used for group of numbered bullets. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Returns the style of a numbered bullet. |
| [getColor()](#getColor--) | Returns the color of a bullet. |
| [isBulletHardColor()](#isBulletHardColor--) | Determines whether the bullet has own color or inherits it from the first portion in the paragraph. |
| [isBulletHardFont()](#isBulletHardFont--) | Determines whether the bullet has own font or inherits it from the first portion in the paragraph. |
| [getPicture()](#getPicture--) | Returns the picture used as a bullet in the paragraph. |
| [getFillFormat()](#getFillFormat--) | Returns the bullet fill format of a paragraph. |
### getType() {#getType--}
```
public abstract byte getType()
```


Returns the bullet type of a paragraph. Read-only [BulletType](../../com.aspose.slides/bullettype).

**Returns:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```


Returns the bullet char of a paragraph. Read-only char.

**Returns:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```


Returns actual bullet value for parent paragraph. Read-only String.

**Returns:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Returns the bullet font of a paragraph. Read-only [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Returns the bullet height of a paragraph. Read-only float.

**Returns:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


Returns the first number which is used for group of numbered bullets. Read-only short.

**Returns:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Returns the style of a numbered bullet. Read-only [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Returns:**
byte
### getColor() {#getColor--}
```
public abstract Color getColor()
```


Returns the color of a bullet. Read-only Color(\#getColor.getColor).

**Returns:**
java.awt.Color
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```


Determines whether the bullet has own color or inherits it from the first portion in the paragraph. Returns **true** if bullet has own color and **false** if bullet inherits color from the first portion in the paragraph. Read-only boolean.

**Returns:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```


Determines whether the bullet has own font or inherits it from the first portion in the paragraph. Returns **true** if bullet has own font and **true** if bullet inherits font from the first portion in the paragraph. Read-only boolean.

**Returns:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Returns the picture used as a bullet in the paragraph. Read-only [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Returns:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Returns the bullet fill format of a paragraph. Read-only [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

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

**Returns:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
