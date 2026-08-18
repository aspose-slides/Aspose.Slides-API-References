---
title: HyperlinkManager
second_title: Aspose.Slides für die Java API-Referenz
description: Bietet die Verwaltung von Hyperlinks zum Hinzufügen und Entfernen.
type: docs
url: /de/com.aspose.slides/hyperlinkmanager/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

Stellt die Verwaltung von Hyperlinks bereit (Hinzufügen, Entfernen).
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Setzt externen Hyperlink beim Klicken. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Setzt internen Hyperlink beim Klicken. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Entfernt Hyperlink beim Klicken. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Setzt externen Hyperlink beim Mouseover. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Setzt internen Hyperlink beim Mouseover. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Entfernt Hyperlink beim Mouseover. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Setzt Makro-Hyperlink beim Klicken. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

Setzt externen Hyperlink beim Klicken.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // Instantiates a Presentation class that represents a PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Gets the first slide in the presentation
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Adds an AutoShape object with type set as Rectangle
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // Casts the shape to AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // Accesses the ITextFrame property associated with the AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Adds some text to the frame
>      portion.setText("Aspose.Slides");
>      // Sets the Hyperlink for the portion text
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // Saves the PPTX Presentation
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | java.lang.String | Hyperlink-URL. |

**Rückgabe:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Setzt internen Hyperlink beim Klicken.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Zielfolie. |

**Rückgabe:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```

Entfernt Hyperlink beim Klicken.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```

Setzt externen Hyperlink beim Mouseover.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | java.lang.String | Hyperlink-URL. |

**Rückgabe:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Setzt internen Hyperlink beim Mouseover.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Zielfolie. |

**Rückgabe:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```

Entfernt Hyperlink beim Mouseover.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```

Setzt Makro-Hyperlink beim Klicken.

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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| macroName | java.lang.String | Name des Makros |

**Rückgabe:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink-Objekt [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Objekt Parent_Immediate zurück. Schreibgeschütztes IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject