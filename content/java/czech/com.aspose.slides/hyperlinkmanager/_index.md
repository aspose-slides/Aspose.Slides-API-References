---
title: HyperlinkManager
second_title: Aspose.Slides pro Java API Reference
description: Poskytuje správu hyperodkazů přidávání a odstraňování.
type: docs
url: /cs/com.aspose.slides/hyperlinkmanager/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

Poskytuje správu hyperodkazů (přidávání, odstraňování).
## Metody

| Metoda | Popis |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Nastaví externí hyperodkaz po kliknutí. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Nastaví interní hyperodkaz po kliknutí. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Odstraní hyperodkaz po kliknutí. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Nastaví externí hyperodkaz při přejetí myší. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Nastaví interní hyperodkaz při přejetí myší. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Odstraní hyperodkaz při přejetí myší. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Nastaví hyperodkaz na makro při kliknutí. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```


Nastaví externí hyperodkaz po kliknutí.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // Vytvoří instanci třídy Presentation, která představuje PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Získá první snímek v prezentaci
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Přidá objekt AutoShape s typem nastaveným na Rectangle
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // Přetypuje tvar na AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // Přistupuje k vlastnosti ITextFrame spojené s AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Přidá nějaký text do rámce
>      portion.setText("Aspose.Slides");
>      // Nastaví hyperodkaz pro text úseku
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // Uloží PPTX prezentaci
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| url | java.lang.String | URL hyperodkaz. |

**Vrací:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```


Nastaví interní hyperodkaz po kliknutí.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Cílový snímek. |

**Vrací:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```


Odstraní hyperodkaz po kliknutí.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```


Nastaví externí hyperodkaz při přejetí myší.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| url | java.lang.String | URL hyperodkaz. |

**Vrací:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


Nastaví interní hyperodkaz při přejetí myší.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Cílový snímek. |

**Vrací:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```


Odstraní hyperodkaz při přejetí myší.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```


Nastaví hyperodkaz na makro při kliknutí.

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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| macroName | java.lang.String | Název makra |

**Vrací:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink objekt [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject