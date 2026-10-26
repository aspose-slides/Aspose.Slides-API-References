---
title: HyperlinkManager
second_title: Aspose.Slides for Android için Java API Referansı
description: Hiperlink yönetimini ekleme ve kaldırma sağlar.
type: docs
url: /tr/com.aspose.slides/hyperlinkmanager/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

Hiperlink yönetimini sağlar (ekleme, kaldırma).
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Harici hiperlinki tıklamada ayarlar. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | İç hiperlinki tıklamada ayarlar. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Tıklamada hiperlinki kaldırır. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Harici hiperlinki fareyle üzerine gelindiğinde ayarlar. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | İç hiperlinki fareyle üzerine gelindiğinde ayarlar. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Fareyle üzerine gelindiğinde hiperlinki kaldırır. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Makro hiperlinki bir tıklamada ayarlar. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```


Harici hiperlinki tıklamada ayarlar.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | java.lang.String | Hiperlink URL'si. |

**Döndürür:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```


İç hiperlinki tıklamada ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Hedef slayt. |

**Döndürür:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```


Tıklamada hiperlinki kaldırır.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```


Harici hiperlinki fareyle üzerine gelindiğinde ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | java.lang.String | Hiperlink URL'si. |

**Döndürür:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


İç hiperlinki fareyle üzerine gelindiğinde ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Hedef slayt. |

**Döndürür:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```


Fareyle üzerine gelindiğinde hiperlinki kaldırır.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```


Makro hiperlinki bir tıklamada ayarlar.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| macroName | java.lang.String | Makronun adı |

**Döndürür:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Döndürür Parent_Immediate nesnesi. Sadece okuma IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject