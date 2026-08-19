---
title: ParagraphFormat
second_title: Aspose.Slides för Java API-referens
description: Denna klass innehåller egenskaperna för styckeformatering.
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

Denna klass innehåller egenskaperna för styckeformatering. Till skillnad från [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) är alla egenskaper i den här klassen skrivbara.

--------------------

Denna klass används för att returnera och manipulera styckeformateringsegenskaper som definierats för det specifika stycket. Detta innebär att ingen arv tillämpas när värden hämtas, så i de flesta fall får du värden som betyder "odefinierat".

För att få de effektiva formatparametervärdena inklusive ärvda måste du använda [getEffective](../../com.aspose.slides/paragraphformat\#getEffective)-metoden som returnerar en [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)-instans.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | Initialiserar en ny instans av [ParagraphFormat](../../com.aspose.slides/paragraphformat) klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBullet()](#getBullet--) | Returnerar punktformat för stycket. |
| [getDepth()](#getDepth--) | Returnerar eller anger djupet för stycket. |
| [setDepth(short value)](#setDepth-short-) | Returnerar eller anger djupet för stycket. |
| [getAlignment()](#getAlignment--) | Returnerar eller anger textjusteringen i ett stycke utan arv. |
| [setAlignment(int value)](#setAlignment-int-) | Returnerar eller anger textjusteringen i ett stycke utan arv. |
| [getSpaceWithin()](#getSpaceWithin--) | Returnerar eller anger mängden utrymme mellan baslinjer i ett stycke. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Returnerar eller anger mängden utrymme mellan baslinjer i ett stycke. |
| [getSpaceBefore()](#getSpaceBefore--) | Returnerar eller anger mängden utrymme före den första raden i ett stycke utan arv. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Returnerar eller anger mängden utrymme före den första raden i ett stycke utan arv. |
| [getSpaceAfter()](#getSpaceAfter--) | Returnerar eller anger mängden utrymme efter den sista raden i ett stycke utan arv. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Returnerar eller anger mängden utrymme efter den sista raden i ett stycke utan arv. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Bestämmer om radbrytning för östasiatiskt språk används i ett stycke. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Bestämmer om radbrytning för östasiatiskt språk används i ett stycke. |
| [getRightToLeft()](#getRightToLeft--) | Bestämmer om skrivning från höger till vänster används i ett stycke. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Bestämmer om skrivning från höger till vänster används i ett stycke. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Bestämmer om latinradbrytning används i ett stycke. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Bestämmer om latinradbrytning används i ett stycke. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Bestämmer om hängande interpunktion används i ett stycke. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Bestämmer om hängande interpunktion används i ett stycke. |
| [getMarginLeft()](#getMarginLeft--) | Returnerar eller anger vänstermarginalen i ett stycke utan arv. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Returnerar eller anger vänstermarginalen i ett stycke utan arv. |
| [getMarginRight()](#getMarginRight--) | Returnerar eller anger högermarginalen i ett stycke utan arv. |
| [setMarginRight(float value)](#setMarginRight-float-) | Returnerar eller anger högermarginalen i ett stycke utan arv. |
| [getIndent()](#getIndent--) | Returnerar eller anger styckets första radindrag/hängande indrag utan arv. |
| [setIndent(float value)](#setIndent-float-) | Returnerar eller anger styckets första radindrag/hängande indrag utan arv. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Returnerar eller anger standardtabulatorns storlek utan arv. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Returnerar eller anger standardtabulatorns storlek utan arv. |
| [getTabs()](#getTabs--) | Returnerar tabulatorer för ett stycke. |
| [getFontAlignment()](#getFontAlignment--) | Returnerar eller anger en teckensnittjustering i ett stycke utan arv. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Returnerar eller anger en teckensnittjustering i ett stycke utan arv. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Returnerar standarddelformat för ett stycke. |
| [getEffective()](#getEffective--) | Hämtar effektiva styckeformateringsdata med arv tillämpat. |
| [getVersion()](#getVersion--) |  |

### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

Initialiserar en ny instans av [ParagraphFormat](../../com.aspose.slides/paragraphformat) klass.

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

Returnerar eller anger djupet för stycket. Värde 0 betyder odefinierat värde. Läs/skriv  short .

**Returnerar:**
short
### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

Returnerar eller anger djupet för stycket. Värde 0 betyder odefinierat värde. Läs/skriv  short .

**Parametrar:**
| Parameter | Typ | Beskrivning |
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
>      // Åtkomst till första bilden
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Åtkomst till den första och andra platshållaren i bilden och typkonvertering till AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Ändra texten i båda platshållarna
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Hämtar det första stycket i platshållarna
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Justerar textstycket till mitten
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Skriver presentationen som en PPTX-fil
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```

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
>      // Åtkomst till första bilden
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Åtkomst till den första och andra platshållaren i bilden och typkonvertering till AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Ändra texten i båda platshållarna
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Hämtar det första stycket i platshållarna
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Justerar textstycket till mitten
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Skriver presentationen som en PPTX-fil
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

Returnerar eller anger mängden utrymme mellan baslinjer i ett stycke. Positivt värde betyder procent, negativt - storlek i punkter. Ingen arv tillämpas. Läs/skriv  float .

**Returnerar:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

Returnerar eller anger mängden utrymme mellan baslinjer i ett stycke. Positivt värde betyder procent, negativt - storlek i punkter. Ingen arv tillämpas. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

Returnerar eller anger mängden utrymme före den första raden i ett stycke utan arv. Ett positivt värde anger procentsatsen av teckensnittsstorleken som det vita utrymmet ska vara. Ett negativt värde anger storleken på det vita utrymmet i punktstorlek. Läs/skriv  float .

**Returnerar:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

Returnerar eller anger mängden utrymme före den första raden i ett stycke utan arv. Ett positivt värde anger procentsatsen av teckensnittsstorleken som det vita utrymmet ska vara. Ett negativt värde anger storleken på det vita utrymmet i punktstorlek. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

Returnerar eller anger mängden utrymme efter den sista raden i ett stycke utan arv. Ett positivt värde anger procentsatsen av teckensnittsstorleken som det vita utrymmet ska vara. Ett negativt värde anger storleken på det vita utrymmet i punktstorlek. Läs/skriv  float .

**Returnerar:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

Returnerar eller anger mängden utrymme efter den sista raden i ett stycke utan arv. Ett positivt värde anger procentsatsen av teckensnittsstorleken som det vita utrymmet ska vara. Ett negativt värde anger storleken på det vita utrymmet i punktstorlek. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

Bestämmer om radbrytning för östasiatiskt språk används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

Bestämmer om radbrytning för östasiatiskt språk används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

Bestämmer om skrivning från höger till vänster används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

Bestämmer om skrivning från höger till vänster används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

Bestämmer om latinradbrytning används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

Bestämmer om latinradbrytning används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

Bestämmer om hängande interpunktion används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

Bestämmer om hängande interpunktion används i ett stycke. Ingen arv tillämpas. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```

Returnerar eller anger styckeindrag för första raden/hängande indrag utan arv. Hängande indrag kan definieras med negativa värden. Läs/skriv  float .

**Returnerar:**
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

Returnerar eller anger styckeindrag för första raden/hängande indrag utan arv. Hängande indrag kan definieras med negativa värden. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

Returnerar standarddelformat för ett stycke. Ingen arv tillämpas. Skrivskyddad [IPortionFormat](../../com.aspose.slides/iportionformat).

**Returnerar:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

Hämtar effektiva data för styckeformatering med arv tillämpat.

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