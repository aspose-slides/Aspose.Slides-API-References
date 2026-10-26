---
title: HyperlinkManager
second_title: Aspose.Slides for Java API Referansı
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

Hiperlink yönetimini sağlayın (ekleme, kaldırma).
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Tıklama sırasında dış hiperlink ayarlar. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Tıklama sırasında iç hiperlink ayarlar. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Tıklama sırasında hiperlink kaldırır. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Fare üzerine geldiğinde dış hiperlink ayarlar. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Fare üzerine geldiğinde iç hiperlink ayarlar. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Fare üzerine geldiğinde hiperlink kaldırır. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Tıklama sırasında Makro hiperlink ayarlar. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```


Tıklama sırasında dış hiperlink ayarlar.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // PPTX'i temsil eden bir Presentation sınıfı oluşturur
>  Presentation pres = new Presentation();
>  try {
>      // Sunumdaki ilk slaytı alır
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Türü Rectangle olan bir AutoShape nesnesi ekler
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // Şekli AutoShape tipine dönüştürür
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // AutoShape ile ilişkili ITextFrame özelliğine erişir
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Çerçeveye bazı metinler ekler
>      portion.setText("Aspose.Slides");
>      // Bölüm metni için Hyperlink ayarlar
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // PPTX Sunumunu kaydeder
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| url | java.lang.String | Hiperlink URL'si. |

**Döndürür:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```


Tıklama sırasında iç hiperlink ayarlar.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Hedef slayt. |

**Döndürür:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hiperlink.

### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```


Tıklama sırasında hiperlink kaldırır.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```


Fare üzerine geldiğinde dış hiperlink ayarlar.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| url | java.lang.String | Hiperlink URL'si. |

**Döndürür:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hiperlink.

### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


Fare üzerine geldiğinde iç hiperlink ayarlar.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Hedef slayt. |

**Döndürür:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hiperlink.

### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```


Fare üzerine geldiğinde hiperlink kaldırır.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```


Tıklama sırasında Makro hiperlink ayarlar.

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
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| macroName | java.lang.String | Makronun adı |

**Döndürür:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink nesnesi [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate nesnesini döndürür. Salt Okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject