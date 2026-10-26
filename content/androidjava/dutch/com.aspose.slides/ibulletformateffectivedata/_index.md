---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Onveranderlijk object dat effectieve alinea-bulletopmaak eigenschappen bevat.
type: docs
url: /nl/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Onveranderlijk object dat effectieve alinea-bulletopmaak eigenschappen bevat.

--------------------

Deze interface wordt gebruikt als onderdeel van [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Retourneert het bullettype van een alinea. |
| [getChar()](#getChar--) | Retourneert het bulletteken van een alinea. |
| [getActualBulletValue()](#getActualBulletValue--) | Retourneert de werkelijke bulletwaarde voor de bovenliggende alinea. |
| [getFont()](#getFont--) | Retourneert het bulletlettertype van een alinea. |
| [getHeight()](#getHeight--) | Retourneert de bullethoogte van een alinea. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Retourneert het eerste nummer dat wordt gebruikt voor een groep genummerde bullets. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Retourneert de stijl van een genummerde bullet. |
| [isBulletHardColor()](#isBulletHardColor--) | Bepaalt of de bullet een eigen kleur heeft of deze erft van het eerste gedeelte in de alinea. |
| [isBulletHardFont()](#isBulletHardFont--) | Bepaalt of de bullet een eigen lettertype heeft of dit erft van het eerste gedeelte in de alinea. |
| [getPicture()](#getPicture--) | Retourneert de afbeelding die als bullet in de alinea wordt gebruikt. |
| [getFillFormat()](#getFillFormat--) | Retourneert het bulletopvulformaat van een alinea. |
### getType() {#getType--}
```
public abstract byte getType()
```


Retourneert het bullettype van een alinea. Alleen-lezen [BulletType](../../com.aspose.slides/bullettype).

**Retourneert:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```


Retourneert het bulletteken van een alinea. Alleen-lezen char.

**Retourneert:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```


Retourneert de werkelijke bulletwaarde voor de bovenliggende alinea. Alleen-lezen String.

**Retourneert:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Retourneert het bulletlettertype van een alinea. Alleen-lezen [IFontData](../../com.aspose.slides/ifontdata).

**Retourneert:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Retourneert de bullethoogte van een alinea. Alleen-lezen float.

**Retourneert:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


Retourneert het eerste nummer dat wordt gebruikt voor een groep genummerde bullets. Alleen-lezen short.

**Retourneert:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Retourneert de stijl van een genummerde bullet. Alleen-lezen [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Retourneert:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```


Bepaalt of de bullet een eigen kleur heeft of deze erft van het eerste gedeelte in de alinea. Retourneert **true** als de bullet een eigen kleur heeft en **false** als de bullet kleur erft van het eerste gedeelte in de alinea. Alleen-lezen boolean.

**Retourneert:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```


Bepaalt of de bullet een eigen lettertype heeft of dit erft van het eerste gedeelte in de alinea. Retourneert **true** als de bullet een eigen lettertype heeft en **true** als de bullet erft van het eerste gedeelte in de alinea. Alleen-lezen boolean.

**Retourneert:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Retourneert de afbeelding die als bullet in de alinea wordt gebruikt. Alleen-lezen [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Retourneert:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Retourneert het bulletopvulformaat van een alinea. Alleen-lezen [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Veronderstel dat de eerste vorm op de eerste dia een AutoShape met enige tekst is...
>      // Geef informatie weer over de bullets van tekstalinea's
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


**Retourneert:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)