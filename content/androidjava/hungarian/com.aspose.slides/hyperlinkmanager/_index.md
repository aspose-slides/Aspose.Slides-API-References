---
title: HyperlinkManager
second_title: Aspose.Slides Android számára Java API-referencia
description: Biztosítja a hiperhivatkozások kezelését, hozzáadást és eltávolítást.
type: docs
url: /hu/com.aspose.slides/hyperlinkmanager/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

Hiperhivatkozások kezelése (hozzáadás, eltávolítás).
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Külső hiperhivatkozás beállítása kattintáskor. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Belső hiperhivatkozás beállítása kattintáskor. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Hiperhivatkozás eltávolítása kattintáskor. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Külső hiperhivatkozás beállítása egérmutató fölé. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Belső hiperhivatkozás beállítása egérmutató fölé. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Hiperhivatkozás eltávolítása egérmutató fölé. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Makró hiperhivatkozás beállítása kattintáskor. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

Külső hiperhivatkozás beállítása kattintáskor.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // Példányosít egy Presentation osztályt, amely egy PPTX-et képvisel
>  Presentation pres = new Presentation();
>  try {
>      // Lekéri a prezentáció első diáját
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Hozzáad egy AutoShape objektumot, típus beállítva Téglalapként
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // Átalakítja a formát AutoShape-re
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // Eléri az AutoShape-hez tartozó ITextFrame tulajdonságot
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Szöveget ad a kerethez
>      portion.setText("Aspose.Slides");
>      // Beállítja a hiperhivatkozást a rész szövegéhez
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // Mentés a PPTX prezentációt
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | java.lang.String | Hiperhivatkozás URL. |

**Visszatérési érték:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Belső hiperhivatkozás beállítása kattintáskor.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Cél dia. |

**Visszatérési érték:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```

Hiperhivatkozás eltávolítása kattintáskor.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```

Külső hiperhivatkozás beállítása egérmutató fölé.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | java.lang.String | Hiperhivatkozás URL. |

**Visszatérési érték:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Belső hiperhivatkozás beállítása egérmutató fölé.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Cél dia. |

**Visszatérési érték:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```

Hiperhivatkozás eltávolítása egérmutató fölé.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```

Makró hiperhivatkozás beállítása kattintáskor.

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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| macroName | java.lang.String | A makró neve |

**Visszatérési érték:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject