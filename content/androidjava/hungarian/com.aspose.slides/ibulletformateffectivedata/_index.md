---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides Android számára Java API-referencia
description: Módosíthatatlan objektum, amely hatékony bekezdésjelölő formázási tulajdonságokat tartalmaz.
type: docs
url: /hu/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Módosíthatatlan objektum, amely hatékony bekezdésjelölő formázási tulajdonságokat tartalmaz.

--------------------

Ez a felület a [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) részeként használatos.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getType()](#getType--) | Visszaadja a bekezdés jelölő típusát. |
| [getChar()](#getChar--) | Visszaadja a bekezdés jelölő karakterét. |
| [getActualBulletValue()](#getActualBulletValue--) | Visszaadja a szülő bekezdés tényleges jelölő értékét. |
| [getFont()](#getFont--) | Visszaadja a bekezdés jelölő betűtípusát. |
| [getHeight()](#getHeight--) | Visszaadja a bekezdés jelölő magasságát. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Visszaadja az első számot, amely a számozott jelölők csoportjában használatos. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Visszaadja a számozott jelölő stílusát. |
| [isBulletHardColor()](#isBulletHardColor--) | Meghatározza, hogy a jelölőnek saját színe van-e, vagy a bekezdés első részétől örökli. |
| [isBulletHardFont()](#isBulletHardFont--) | Meghatározza, hogy a jelölőnek saját betűtípusa van-e, vagy a bekezdés első részétől örökli. |
| [getPicture()](#getPicture--) | Visszaadja a bekezdésben jelölőként használt képet. |
| [getFillFormat()](#getFillFormat--) | Visszaadja a bekezdés jelölő kitöltési formátumát. |
### getType() {#getType--}
```
public abstract byte getType()
```


Visszaadja a bekezdés jelölő típusát. Csak olvasható [BulletType](../../com.aspose.slides/bullettype).

**Visszatér:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```


Visszaadja a bekezdés jelölő karakterét. Csak olvasható char.

**Visszatér:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```


Visszaadja a szülő bekezdés tényleges jelölő értékét. Csak olvasható String.

**Visszatér:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Visszaadja a bekezdés jelölő betűtípusát. Csak olvasható [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Visszaadja a bekezdés jelölő magasságát. Csak olvasható float.

**Visszatér:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


Visszaadja az első számot, amely a számozott jelölők csoportjában használatos. Csak olvasható short.

**Visszatér:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Visszaadja a számozott jelölő stílusát. Csak olvasható [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Visszatér:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```


Meghatározza, hogy a jelölőnek saját színe van-e, vagy a bekezdés első részétől örökli. **true** értéket ad vissza, ha a jelölőnek saját színe van, és **false** értéket, ha a jelölő a bekezdés első részétől örökli a színt. Csak olvasható boolean.

**Visszatér:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```


Meghatározza, hogy a jelölőnek saját betűtípusa van-e, vagy a bekezdés első részétől örökli. **true** értéket ad vissza, ha a jelölőnek saját betűtípusa van, és **true** értéket, ha a jelölő a bekezdés első részétől örökli a betűtípust. Csak olvasható boolean.

**Visszatér:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Visszaadja a bekezdésben jelölőként használt képet. Csak olvasható [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Visszatér:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Visszaadja a bekezdés jelölő kitöltési formátumát. Csak olvasható [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

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

**Visszatér:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)