---
title: HyperlinkManager
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cung cấp quản lý siêu liên kết, thêm và xóa.
type: docs
url: /vi/com.aspose.slides/hyperlinkmanager/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

Cung cấp quản lý siêu liên kết (thêm, xóa).
## Methods

| Method | Description |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Đặt siêu liên kết bên ngoài khi nhấp. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Đặt siêu liên kết nội bộ khi nhấp. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Xóa siêu liên kết khi nhấp. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Đặt siêu liên kết bên ngoài khi di chuột qua. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Đặt siêu liên kết nội bộ khi di chuột qua. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Xóa siêu liên kết khi di chuột qua. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Đặt siêu liên kết Macro khi nhấp. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```


Đặt siêu liên kết bên ngoài khi nhấp.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // Khởi tạo một lớp Presentation đại diện cho một PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Lấy slide đầu tiên trong bản trình bày
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Thêm một đối tượng AutoShape với loại được đặt là Rectangle
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // Ép kiểu shape sang AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // Truy cập thuộc tính ITextFrame liên kết với AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Thêm một số văn bản vào khung
>      portion.setText("Aspose.Slides");
>      // Đặt Hyperlink cho văn bản phần
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // Lưu bản trình bày PPTX
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL của siêu liên kết. |

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```


Đặt siêu liên kết nội bộ khi nhấp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Slide mục tiêu. |

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```


Xóa siêu liên kết khi nhấp.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```


Đặt siêu liên kết bên ngoài khi di chuột qua.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL của siêu liên kết. |

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


Đặt siêu liên kết nội bộ khi di chuột qua.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Slide mục tiêu. |

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```


Xóa siêu liên kết khi di chuột qua.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```


Đặt siêu liên kết Macro khi nhấp.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| macroName | java.lang.String | Tên của macro |

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Đối tượng Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject