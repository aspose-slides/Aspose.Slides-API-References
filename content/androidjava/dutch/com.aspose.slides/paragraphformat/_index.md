---
title: ParagraphFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Deze klasse bevat de alinea-opmaak eigenschappen.
type: docs
url: /nl/com.aspose.slides/paragraphformat/
---
**Overerving:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

Deze klasse bevat de alinea-opmaak eigenschappen. In tegenstelling tot [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) zijn alle eigenschappen van deze klasse schrijfbaar.

--------------------

Deze klasse wordt gebruikt om alinea-opmaak eigenschappen terug te geven en te manipuleren die zijn gedefinieerd voor de specifieke alinea. Dit betekent dat er geen erfelijkheid wordt toegepast bij het ophalen van waarden, dus in de meeste gevallen krijg je waarden die "onbepaald" betekenen.

Om de effectieve opmaakparameterwaarden, inclusief geërfde, te verkrijgen, moet je de [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) methode gebruiken die een [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) instantie retourneert.

## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | Initialiseert een nieuw exemplaar van de [ParagraphFormat](../../com.aspose.slides/paragraphformat) klasse. |

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBullet()](#getBullet--) | Retourneert het opsommingstekenformaat van de alinea. |
| [getDepth()](#getDepth--) | Retourneert of stelt de diepte van de alinea in. |
| [setDepth(short value)](#setDepth-short-) | Retourneert of stelt de diepte van de alinea in. |
| [getAlignment()](#getAlignment--) | Retourneert of stelt de tekstuitlijning in een alinea in zonder erfelijkheid. |
| [setAlignment(int value)](#setAlignment-int-) | Retourneert of stelt de tekstuitlijning in een alinea in zonder erfelijkheid. |
| [getSpaceWithin()](#getSpaceWithin--) | Retourneert of stelt de hoeveelheid ruimte tussen basisregels in een alinea in. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Retourneert of stelt de hoeveelheid ruimte tussen basisregels in een alinea in. |
| [getSpaceBefore()](#getSpaceBefore--) | Retourneert of stelt de hoeveelheid ruimte vóór de eerste regel in een alinea in zonder erfelijkheid. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Retourneert of stelt de hoeveelheid ruimte vóór de eerste regel in een alinea in zonder erfelijkheid. |
| [getSpaceAfter()](#getSpaceAfter--) | Retourneert of stelt de hoeveelheid ruimte na de laatste regel in een alinea in zonder erfelijkheid. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Retourneert of stelt de hoeveelheid ruimte na de laatste regel in een alinea in zonder erfelijkheid. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Bepaalt of de oost-Aziatische regeleinde wordt gebruikt in een alinea. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Bepaalt of de oost-Aziatische regeleinde wordt gebruikt in een alinea. |
| [getRightToLeft()](#getRightToLeft--) | Bepaalt of van rechts naar links schrijven wordt gebruikt in een alinea. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Bepaalt of van rechts naar links schrijven wordt gebruikt in een alinea. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Bepaalt of de Latijnse regeleinde wordt gebruikt in een alinea. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Bepaalt of de Latijnse regeleinde wordt gebruikt in een alinea. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Bepaalt of hangende interpunctie wordt gebruikt in een alinea. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Bepaalt of hangende interpunctie wordt gebruikt in een alinea. |
| [getMarginLeft()](#getMarginLeft--) | Retourneert of stelt de linkermarge in een alinea in zonder erfelijkheid. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Retourneert of stelt de linkermarge in een alinea in zonder erfelijkheid. |
| [getMarginRight()](#getMarginRight--) | Retourneert of stelt de rechtermarge in een alinea in zonder erfelijkheid. |
| [setMarginRight(float value)](#setMarginRight-float-) | Retourneert of stelt de rechtermarge in een alinea in zonder erfelijkheid. |
| [getIndent()](#getIndent--) | Retourneert of stelt de eerste regel-inspringing/hangende inspringing van de alinea in zonder erfelijkheid. |
| [setIndent(float value)](#setIndent-float-) | Retourneert of stelt de eerste regel-inspringing/hangende inspringing van de alinea in zonder erfelijkheid. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Retourneert of stelt de standaard tabulatiegrootte in zonder erfelijkheid. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Retourneert of stelt de standaard tabulatiegrootte in zonder erfelijkheid. |
| [getTabs()](#getTabs--) | Retourneert tabulaties van een alinea. |
| [getFontAlignment()](#getFontAlignment--) | Retourneert of stelt een lettertype-uitlijning in een alinea in zonder erfelijkheid. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Retourneert of stelt een lettertype-uitlijning in een alinea in zonder erfelijkheid. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Retourneert het standaard gedeelteformaat van een alinea. |
| [getEffective()](#getEffective--) | Haalt effectieve alinea-opmaakgegevens op met de toegepaste erfelijkheid. |
| [getVersion()](#getVersion--) |  |

### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

Initialiseert een nieuw exemplaar van de [ParagraphFormat](../../com.aspose.slides/paragraphformat) klasse.

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

Retourneert het opsommingstekenformaat van de alinea. Alleen-lezen [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Retourneert:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public final short getDepth()
```

Retourneert of stelt de diepte van de alinea in. Waarde 0 betekent ongedefinieerde waarde. Lezen/schrijven short.

**Retourneert:**
short

### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

Retourneert of stelt de diepte van de alinea in. Waarde 0 betekent ongedefinieerde waarde. Lezen/schrijven short.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Retourneert of stelt de tekstuitlijning in een alinea in zonder erfelijkheid. Lezen/schrijven [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Instantieer een Presentation-object dat een PPTX-bestand vertegenwoordigt
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Toegang tot eerste dia
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Toegang tot de eerste en tweede placeholder op de dia en casting als AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Verander de tekst in beide placeholders
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Verkrijgen van de eerste alinea van de placeholders
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Uitlijnen van de tekst alinea naar het midden
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // Schrijf de presentatie als een PPTX-bestand
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Retourneert of stelt de tekstuitlijning in een alinea in zonder erfelijkheid. Lezen/schrijven [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Instantieer een Presentation-object dat een PPTX-bestand vertegenwoordigt
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Toegang tot eerste dia
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Toegang tot de eerste en tweede placeholder op de dia en het casten als AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Verander de tekst in beide placeholders
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Verkrijgen van de eerste alinea van de placeholders
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Uitlijnen van de tekst alinea naar het midden
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Writing de presentatie als een PPTX-bestand
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

Retourneert of stelt de hoeveelheid ruimte tussen basisregels in een alinea in. Positieve waarde betekent percentage, negatieve – grootte in punten. Geen erfelijkheid toegepast. Lezen/schrijven float.

**Retourneert:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

Retourneert of stelt de hoeveelheid ruimte tussen basisregels in een alinea in. Positieve waarde betekent percentage, negatieve – grootte in punten. Geen erfelijkheid toegepast. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

Retourneert of stelt de hoeveelheid ruimte vóór de eerste regel in een alinea in zonder erfelijkheid. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witruimte moet bedragen. Een negatieve waarde geeft de grootte van de witruimte in punten aan. Lezen/schrijven float.

**Retourneert:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

Retourneert of stelt de hoeveelheid ruimte vóór de eerste regel in een alinea in zonder erfelijkheid. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witruimte moet bedragen. Een negatieve waarde geeft de grootte van de witruimte in punten aan. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

Retourneert of stelt de hoeveelheid ruimte na de laatste regel in een alinea in zonder erfelijkheid. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witruimte moet bedragen. Een negatieve waarde geeft de grootte van de witruimte in punten aan. Lezen/schrijven float.

**Retourneert:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

Retourneert of stelt de hoeveelheid ruimte na de laatste regel in een alinea in zonder erfelijkheid. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witruimte moet bedragen. Een negatieve waarde geeft de grootte van de witruimte in punten aan. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

Bepaalt of de oost-Aziatische regeleinde wordt gebruikt in een alinea. Geen erfelijkheid toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

Bepaalt of de oost-Aziatische regeleinde wordt gebruikt in een alinea. Geen erfelijkheid toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

Bepaalt of van rechts naar links schrijven wordt gebruikt in een alinea. Geen erfelijkheid toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

Bepaalt of van rechts naar links schrijven wordt gebruikt in een alinea. Geen erfelijkheid toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

Bepaalt of de Latijnse regeleinde wordt gebruikt in een alinea. Geen erfelijkheid toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

Bepaalt of de Latijnse regeleinde wordt gebruikt in een alinea. Geen erfelijkheid toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

Bepaalt of hangende interpunctie wordt gebruikt in een alinea. Geen erfelijkheid toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

Bepaalt of hangende interpunctie wordt gebruikt in een alinea. Geen erfelijkheid toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

Retourneert of stelt de linkermarge in een alinea in zonder erfelijkheid. Lezen/schrijven float.

**Retourneert:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

Retourneert of stelt de linkermarge in een alinea in zonder erfelijkheid. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

Retourneert of stelt de rechtermarge in een alinea in zonder erfelijkheid. Lezen/schrijven float.

**Retourneert:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

Retourneert of stelt de rechtermarge in een alinea in zonder erfelijkheid. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```

Retourneert of stelt de eerste regel-inspringing/hangende inspringing van de alinea in zonder erfelijkheid. Hangende inspringing kan worden gedefinieerd met negatieve waarden. Lezen/schrijven float.

**Retourneert:**
float

### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

Retourneert of stelt de eerste regel-inspringing/hangende inspringing van de alinea in zonder erfelijkheid. Hangende inspringing kan worden gedefinieerd met negatieve waarden. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

Retourneert of stelt de standaard tabulatiegrootte in zonder erfelijkheid. Lezen/schrijven float.

**Retourneert:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

Retourneert of stelt de standaard tabulatiegrootte in zonder erfelijkheid. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

Retourneert tabulaties van een alinea. Geen erfelijkheid toegepast. Alleen-lezen [ITabCollection](../../com.aspose.slides/itabcollection).

**Retourneert:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

Retourneert of stelt een lettertype-uitlijning in een alinea in zonder erfelijkheid. Lezen/schrijven [FontAlignment](../../com.aspose.slides/fontalignment).

**Retourneert:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

Retourneert of stelt een lettertype-uitlijning in een alinea in zonder erfelijkheid. Lezen/schrijven [FontAlignment](../../com.aspose.slides/fontalignment).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

Retourneert het standaard gedeelteformaat van een alinea. Geen erfelijkheid toegepast. Alleen-lezen [IPortionFormat](../../com.aspose.slides/iportionformat).

**Retourneert:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

Haalt effectieve alinea-opmaakgegevens op met de toegepaste erfelijkheid.

--------------------

> ```
> Dit voorbeeld demonstreert het ophalen van enkele effectieve alinea-opmaak eigenschappen.
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


**Retourneert:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versie. Alleen-lezen long.

**Retourneert:**
long