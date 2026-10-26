---
title: PortionFormat
second_title: Aspose.Slides voor Java API-referentie
description: Deze klasse bevat de opmaak-eigenschappen van het tekstgedeelte.
type: docs
url: /nl/com.aspose.slides/portionformat/
---
**Overerving:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

Deze klasse bevat de opmaak-eigenschappen van het tekstgedeelte. In tegenstelling tot [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), zijn alle eigenschappen van deze klasse schrijfbaar.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //Maak een presentation object dat een presentatiebestand vertegenwoordigt
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides gebruikt deze speciale identifiers (vergelijkbaar met die in PowerPoint):
>      // +mn-lt - Lichaamlettertype Latin (Klein Latin Lettertype)
>      // +mj-lt - Koptekst Lettertype Latin (Groot Latin Lettertype)
>      // +mn-ea - Lichaamlettertype Oost-Aziatisch (Klein Oost-Aziatisch Lettertype)
>      // +mj-ea - Lichaamlettertype Oost-Aziatisch (Klein Oost-Aziatisch Lettertype)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Deze klasse wordt gebruikt om de opmaak-eigenschappen van een tekstgedeelte op te halen en te bewerken die voor het specifieke gedeelte zijn gedefinieerd. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, zodat u in de meeste gevallen waarden krijgt die "onbepaald" betekenen.

Om de effectieve opmaak-parameterwaarden, inclusief geërfde, te krijgen, moet u de [getEffective](../../com.aspose.slides/portionformat\#getEffective)-methode gebruiken die een [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-instantie retourneert.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | Initialiseert een nieuw exemplaar van [PortionFormat](../../com.aspose.slides/portionformat) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Retourneert of stelt bladwijzer-identificator in. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Retourneert of stelt bladwijzer-identificator in. |
| [getSmartTagClean()](#getSmartTagClean--) | Bepaalt of de smart-tag moet worden opgeschoond. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Bepaalt of de smart-tag moet worden opgeschoond. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muis-over. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muis-over. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Hyperlinks-manager. |
| [getEffective()](#getEffective--) | Haalt effectieve opmaakeigenschappen van het gedeelte op met de overerving toegepast. |
### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```

Initialiseert een nieuw exemplaar van [PortionFormat](../../com.aspose.slides/portionformat) klasse.

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```

Retourneert of stelt bladwijzer-identificator in. Lezen/Schrijven String.

**Retour:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```

Retourneert of stelt bladwijzer-identificator in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```

Bepaalt of de smart-tag moet worden opgeschoond. Geen overerving toegepast. Lezen/Schrijven boolean .

**Retour:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```

Bepaalt of de smart-tag moet worden opgeschoond. Geen overerving toegepast. Lezen/Schrijven boolean .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. Lezen/Schrijven [IHyperlink](../../com.aspose.slides/ihyperlink).

**Retour:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. Lezen/Schrijven [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Retourneert of stelt de hyperlink in die is gedefinieerd voor muis-over. Lezen/Schrijven [IHyperlink](../../com.aspose.slides/ihyperlink).

**Retour:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Retourneert of stelt de hyperlink in die is gedefinieerd voor muis-over. Lezen/Schrijven [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Hyperlinks-manager. Alleen-lezen [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Retour:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```

Haalt effectieve opmaakeigenschappen van het gedeelte op met de overerving toegepast.

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Retour:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - een [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).