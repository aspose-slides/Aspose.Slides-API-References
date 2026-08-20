---
title: IHyperlinkManager
second_title: Aspose.Slides for Java Tham chiếu API
description: Cung cấp quản lý siêu liên kết để thêm và xóa.
type: docs
url: /vi/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Cung cấp quản lý siêu liên kết (thêm, xóa).
## Phương thức

| Method | Description |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Đặt siêu liên kết bên ngoài khi nhấp. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Đặt siêu liên kết nội bộ khi nhấp. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Xóa siêu liên kết khi nhấp. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Đặt siêu liên kết bên ngoài khi di chuột. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Đặt siêu liên kết nội bộ khi di chuột. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Xóa siêu liên kết khi di chuột. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Đặt siêu liên kết Macro khi nhấp. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

Đặt siêu liên kết bên ngoài khi nhấp.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL siêu liên kết. |

**Trả về:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - đối tượng Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Đặt siêu liên kết nội bộ khi nhấp.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Slide mục tiêu. |

**Trả về:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

Xóa siêu liên kết khi nhấp.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

Đặt siêu liên kết bên ngoài khi di chuột.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL siêu liên kết. |

**Trả về:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Đặt siêu liên kết nội bộ khi di chuột.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Slide mục tiêu. |

**Trả về:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

Xóa siêu liên kết khi di chuột.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
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

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| macroName | java.lang.String | Tên của macro |

**Trả về:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - đối tượng Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)