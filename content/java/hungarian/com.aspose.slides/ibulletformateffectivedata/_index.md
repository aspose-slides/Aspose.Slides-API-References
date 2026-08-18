---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective paragraph bullet formatting properties.
type: docs
url: /hu/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Az immutable (változtathatatlan) objektum, amely a bekezdés golyó formázási tulajdonságait tartalmazza.

--------------------

Ez a felület a [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) részeként használható.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getType()](#getType--) | Visszatér a bekezdés golyó típusával. |
| [getChar()](#getChar--) | Visszatér a bekezdés golyó karakterével. |
| [getActualBulletValue()](#getActualBulletValue--) | Visszatér a szülő bekezdés tényleges golyó értékével. |
| [getFont()](#getFont--) | Visszatér a bekezdés golyó betűtípusával. |
| [getHeight()](#getHeight--) | Visszatér a bekezdés golyó magasságával. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Visszatér az első számmal, amely a számozott golyók csoportjához használatos. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Visszatér a számozott golyó stílusával. |
| [isBulletHardColor()](#isBulletHardColor--) | Meghatározza, hogy a golyó saját színnel rendelkezik-e vagy az első részlet színét örökli a bekezdésben. |
| [isBulletHardFont()](#isBulletHardFont--) | Meghatározza, hogy a golyó saját betűtípussal rendelkezik-e vagy az első részlet betűtípusát örökli a bekezdésben. |
| [getPicture()](#getPicture--) | Visszatér a bekezdésben golyóként használt képpel. |
| [getFillFormat()](#getFillFormat--) | Visszatér a bekezdés golyó kitöltésformátumával. |
### getType() {#getType--}
```
public abstract byte getType()
```


Visszatér a bekezdés golyó típusával. Csak olvasható [BulletType](../../com.aspose.slides/bullettype).

**Visszatér:**  
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```


Visszatér a bekezdés golyó karakterével. Csak olvasható char.

**Visszatér:**  
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```


Visszatér a szülő bekezdés tényleges golyó értékével. Csak olvasható String.

**Visszatér:**  
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Visszatér a bekezdés golyó betűtípusával. Csak olvasható [IFontData](../../com.aspose.slides/ifontdata).

**Visszatér:**  
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Visszatér a bekezdés golyó magasságával. Csak olvasható float.

**Visszatér:**  
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


Visszatér az első számmal, amely a számozott golyók csoportjához használatos. Csak olvasható short.

**Visszatér:**  
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Visszatér a számozott golyó stílusával. Csak olvasható [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Visszatér:**  
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```


Meghatározza, hogy a golyó saját színnel rendelkezik-e vagy az első részlet színét örökli a bekezdésben. Visszatér **true**, ha a golyó saját színnel rendelkezik, és **false**, ha a golyó az első részlet színét örökli. Csak olvasható boolean.

**Visszatér:**  
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```


Meghatározza, hogy a golyó saját betűtípussal rendelkezik-e vagy az első részlet betűtípusát örökli a bekezdésben. Visszatér **true**, ha a golyó saját betűtípussal rendelkezik, és **true**, ha a golyó az első részlet betűtípusát örökli. Csak olvasható boolean.

**Visszatér:**  
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Visszatér a bekezdésben golyóként használt képpel. Csak olvasható [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Visszatér:**  
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Visszatér a bekezdés golyó kitöltésformátumával. Csak olvasható [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Feltételezzük, hogy az első dián az első alakzat AutoShape némi szöveggel rendelkezik...
>      // Kiírja a szöveges bekezdések golyóiról szóló információkat
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