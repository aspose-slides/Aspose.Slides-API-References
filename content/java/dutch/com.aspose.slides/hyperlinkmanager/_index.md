---
title: HyperlinkManager
second_title: Aspose.Slides voor Java API-referentie
description: Biedt beheer van hyperlinks, toevoegen en verwijderen.
type: docs
url: /nl/com.aspose.slides/hyperlinkmanager/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

Biedt beheer van hyperlinks (toevoegen, verwijderen).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Stelt externe hyperlink in bij klikken. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Stelt interne hyperlink in bij klikken. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Verwijdert hyperlink bij klikken. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Stelt externe hyperlink in bij muis over. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Stelt interne hyperlink in bij muis over. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Verwijdert hyperlink bij muis over. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Stelt macro-hyperlink in bij klikken. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```


Stelt externe hyperlink in bij klikken.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // Instantieert een Presentation-klasse die een PPTX voorstelt
>  Presentation pres = new Presentation();
>  try {
>      // Haalt de eerste dia op in de presentatie
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Voegt een AutoShape-object toe met het type ingesteld op Rechthoek
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // Cast het shape-object naar AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // Benadert de ITextFrame-eigenschap die aan de AutoShape is gekoppeld
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Voegt wat tekst toe aan het frame
>      portion.setText("Aspose.Slides");
>      // Stelt de hyperlink in voor de tekst van het gedeelte
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // Slaat de PPTX-presentatie op
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | Hyperlink-URL. |

**Retour:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```


Stelt interne hyperlink in bij klikken.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Doel-slide. |

**Retour:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```


Verwijdert hyperlink bij klikken.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```


Stelt externe hyperlink in bij muis over.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | Hyperlink-URL. |

**Retour:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


Stelt interne hyperlink in bij muis over.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Doel-slide. |

**Retour:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```


Verwijdert hyperlink bij muis over.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```


Stelt macro-hyperlink in bij klikken.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.BlankButton, 20, 20, 80, 30);
>      shape.getHyperlinkManager().setMacroHyperlinkClick("MacroName");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| macroName | java.lang.String | Naam van de macro |

**Retour:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Geeft Parent_Immediate object terug. Alleen-lezen IDOMObject.

**Retour:**
com.aspose.slides.IDOMObject