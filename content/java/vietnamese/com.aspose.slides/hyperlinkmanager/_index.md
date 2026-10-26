---
title: HyperlinkManager
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cung cấp quản lý siêu liên kết, bao gồm thêm và xóa.
type: docs
url: /vi/com.aspose.slides/hyperlinkmanager/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

Cung cấp quản lý siêu liên kết (thêm, xóa).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Đặt siêu liên kết bên ngoài khi nhấp chuột. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Đặt siêu liên kết nội bộ khi nhấp chuột. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Xóa siêu liên kết khi nhấp chuột. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Đặt siêu liên kết bên ngoài khi di chuột qua. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Đặt siêu liên kết nội bộ khi di chuột qua. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Xóa siêu liên kết khi di chuột qua. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Đặt siêu liên kết macro khi nhấp chuột. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```


Đặt siêu liên kết bên ngoài khi nhấp chuột.

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

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| url | java.lang.String | URL siêu liên kết. |

**Trả về:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```


Đặt siêu liên kết nội bộ khi nhấp chuột.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Trang chiếu mục tiêu. |

**Trả về:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Siêu liên kết.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```


Xóa siêu liên kết khi nhấp chuột.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```


Đặt siêu liên kết bên ngoài khi di chuột qua.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| url | java.lang.String | URL siêu liên kết. |

**Trả về:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Siêu liên kết.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


Đặt siêu liên kết nội bộ khi di chuột qua.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Trang chiếu mục tiêu. |

**Trả về:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Siêu liên kết.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```


Xóa siêu liên kết khi di chuột qua.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```


Đặt siêu liên kết macro khi nhấp chuột.

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


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| macroName | java.lang.String | Tên macro |

**Trả về:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Đối tượng Siêu liên kết [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject