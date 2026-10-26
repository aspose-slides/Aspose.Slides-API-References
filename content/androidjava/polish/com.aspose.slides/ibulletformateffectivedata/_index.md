---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Niezmienny obiekt zawierający efektywne właściwości formatowania wypunktowania akapitu.
type: docs
url: /pl/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Niezmienny obiekt zawierający efektywne właściwości formatowania wypunktowania akapitu.

--------------------

Ten interfejs jest używany jako część [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Metody

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Zwraca typ wypunktowania akapitu. |
| [getChar()](#getChar--) | Zwraca znak wypunktowania akapitu. |
| [getActualBulletValue()](#getActualBulletValue--) | Zwraca rzeczywistą wartość wypunktowania dla nadrzędnego akapitu. |
| [getFont()](#getFont--) | Zwraca czcionkę wypunktowania akapitu. |
| [getHeight()](#getHeight--) | Zwraca wysokość wypunktowania akapitu. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Zwraca pierwszą liczbę używaną dla grupy numerowanych wypunktowań. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Zwraca styl numerowanego wypunktowania. |
| [isBulletHardColor()](#isBulletHardColor--) | Określa, czy wypunktowanie ma własny kolor, czy dziedziczy go z pierwszej części akapitu. |
| [isBulletHardFont()](#isBulletHardFont--) | Określa, czy wypunktowanie ma własną czcionkę, czy dziedziczy ją z pierwszej części akapitu. |
| [getPicture()](#getPicture--) | Zwraca obraz używany jako wypunktowanie w akapicie. |
| [getFillFormat()](#getFillFormat--) | Zwraca format wypełnienia wypunktowania akapitu. |
### getType() {#getType--}
```
public abstract byte getType()
```

Zwraca typ wypunktowania akapitu. Tylko do odczytu [BulletType](../../com.aspose.slides/bullettype).

**Zwraca:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```

Zwraca znak wypunktowania akapitu. Tylko do odczytu char.

**Zwraca:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```

Zwraca rzeczywistą wartość wypunktowania dla nadrzędnego akapitu. Tylko do odczytu String.

**Zwraca:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Zwraca czcionkę wypunktowania akapitu. Tylko do odczytu [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Zwraca wysokość wypunktowania akapitu. Tylko do odczytu float.

**Zwraca:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Zwraca pierwszą liczbę używaną dla grupy numerowanych wypunktowań. Tylko do odczytu short.

**Zwraca:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Zwraca styl numerowanego wypunktowania. Tylko do odczytu [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Zwraca:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```

Określa, czy wypunktowanie ma własny kolor, czy dziedziczy go z pierwszej części akapitu. Zwraca **true**, jeśli wypunktowanie ma własny kolor i **false**, jeśli wypunktowanie dziedziczy kolor z pierwszej części akapitu. Tylko do odczytu boolean.

**Zwraca:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```

Określa, czy wypunktowanie ma własną czcionkę, czy dziedziczy ją z pierwszej części akapitu. Zwraca **true**, jeśli wypunktowanie ma własną czcionkę i **true**, jeśli wypunktowanie dziedziczy czcionkę z pierwszej części akapitu. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

Zwraca obraz używany jako wypunktowanie w akapicie. Tylko do odczytu [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Zwraca:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

Zwraca format wypełnienia wypunktowania akapitu. Tylko do odczytu [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Załóżmy, że pierwszy kształt na pierwszym slajdzie jest AutoShape z pewnym tekstem...
>      // Wypisz informacje o wypunktowaniu akapitów tekstu
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


**Zwraca:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)