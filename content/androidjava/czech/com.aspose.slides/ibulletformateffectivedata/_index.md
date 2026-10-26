---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Neměnný objekt, který obsahuje efektivní vlastnosti formátování odrážek odstavce.
type: docs
url: /cs/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Neměnný objekt, který obsahuje efektivní vlastnosti formátování odrážek odstavce.

--------------------

Toto rozhraní se používá jako součást [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Metody

| Metoda | Popis |
| --- | --- |
| [getType()](#getType--) | Vrací typ odrážky odstavce. |
| [getChar()](#getChar--) | Vrací znak odrážky odstavce. |
| [getActualBulletValue()](#getActualBulletValue--) | Vrací skutečnou hodnotu odrážky pro nadřazený odstavec. |
| [getFont()](#getFont--) | Vrací písmo odrážky odstavce. |
| [getHeight()](#getHeight--) | Vrací výšku odrážky odstavce. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Vrací první číslo použité pro skupinu číslovaných odrážek. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Vrací styl číslované odrážky. |
| [isBulletHardColor()](#isBulletHardColor--) | Určuje, zda má odrážka vlastní barvu nebo ji dědí z první části odstavce. |
| [isBulletHardFont()](#isBulletHardFont--) | Určuje, zda má odrážka vlastní písmo nebo je děděno z první části odstavce. |
| [getPicture()](#getPicture--) | Vrací obrázek použitý jako odrážka v odstavci. |
| [getFillFormat()](#getFillFormat--) | Vrací formát výplně odrážky odstavce. |
### getType() {#getType--}
```
public abstract byte getType()
```

Vrací typ odrážky odstavce. Pouze pro čtení [BulletType](../../com.aspose.slides/bullettype).

**Vrací:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```

Vrací znak odrážky odstavce. Pouze pro čtení char.

**Vrací:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```

Vrací skutečnou hodnotu odrážky pro nadřazený odstavec. Pouze pro čtení String.

**Vrací:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Vrací písmo odrážky odstavce. Pouze pro čtení [IFontData](../../com.aspose.slides/ifontdata).

**Vrací:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Vrací výšku odrážky odstavce. Pouze pro čtení float.

**Vrací:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Vrací první číslo použité pro skupinu číslovaných odrážek. Pouze pro čtení short.

**Vrací:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Vrací styl číslované odrážky. Pouze pro čtení [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Vrací:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```

Určuje, zda má odrážka vlastní barvu nebo ji dědí z první části odstavce. Vrací **true**, pokud odrážka má vlastní barvu, a **false**, pokud barvu dědí z první části odstavce. Pouze pro čtení boolean.

**Vrací:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```

Určuje, zda má odrážka vlastní písmo nebo je děděno z první části odstavce. Vrací **true**, pokud odrážka má vlastní písmo, a **true**, pokud písmo dědí z první části odstavce. Pouze pro čtení boolean.

**Vrací:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

Vrací obrázek použitý jako odrážka v odstavci. Pouze pro čtení [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Vrací:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

Vrací formát výplně odrážky odstavce. Pouze pro čtení [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Předpokládejme, že první tvar na první snímku je AutoShape s nějakým textem...
>      // Vypiš informace o odrážkách odstavců textu
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


**Vrací:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)