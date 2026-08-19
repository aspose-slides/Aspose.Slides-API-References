---
title: IHyperlinkManager
second_title: Aspose.Slides for Java API Reference
description: Menyediakan manajemen hyperlink (menambah, menghapus).
type: docs
url: /id/com.aspose.slides/ihyperlinkmanager/
---``` 
public interface IHyperlinkManager
```

Menyediakan manajemen hyperlink (menambah, menghapus).
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
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
``` 
public abstract IHyperlink setExternalHyperlinkClick(String url)
```


Set external hyperlink on click.

**Parameter:**  
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| url | java.lang.String | Hyperlink URL. |

**Mengembalikan:**  
[IHyperlink](../../com.aspose.slides/ihyperlink) - objek Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
``` 
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```


Sets internal hyperlink on click.

**Parameter:**  
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Slide target. |

**Mengembalikan:**  
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```


Removes hyperlink on click.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```


Sets external hyperlink mouse over.

**Parameter:**  
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| url | java.lang.String | Hyperlink URL. |

**Mengembalikan:**  
[IHyperlink](../../com.aspose.slides/ihyperlink) - objek Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


Sets internal hyperlink mouse over.

**Parameter:**  
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Slide target. |

**Mengembalikan:**  
[IHyperlink](../../com.aspose.slides/ihyperlink) - objek Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```


Removes hyperlink mouse over.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```


Set Macro hyperlink on a click.

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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| macroName | java.lang.String | Nama macro |

**Mengembalikan:**  
[IHyperlink](../../com.aspose.slides/ihyperlink) - objek Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)