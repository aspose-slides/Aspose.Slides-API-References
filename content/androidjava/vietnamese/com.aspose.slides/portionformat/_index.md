---
title: PortionFormat
second_title: Aspose.Slides cho Android thông qua Tham khảo API Java
description: Lớp này chứa các thuộc tính định dạng phần văn bản.
type: docs
url: /vi/com.aspose.slides/portionformat/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

Lớp này chứa các thuộc tính định dạng phần văn bản. Khác với [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), tất cả các thuộc tính của lớp này đều có thể ghi.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //Khởi tạo một đối tượng presentation đại diện cho một tệp trình chiếu
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides sử dụng các định danh đặc biệt này (tương tự như các định danh được sử dụng trong PowerPoint):
>      // +mn-lt - Phông chữ Latin phần thân (Phông Latin phụ)
>      // +mj-lt - Phông chữ Latin tiêu đề (Phông Latin chính)
>      // +mn-ea - Phông chữ Đông Á phần thân (Phông Đông Á phụ)
>      // +mj-ea - Phông chữ Đông Á phần thân (Phông Đông Á phụ)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Lớp này được sử dụng để trả về và thao tác các thuộc tính định dạng phần văn bản được định nghĩa cho phần cụ thể. Điều này có nghĩa là không có kế thừa được áp dụng khi lấy giá trị, do đó trong phần lớn các trường hợp bạn sẽ nhận được các giá trị có nghĩa là "không xác định".

Để lấy các giá trị tham số định dạng hiệu quả bao gồm cả kế thừa, bạn cần sử dụng phương thức [getEffective](../../com.aspose.slides/portionformat\#getEffective) mà trả về một thể hiện [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | Khởi tạo một thể hiện mới của lớp [PortionFormat](../../com.aspose.slides/portionformat). |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Trả về hoặc đặt định danh dấu trang. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Trả về hoặc đặt định danh dấu trang. |
| [getSmartTagClean()](#getSmartTagClean--) | Xác định liệu thẻ thông minh có nên được xóa không. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Xác định liệu thẻ thông minh có nên được xóa không. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Trả về hoặc đặt siêu liên kết được định nghĩa cho nhấp chuột. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Trả về hoặc đặt siêu liên kết được định nghĩa cho nhấp chuột. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Trả về hoặc đặt siêu liên kết được định nghĩa cho di chuột. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Trả về hoặc đặt siêu liên kết được định nghĩa cho di chuột. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Trình quản lý siêu liên kết. |
| [getEffective()](#getEffective--) | Lấy dữ liệu định dạng phần hiệu quả với kế thừa đã được áp dụng. |
### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```


Khởi tạo một thể hiện mới của lớp [PortionFormat](../../com.aspose.slides/portionformat).

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```


Trả về hoặc đặt định danh dấu trang. Đọc/ghi String.

**Trả về:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```


Trả về hoặc đặt định danh dấu trang. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```


Xác định liệu thẻ thông minh có nên được xóa không. Không áp dụng kế thừa. Đọc/ghi boolean .

**Trả về:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```


Xác định liệu thẻ thông minh có nên được xóa không. Không áp dụng kế thừa. Đọc/ghi boolean .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```


Trả về hoặc đặt siêu liên kết được định nghĩa cho nhấp chuột. Đọc/ghi [IHyperlink](../../com.aspose.slides/ihyperlink).

**Trả về:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```


Trả về hoặc đặt siêu liên kết được định nghĩa cho nhấp chuột. Đọc/ghi [IHyperlink](../../com.aspose.slides/ihyperlink).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```


Trả về hoặc đặt siêu liên kết được định nghĩa cho di chuột. Đọc/ghi [IHyperlink](../../com.aspose.slides/ihyperlink).

**Trả về:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```


Trả về hoặc đặt siêu liên kết được định nghĩa cho di chuột. Đọc/ghi [IHyperlink](../../com.aspose.slides/ihyperlink).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```


Trình quản lý siêu liên kết. Chỉ đọc [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Trả về:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```


Lấy dữ liệu định dạng phần hiệu quả với kế thừa đã được áp dụng.

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


--------------------

**Trả về:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).