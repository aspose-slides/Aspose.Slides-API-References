---
title: ParagraphFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Denna klass innehåller styckeformateringsegenskaperna.
type: docs
url: /sv/com.aspose.slides/paragraphformat/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

Denna klass innehåller egenskaperna för styckeformatering. Till skillnad från [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) är alla egenskaper i denna klass skrivbara.

--------------------

Denna klass används för att läsa och manipulera styckeformateringsegenskaper som definierats för det specifika stycket. Det innebär att ingen arv tillämpas när värden hämtas, så i de flesta fall får du värden som betyder "odefinierat".

För att få de effektiva formateringsparametervärdena, inklusive ärvda, måste du använda [getEffective](../../com.aspose.slides/paragraphformat\#getEffective)-metoden som returnerar en [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)-instans.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | Initierar en ny instans av klassen [ParagraphFormat](../../com.aspose.slides/paragraphformat). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBullet()](#getBullet--) | Returnerar punktformat för stycket. |
| [getDepth()](#getDepth--) | Returnerar eller anger djupet på stycket. |
| [setDepth(short value)](#setDepth-short-) | Returnerar eller anger djupet på stycket. |
| [getAlignment()](#getAlignment--) | Returnerar eller anger textjusteringen i ett stycke utan arv. |
| [setAlignment(int value)](#setAlignment-int-) | Returnerar eller anger textjusteringen i ett stycke utan arv. |
| [getSpaceWithin()](#getSpaceWithin--) | Returnerar eller anger mängden utrymme mellan baslinjer i ett stycke. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Returnerar eller anger mängden utrymme mellan baslinjer i ett stycke. |
| [getSpaceBefore()](#getSpaceBefore--) | Returnerar eller anger mängden utrymme före den första raden i ett stycke utan arv. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Returnerar eller anger mängden utrymme före den första raden i ett stycke utan arv. |
| [getSpaceAfter()](#getSpaceAfter--) | Returnerar eller anger mängden utrymme efter den sista raden i ett stycke utan arv. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Returnerar eller anger mängden utrymme efter den sista raden i ett stycke utan arv. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Avgör om den östasiatiska radbrytningen används i ett stycke. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Avgör om den östasiatiska radbrytningen används i ett stycke. |
| [getRightToLeft()](#getRightToLeft--) | Avgör om Right to Left-skrivning används i ett stycke. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Avgör om Right to Left-skrivning används i ett stycke. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Avgör om latinsk radbrytning används i ett stycke. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Avgör om latinsk radbrytning används i ett stycke. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Avgör om hängande interpunktion används i ett stycke. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Avgör om hängande interpunktion används i ett stycke. |
| [getMarginLeft()](#getMarginLeft--) | Returnerar eller anger vänstermarginalen i ett stycke utan arv. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Returnerar eller anger vänstermarginalen i ett stycke utan arv. |
| [getMarginRight()](#getMarginRight--) | Returnerar eller anger högermarginalen i ett stycke utan arv. |
| [setMarginRight(float value)](#setMarginRight-float-) | Returnerar eller anger högermarginalen i ett stycke utan arv. |
| [getIndent()](#getIndent--) | Returnerar eller anger styckets första radindragning/hängande indragning utan arv. |
| [setIndent(float value)](#setIndent-float-) | Returnerar eller anger styckets första radindragning/hängande indragning utan arv. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Returnerar eller anger standardtabulatorns storlek utan arv. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Returnerar eller anger standardtabulatorns storlek utan arv. |
| [getTabs()](#getTabs--) | Returnerar tabulatorer för ett stycke. |
| [getFontAlignment()](#getFontAlignment--) | Returnerar eller anger en teckensnittjustering i ett stycke utan arv. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Returnerar eller anger en teckensnittjustering i ett stycke utan arv. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Returnerar standardavsnittsformat för ett stycke. |
| [getEffective()](#getEffective--) | Hämtar den effektiva styckeformateringsdatan med arv tillämpat. |
| [getVersion()](#getVersion--) |  |
### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

Initierar en ny instans av klassen [ParagraphFormat](../../com.aspose.slides/paragraphformat).

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

Returnerar punktformat för stycket. Skrivskyddad [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Returnerar:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public final short getDepth()
```

Returnerar eller anger djupet på stycket. Värde 0 betyder odefinierat värde. Läs/skriv  short .

**Returnerar:**
short
### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

Returnerar eller anger djupet på stycket. Värde 0 betyder odefinierat värde. Läs/skriv  short .

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Returnerar eller anger textjusteringen i ett stycke utan arv. Läs/skriv [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Skapa ett Presentation-objekt som representerar en PPTX-fil
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Hämtar den första bilden
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Hämtar den första och andra platshållaren i bilden och typkonverterar den till AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Ändra texten i båda platshållarna
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Hämtar första stycket i platshållarna
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Justera textstycket till mitten
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Skriver presentationen som en PPTX-fil
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Returnerar eller anger textjusteringen i ett stycke utan arv. Läs/skriv [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Skapa ett Presentation-objekt som representerar en PPTX-fil
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Hämtar den första bilden
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Hämtar den första och andra platshållaren i bilden och typkonverterar den till AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Ändra texten i båda platshållarna
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Hämtar första stycket i platshållarna
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Justerar textstycket till mitten
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // Skriver presentationen som en PPTX-fil
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

Returnerar eller anger mängden utrymme mellan baslinjer i ett stycke. Positivt värde betyder procent, negativt – storlek i punkter. Ingen arv tillämpas. Läs/skriv  float .

**Returnerar:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

Returnerar eller anger mängden utrymme mellan baslinjer i ett stycke. Positivt värde betyder procent, negativt – storlek i punkter. Ingen arv tillämpas. Läs/skriv  float .

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

Returnerar eller anger mängden utrymme före den första raden i ett stycke utan arv. Ett positivt värde anger procent av teckensnittsstorleken som vitautrymmet ska vara. Ett negativt värde anger storleken på det vita utrymmet i punkter. Läs/skriv  float .

**Returnerar:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

Returnerar eller anger mängden utrymme före den första raden i ett stycke utan arv. Ett positivt värde anger procent av teckensnittsstorleken som vitautrymmet ska vara. Ett negativt värde anger storleken på det vita utrymmet i punkter. Läs/skriv  float .

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

Returnerar eller anger mängden utrymme efter den sista raden i ett stycke utan arv. Ett positivt värde anger procent av teckensnittsstorleken som vitautrymmet ska vara. Ett negativt värde anger storleken på det vita utrymmet i punkter. Läs/skriv  float .

**Returnerar:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

Returnerar eller anger mängden utrymme efter den sista raden i ett stycke utan arv. Ett positivt värde anger procent av teckensnittsstorleken som vitautrymmet ska vara. Ett negativt värde anger storleken på det vita utrymmet i punkter. Läs/skriv  float .

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

Avgör om den östasiatiska radbrytningen används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

Avgör om den östasiatiska radbrytningen används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

Avgör om Right to Left-skrivning används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

Avgör om Right to Left-skrivning används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

Avgör om latinsk radbrytning används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

Avgör om latinsk radbrytning används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

Avgör om hängande interpunktion används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

Avgör om hängande interpunktion används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

Returnerar eller anger vänstermarginalen i ett stycke utan arv. Läs/skriv  float .

**Returnerar:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

Returnerar eller anger vänstermarginalen i ett stycke utan arv. Läs/skriv  float .

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

Returnerar eller anger högermarginalen i ett stycke utan arv. Läs/skriv  float .

**Returnerar:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

Returnerar eller anger högermarginalen i ett stycke utan arv. Läs/skriv  float .

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```

Returnerar eller anger styckets första radindragning/hängande indragning utan arv. Hängande indragning kan definieras med negativa värden. Läs/skriv  float .

**Returnerar:**
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

Returnerar eller anger styckets första radindragning/hängande indragning utan arv. Hängande indragning kan definieras med negativa värden. Läs/skriv  float .

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

Returnerar eller anger standardtabulatorns storlek utan arv. Läs/skriv  float .

**Returnerar:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

Returnerar eller anger standardtabulatorns storlek utan arv. Läs/skriv  float .

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

Returnerar tabulatorer för ett stycke. Ingen arv tillämpas. Skrivskyddad [ITabCollection](../../com.aspose.slides/itabcollection).

**Returnerar:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

Returnerar eller anger en teckensnittjustering i ett stycke utan arv. Läs/skriv [FontAlignment](../../com.aspose.slides/fontalignment).

**Returnerar:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

Returnerar eller anger en teckensnittjustering i ett stycke utan arv. Läs/skriv [FontAlignment](../../com.aspose.slides/fontalignment).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

Returnerar standardavsnittsformat för ett stycke. Ingen arv tillämpas. Skrivskyddad [IPortionFormat](../../com.aspose.slides/iportionformat).

**Returnerar:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

Hämtar den effektiva styckeformateringsdatan med arv tillämpat.

--------------------

> ```
> This example demonstrates getting some effective paragraph format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getEffective();
>  	System.out.println("Text alignment: " + effectiveParagraphFormat.getAlignment());
>  	System.out.println("Indent: " + effectiveParagraphFormat.getIndent());
>  	System.out.println("Bullet type: " + effectiveParagraphFormat.getBullet().getType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Skrivskyddad long.

**Returnerar:**
long