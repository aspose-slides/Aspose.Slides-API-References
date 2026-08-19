---
title: HyperlinkManager
second_title: Referensi API Aspose.Slides untuk Java
description: Menyediakan manajemen hyperlink, menambah dan menghapus.
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
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Mengatur hyperlink eksternal pada klik. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Mengatur hyperlink internal pada klik. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Menghapus hyperlink pada klik. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Mengatur hyperlink eksternal saat mouse over. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Mengatur hyperlink internal saat mouse over. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Menghapus hyperlink saat mouse over. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Mengatur hyperlink Makro pada klik. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

Mengatur hyperlink eksternal pada klik.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // Membuat instance kelas Presentation yang mewakili PPTX
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
>      // Mengatur Hyperlink untuk teks portion
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
| url | java.lang.String | URL hyperlink. |

**Mengembalikan:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Mengatur hyperlink internal pada klik.

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

Menghapus hyperlink pada klik.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```

Mengatur hyperlink eksternal saat mouse over.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | java.lang.String | URL hyperlink. |

**Mengembalikan:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Mengatur hyperlink internal saat mouse over.

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

Menghapus hyperlink saat mouse over.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```

Mengatur hyperlink Makro pada klik.

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
[IHyperlink](../../com.aspose.slides/ihyperlink) - objek Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Baca-saja IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject