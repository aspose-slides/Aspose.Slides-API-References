---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective paragraph bullet formatting properties.
type: docs
url: /sv/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Oföränderligt objekt som innehåller effektiva styckepunktformateringsegenskaper.

--------------------

Detta gränssnitt används som en del av [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getType()](#getType--) | Returnerar punktlistans typ för ett stycke. |
| [getChar()](#getChar--) | Returnerar punkttecknet för ett stycke. |
| [getActualBulletValue()](#getActualBulletValue--) | Returnerar det faktiska punktvärdet för förälderstycket. |
| [getFont()](#getFont--) | Returnerar punktens teckensnitt för ett stycke. |
| [getHeight()](#getHeight--) | Returnerar punktens höjd för ett stycke. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Returnerar det första numret som används för en grupp numrerade punkter. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Returnerar stilen för en numrerad punkt. |
| [isBulletHardColor()](#isBulletHardColor--) | Avgör om punkten har egen färg eller ärver den från den första delen i stycket. |
| [isBulletHardFont()](#isBulletHardFont--) | Avgör om punkten har eget teckensnitt eller ärver det från den första delen i stycket. |
| [getPicture()](#getPicture--) | Returnerar bilden som används som punkt i stycket. |
| [getFillFormat()](#getFillFormat--) | Returnerar punktens fyllningsformat för ett stycke. |
### getType() {#getType--}
```
public abstract byte getType()
```

Returnerar punktlistans typ för ett stycke. Skrivskyddad [BulletType](../../com.aspose.slides/bullettype).

**Returnerar:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```

Returnerar punkttecknet för ett stycke. Skrivskyddad char.

**Returnerar:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```

Returnerar det faktiska punktvärdet för förälderstycket. Skrivskyddad String.

**Returnerar:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Returnerar punktens teckensnitt för ett stycke. Skrivskyddad [IFontData](../../com.aspose.slides/ifontdata).

**Returnerar:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Returnerar punktens höjd för ett stycke. Skrivskyddad float.

**Returnerar:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Returnerar det första numret som används för en grupp numrerade punkter. Skrivskyddad short.

**Returnerar:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Returnerar stilen för en numrerad punkt. Skrivskyddad [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Returnerar:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```

Avgör om punkten har egen färg eller ärver den från den första delen i stycket. Returnerar **true** om punkten har egen färg och **false** om punkten ärver färg från den första delen i stycket. Skrivskyddad boolean.

**Returnerar:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```

Avgör om punkten har eget teckensnitt eller ärver det från den första delen i stycket. Returnerar **true** om punkten har eget teckensnitt och **true** om punkten ärver teckensnitt från den första delen i stycket. Skrivskyddad boolean.

**Returnerar:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

Returnerar bilden som används som punkt i stycket. Skrivskyddad [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Returnerar:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

Returnerar punktens fyllningsformat för ett stycke. Skrivskyddad [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Antag att den första formen på den första bilden är AutoShape med någon text...
>      // Skriv ut information om styckeparagrafernas punkter
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


**Returnerar:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)