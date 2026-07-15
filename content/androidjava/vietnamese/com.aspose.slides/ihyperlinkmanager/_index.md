---
title: IHyperlinkManager
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cung cấp chức năng quản lý siêu liên kết, thêm và xóa.
type: docs
url: /vi/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Cung cấp chức năng quản lý siêu liên kết (thêm, xóa).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Đặt siêu liên kết ngoại khi nhấp chuột. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Đặt siêu liên kết nội bộ khi nhấp chuột. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Xóa siêu liên kết khi nhấp chuột. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Đặt siêu liên kết ngoại khi rê chuột. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Đặt siêu liên kết nội bộ khi rê chuột. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Xóa siêu liên kết khi rê chuột. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Đặt siêu liên kết Macro khi nhấp chuột. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

Đặt siêu liên kết ngoại khi nhấp chuột.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| url | java.lang.String | URL siêu liên kết. |

**Kết quả:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - đối tượng Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Đặt siêu liên kết nội bộ khi nhấp chuột.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Slide mục tiêu. |

**Kết quả:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

Xóa siêu liên kết khi nhấp chuột.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

Đặt siêu liên kết ngoại khi rê chuột.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| url | java.lang.String | URL siêu liên kết. |

**Kết quả:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Đặt siêu liên kết nội bộ khi rê chuột.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Slide mục tiêu. |

**Kết quả:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

Xóa siêu liên kết khi rê chuột.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

Đặt siêu liên kết Macro khi nhấp chuột.

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

**Kết quả:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - đối tượng Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)