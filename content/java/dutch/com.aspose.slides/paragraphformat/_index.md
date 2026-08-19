---
title: ParagraphFormat
second_title: Aspose.Slides voor Java API-referentie
description: Deze klasse bevat de alinea-opmaak eigenschappen.
type: docs
url: /nl/com.aspose.slides/paragraphformat/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

Deze klasse bevat de alinea-opmaak eigenschappen. In tegenstelling tot [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) zijn alle eigenschappen van deze klasse schrijfbaar.

--------------------

Deze klasse wordt gebruikt om alinea-opmaak eigenschappen op te halen en te manipuleren die gedefinieerd zijn voor de specifieke alinea. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, zodat u in de meeste gevallen waarden krijgt die "onbepaald" betekenen.

Om de effectieve opmaakparameterwaarden, inclusief geërfde, te verkrijgen, moet u de [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) methode gebruiken die een [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) instantie retourneert.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | Initialiseert een nieuw exemplaar van de klasse [ParagraphFormat](../../com.aspose.slides/paragraphformat). |
## Methods

| Methode | Beschrijving |
| --- | --- |
| [getBullet()](#getBullet--) | Retourneert het opsommingstekenformaat van de alinea. |
| [getDepth()](#getDepth--) | Retourneert of stelt de diepte van de alinea in. |
| [setDepth(short value)](#setDepth-short-) | Retourneert of stelt de diepte van de alinea in. |
| [getAlignment()](#getAlignment--) | Retourneert of stelt de tekstuitlijning in een alinea zonder overerving in. |
| [setAlignment(int value)](#setAlignment-int-) | Retourneert of stelt de tekstuitlijning in een alinea zonder overerving in. |
| [getSpaceWithin()](#getSpaceWithin--) | Retourneert of stelt de hoeveelheid ruimte tussen basislijnen in een alinea in. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Retourneert of stelt de hoeveelheid ruimte tussen basislijnen in een alinea in. |
| [getSpaceBefore()](#getSpaceBefore--) | Retourneert of stelt de hoeveelheid ruimte vóór de eerste regel in een alinea zonder overerving in. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Retourneert of stelt de hoeveelheid ruimte vóór de eerste regel in een alinea zonder overerving in. |
| [getSpaceAfter()](#getSpaceAfter--) | Retourneert of stelt de hoeveelheid ruimte na de laatste regel in een alinea zonder overerving in. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Retourneert of stelt de hoeveelheid ruimte na de laatste regel in een alinea zonder overerving in. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Bepaalt of de oost-Aziatische regelafbreking in een alinea wordt gebruikt. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Bepaalt of de oost-Aziatische regelafbreking in een alinea wordt gebruikt. |
| [getRightToLeft()](#getRightToLeft--) | Bepaalt of de rechts-naar-links schrijfstijl in een alinea wordt gebruikt. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Bepaalt of de rechts-naar-links schrijfstijl in een alinea wordt gebruikt. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Bepaalt of de Latijnse regelafbreking in een alinea wordt gebruikt. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Bepaalt of de Latijnse regelafbreking in een alinea wordt gebruikt. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Bepaalt of de hangende interpunctie in een alinea wordt gebruikt. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Bepaalt of de hangende interpunctie in een alinea wordt gebruikt. |
| [getMarginLeft()](#getMarginLeft--) | Retourneert of stelt de linkermarge in een alinea zonder overerving in. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Retourneert of stelt de linkermarge in een alinea zonder overerving in. |
| [getMarginRight()](#getMarginRight--) | Retourneert of stelt de rechtermarge in een alinea zonder overerving in. |
| [setMarginRight(float value)](#setMarginRight-float-) | Retourneert of stelt de rechtermarge in een alinea zonder overerving in. |
| [getIndent()](#getIndent--) | Retourneert of stelt de eerste regelinspringing/hangende inspringing van de alinea in zonder overerving. |
| [setIndent(float value)](#setIndent-float-) | Retourneert of stelt de eerste regelinspringing/hangende inspringing van de alinea in zonder overerving. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Retourneert of stelt de standaard tabulatiegrootte in zonder overerving. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Retourneert of stelt de standaard tabulatiegrootte in zonder overerving. |
| [getTabs()](#getTabs--) | Retourneert tabulaties van een alinea. |
| [getFontAlignment()](#getFontAlignment--) | Retourneert of stelt een lettertype-uitlijning in een alinea zonder overerving in. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Retourneert of stelt een lettertype-uitlijning in een alinea zonder overerving in. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Retourneert het standaardgedeelteformaat van een alinea. |
| [getEffective()](#getEffective--) | Haalt de effectieve alinea-opmaakgegevens op met de toegepaste overerving. |
| [getVersion()](#getVersion--) |  |
### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```


Initialiseert een nieuw exemplaar van de klasse [ParagraphFormat](../../com.aspose.slides/paragraphformat).

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```


Retourneert het opsommingstekenformaat van de alinea. Alleen-lezen [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Retour:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public final short getDepth()
```


Retourneert of stelt de diepte van de alinea in. Waarde 0 betekent een ongedefinieerde waarde. Lezen/schrijven short.

**Retour:**
short
### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```


Retourneert of stelt de diepte van de alinea in. Waarde 0 betekent een ongedefinieerde waarde. Lezen/schrijven short.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Retourneert of stelt de tekstuitlijning in een alinea zonder overerving in. Lezen/schrijven [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Instantieer een Presentation-object dat een PPTX-bestand vertegenwoordigt
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Toegang tot eerste dia
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Toegang tot de eerste en tweede placeholder in de dia en typecasten naar AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Wijzig de tekst in beide placeholders
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Het eerste alinea van de placeholders ophalen
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // De tekstalinea centreren
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //De presentatie opslaan als PPTX-bestand
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retour:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Retourneert of stelt de tekstuitlijning in een alinea zonder overerving in. Lezen/schrijven [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Instantieer een Presentation-object dat een PPTX-bestand vertegenwoordigt
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Toegang tot eerste dia
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Toegang tot de eerste en tweede placeholder in de dia en deze typecasten naar AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Wijzig de tekst in beide placeholders
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Het eerste alinea van de placeholders ophalen
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // De tekstalinea centreren
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // De presentatie opslaan als PPTX-bestand
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


Retourneert of stelt de hoeveelheid ruimte tussen basislijnen in een alinea. Positieve waarde betekent percentage, negatieve - grootte in punten. Geen overerving toegepast. Lezen/schrijven float.

**Retour:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```


Retourneert of stelt de hoeveelheid ruimte tussen basislijnen in een alinea. Positieve waarde betekent percentage, negatieve - grootte in punten. Geen overerving toegepast. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```


Retourneert of stelt de hoeveelheid ruimte vóór de eerste regel in een alinea zonder overerving in. Een positieve waarde specificeert het percentage van de lettergrootte dat de lege ruimte moet zijn. Een negatieve waarde specificeert de grootte van de lege ruimte in punten. Lezen/schrijven float.

**Retour:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```


Retourneert of stelt de hoeveelheid ruimte vóór de eerste regel in een alinea zonder overerving in. Een positieve waarde specificeert het percentage van de lettergrootte dat de lege ruimte moet zijn. Een negatieve waarde specificeert de grootte van de lege ruimte in punten. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```


Retourneert of stelt de hoeveelheid ruimte na de laatste regel in een alinea zonder overerving in. Een positieve waarde specificeert het percentage van de lettergrootte dat de lege ruimte moet zijn. Een negatieve waarde specificeert de grootte van de lege ruimte in punten. Lezen/schrijven float.

**Retour:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```


Retourneert of stelt de hoeveelheid ruimte na de laatste regel in een alinea zonder overerving in. Een positieve waarde specificeert het percentage van de lettergrootte dat de lege ruimte moet zijn. Een negatieve waarde specificeert de grootte van de lege ruimte in punten. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```


Bepaalt of de oost-Aziatische regelafbreking in een alinea wordt gebruikt. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```


Bepaalt of de oost-Aziatische regelafbreking in een alinea wordt gebruikt. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```


Bepaalt of de rechts-naar-links schrijfstijl in een alinea wordt gebruikt. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```


Bepaalt of de rechts-naar-links schrijfstijl in een alinea wordt gebruikt. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```


Bepaalt of de Latijnse regelafbreking in een alinea wordt gebruikt. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```


Bepaalt of de Latijnse regelafbreking in een alinea wordt gebruikt. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```


Bepaalt of de hangende interpunctie in een alinea wordt gebruikt. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```


Bepaalt of de hangende interpunctie in een alinea wordt gebruikt. Geen overerving toegepast. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


Retourneert of stelt de linkermarge in een alinea zonder overerving in. Lezen/schrijven float.

**Retour:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


Retourneert of stelt de linkermarge in een alinea zonder overerving in. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


Retourneert of stelt de rechtermarge in een alinea zonder overerving in. Lezen/schrijven float.

**Retour:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


Retourneert of stelt de rechtermarge in een alinea zonder overerving in. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```


Retourneert of stelt de eerste regelinspringing/hangende inspringing van de alinea in zonder overerving. Hangende inspringing kan met negatieve waarden worden gedefinieerd. Lezen/schrijven float.

**Retour:**
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```


Retourneert of stelt de eerste regelinspringing/hangende inspringing van de alinea in zonder overerving. Hangende inspringing kan met negatieve waarden worden gedefinieerd. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```


Retourneert of stelt de standaard tabulatiegrootte in zonder overerving. Lezen/schrijven float.

**Retour:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```


Retourneert of stelt de standaard tabulatiegrootte in zonder overerving. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```


Retourneert tabulaties van een alinea. Geen overerving toegepast. Alleen-lezen [ITabCollection](../../com.aspose.slides/itabcollection).

**Retour:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```


Retourneert of stelt een lettertype-uitlijning in een alinea zonder overerving in. Lezen/schrijven [FontAlignment](../../com.aspose.slides/fontalignment).

**Retour:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```


Retourneert of stelt een lettertype-uitlijning in een alinea zonder overerving in. Lezen/schrijven [FontAlignment](../../com.aspose.slides/fontalignment).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```


Retourneert het standaardgedeelteformaat van een alinea. Geen overerving toegepast. Alleen-lezen [IPortionFormat](../../com.aspose.slides/iportionformat).

**Retour:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```


Haalt de effectieve alinea-opmaakgegevens op met de toegepaste overerving.

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

**Retour:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Een [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versie. Alleen-lezen long.

**Retour:**
long