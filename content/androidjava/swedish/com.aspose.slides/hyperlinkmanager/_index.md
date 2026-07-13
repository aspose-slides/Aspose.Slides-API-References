---
title: HyperlinkManager
second_title: Aspose.Slides för Android via Java API-referens
description: Tillhandahåller hantering av hyperlänkar, lägga till och ta bort.
type: docs
url: /sv/com.aspose.slides/hyperlinkmanager/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

Tillhandahåll hantering av hyperlänkar (lägger till, tar bort).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Ställ in extern hyperlänk vid klick. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Ställer in intern hyperlänk vid klick. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Tar bort hyperlänk vid klick. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Ställer in extern hyperlänk när musen hovrar. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Ställer in intern hyperlänk när musen hovrar. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Tar bort hyperlänk när musen hovrar. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Ställ in makro-hyperlänk vid ett klick. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

Ställ in extern hyperlänk vid klick.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // Skapar en Presentation-klass som representerar en PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Hämtar den första bilden i presentationen
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Lägger till ett AutoShape-objekt med typen satt till rektangel
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // Kastar formen till AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // Åtkommer ITextFrame-egenskapen som är knuten till AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Lägger till lite text i ramen
>      portion.setText("Aspose.Slides");
>      // Ställer in hyperlänken för portions-texten
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // Sparar PPTX-presentationen
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | java.lang.String | Hyperlänk-URL. |

**Returnerar:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Ställer in intern hyperlänk vid klick.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Målslide. |

**Returnerar:**
[IHyperlink](../../com.aspose.slides/ihyperlink) – Hyperlänk.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```

Tar bort hyperlänk vid klick.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```

Ställer in extern hyperlänk när musen hovrar.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | java.lang.String | Hyperlänk-URL. |

**Returnerar:**
[IHyperlink](../../com.aspose.slides/ihyperlink) – Hyperlänk.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Ställer in intern hyperlänk när musen hovrar.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Målslide. |

**Returnerar:**
[IHyperlink](../../com.aspose.slides/ihyperlink) – Hyperlänk.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```

Tar bort hyperlänk när musen hovrar.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```

Ställ in makro-hyperlänk vid ett klick.

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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| macroName | java.lang.String | Namn på makrot |

**Returnerar:**
[IHyperlink](../../com.aspose.slides/ihyperlink) – Hyperlänkobjekt [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objekt. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject