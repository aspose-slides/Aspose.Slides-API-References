---
title: HyperlinkManager
second_title: Referensi API Java Aspose.Slides untuk Android
description: Menyediakan manajemen hyperlink, penambahan, dan penghapusan.
type: docs
url: /id/com.aspose.slides/hyperlinkmanager/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

Sediakan manajemen hyperlink (menambah, menghapus).
## Metode

| Metode | Deskripsi |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Set external hyperlink on click. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Sets internal hyperlink on click. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Removes hyperlink on click. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Sets external hyperlink mouse over. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Sets internal hyperlink mouse over. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Removes hyperlink mouse over. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Set Macro hyperlink on a click. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

Tetapkan hyperlink eksternal saat diklik.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // Menginstansiasi kelas Presentation yang mewakili PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Mengambil slide pertama dalam presentasi
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Menambahkan objek AutoShape dengan tipe Rectangle
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // Mengubah tipe shape menjadi AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // Mengakses properti ITextFrame yang terkait dengan AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Menambahkan beberapa teks ke frame
>      portion.setText("Aspose.Slides");
>      // Menetapkan Hyperlink untuk teks bagian
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // Menyimpan Presentasi PPTX
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | java.lang.String | URL Hyperlink. |

**Mengembalikan:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Menetapkan hyperlink internal saat diklik.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Slide target. |

**Mengembalikan:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```

Menghapus hyperlink saat diklik.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```

Menetapkan hyperlink eksternal saat mouse melayang.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | java.lang.String | URL Hyperlink. |

**Mengembalikan:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Menetapkan hyperlink internal saat mouse melayang.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Slide target. |

**Mengembalikan:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```

Menghapus hyperlink saat mouse melayang.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```

Tetapkan hyperlink Makro saat diklik.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| macroName | java.lang.String | Nama makro |

**Mengembalikan:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan Parent_Immediate object. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject