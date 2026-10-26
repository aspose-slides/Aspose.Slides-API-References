---
title: IHyperlinkManager
second_title: Aspose.Slides for Android via Java API Reference
description: Provide hyperlinks management adding removing.
type: docs
url: /id/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Menyediakan manajemen hyperlink (penambahan, penghapusan).

## Metode

| Metode | Deskripsi |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Mengatur hyperlink eksternal pada klik. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Mengatur hyperlink internal pada klik. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Menghapus hyperlink pada klik. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Mengatur hyperlink eksternal saat mouse melayang. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Mengatur hyperlink internal saat mouse melayang. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Menghapus hyperlink saat mouse melayang. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Mengatur hyperlink Makro pada klik. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

Mengatur hyperlink eksternal pada klik.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | java.lang.String | URL hyperlink. |

**Mengembalikan:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Mengatur hyperlink internal pada klik.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Target slide. |

**Mengembalikan:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

Menghapus hyperlink pada klik.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

Mengatur hyperlink eksternal saat mouse melayang.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | java.lang.String | URL hyperlink. |

**Mengembalikan:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Mengatur hyperlink internal saat mouse melayang.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Target slide. |

**Mengembalikan:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

Menghapus hyperlink saat mouse melayang.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
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
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)