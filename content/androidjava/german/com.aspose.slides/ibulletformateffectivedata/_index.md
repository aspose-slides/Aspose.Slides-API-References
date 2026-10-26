---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Unveränderliches Objekt, das effektive Absatz-Aufzählungsformatierungseigenschaften enthält.
type: docs
url: /de/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Unveränderliches Objekt, das effektive Absatz-Aufzählungsformatierungseigenschaften enthält.

--------------------

Dieses Interface wird als Teil von [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) verwendet.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Gibt den Aufzählungstyp eines Absatzes zurück. |
| [getChar()](#getChar--) | Gibt das Aufzählungszeichen eines Absatzes zurück. |
| [getActualBulletValue()](#getActualBulletValue--) | Gibt den tatsächlichen Aufzählungswert für den übergeordneten Absatz zurück. |
| [getFont()](#getFont--) | Gibt die Aufzählungsschriftart eines Absatzes zurück. |
| [getHeight()](#getHeight--) | Gibt die Aufzählungshöhe eines Absatzes zurück. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Gibt die erste Zahl zurück, die für eine Gruppe nummerierter Aufzählungszeichen verwendet wird. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Gibt den Stil einer nummerierten Aufzählung zurück. |
| [isBulletHardColor()](#isBulletHardColor--) | Bestimmt, ob die Aufzählung eine eigene Farbe hat oder sie vom ersten Abschnitt im Absatz erbt. |
| [isBulletHardFont()](#isBulletHardFont--) | Bestimmt, ob die Aufzählung eine eigene Schriftart hat oder sie vom ersten Abschnitt im Absatz erbt. |
| [getPicture()](#getPicture--) | Gibt das Bild zurück, das im Absatz als Aufzählung verwendet wird. |
| [getFillFormat()](#getFillFormat--) | Gibt das Füllformat der Aufzählung eines Absatzes zurück. |
### getType() {#getType--}
```
public abstract byte getType()
```

Gibt den Aufzählungstyp eines Absatzes zurück. Nur lesbar [BulletType](../../com.aspose.slides/bullettype).

**Rückgabe:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```

Gibt das Aufzählungszeichen eines Absatzes zurück. Nur lesbar char.

**Rückgabe:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```

Gibt den tatsächlichen Aufzählungswert für den übergeordneten Absatz zurück. Nur lesbar String.

**Rückgabe:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Gibt die Aufzählungsschriftart eines Absatzes zurück. Nur lesbar [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Gibt die Aufzählungshöhe eines Absatzes zurück. Nur lesbar float.

**Rückgabe:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Gibt die erste Zahl zurück, die für eine Gruppe nummerierter Aufzählungszeichen verwendet wird. Nur lesbar short.

**Rückgabe:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Gibt den Stil einer nummerierten Aufzählung zurück. Nur lesbar [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Rückgabe:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```

Bestimmt, ob die Aufzählung eine eigene Farbe hat oder sie vom ersten Abschnitt im Absatz erbt. Gibt **true** zurück, wenn die Aufzählung eine eigene Farbe hat und **false**, wenn die Aufzählung die Farbe vom ersten Abschnitt im Absatz erbt. Nur lesbar boolean.

**Rückgabe:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```

Bestimmt, ob die Aufzählung eine eigene Schriftart hat oder sie vom ersten Abschnitt im Absatz erbt. Gibt **true** zurück, wenn die Aufzählung eine eigene Schriftart hat und **true**, wenn die Aufzählung die Schriftart vom ersten Abschnitt im Absatz erbt. Nur lesbar boolean.

**Rückgabe:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

Gibt das Bild zurück, das im Absatz als Aufzählung verwendet wird. Nur lesbar [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Rückgabe:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

Gibt das Füllformat der Aufzählung eines Absatzes zurück. Nur lesbar [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Angenommen, das erste Shape auf der ersten Folie ist ein AutoShape mit etwas Text...
>      // Ausgabe von Informationen über die Aufzählungen der Textabsätze
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


**Rückgabe:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)