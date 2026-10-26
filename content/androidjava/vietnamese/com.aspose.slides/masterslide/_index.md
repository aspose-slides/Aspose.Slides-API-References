---
title: MasterSlide
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Đại diện cho một slide master trong bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/masterslide/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

Đại diện cho một slide master trong bản trình chiếu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Trả về trình quản lý HeaderFooter của slide master. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Tạo một slide master mới dựa trên slide hiện tại, áp dụng một theme bên ngoài vào nó và áp dụng slide master đã tạo cho tất cả các slide phụ thuộc. |
| [getTitleStyle()](#getTitleStyle--) | Trả về kiểu dáng của văn bản tiêu đề. |
| [getBodyStyle()](#getBodyStyle--) | Trả về kiểu dáng của văn bản nội dung. |
| [getOtherStyle()](#getOtherStyle--) | Trả về kiểu dáng của một văn bản khác. |
| [getLayoutSlides()](#getLayoutSlides--) | Trả về bộ sưu tập các slide bố cục con cho slide master này. |
| [getPreserve()](#getPreserve--) | Xác định liệu master tương ứng có bị xóa khi tất cả các slide kế tiếp master đó bị xóa hay không. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Xác định liệu master tương ứng có bị xóa khi tất cả các slide kế tiếp master đó bị xóa hay không. |
| [getDependingSlides()](#getDependingSlides--) | Trả về một mảng chứa tất cả các slide phụ thuộc vào slide master này. |
| [hasDependingSlides()](#hasDependingSlides--) | Trả về true nếu tồn tại ít nhất một slide phụ thuộc vào slide master này. |
| [getThemeManager()](#getThemeManager--) | Trả về trình quản lý theme. |
| [getName()](#getName--) | Trả về hoặc thiết lập tên của một slide master. |
| [setName(String value)](#setName-java.lang.String-) | Trả về hoặc thiết lập tên của một slide master. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Xác định nếu các hình dạng trên slide master có nên được hiển thị trên các slide hay không. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Xác định nếu các hình dạng trên slide master có nên được hiển thị trên các slide hay không. |
| [getDrawingGuides()](#getDrawingGuides--) | Trả về một bộ sưu tập các hướng dẫn vẽ cho slide master. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```


Trả về trình quản lý HeaderFooter của slide master. Chỉ đọc [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Trả về:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```


Tạo một slide master mới dựa trên slide hiện tại, áp dụng một theme bên ngoài vào nó và áp dụng slide master đã tạo cho tất cả các slide phụ thuộc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fname | java.lang.String | Đường dẫn tới tệp theme bên ngoài (.thmx). |

**Trả về:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - MasterSlide mới có theme.
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```


Trả về kiểu dáng của văn bản tiêu đề. Chỉ đọc [ITextStyle](../../com.aspose.slides/itextstyle).

**Trả về:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```


Trả về kiểu dáng của văn bản nội dung. Chỉ đọc [ITextStyle](../../com.aspose.slides/itextstyle).

**Trả về:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```


Trả về kiểu dáng của một văn bản khác. Chỉ đọc [ITextStyle](../../com.aspose.slides/itextstyle).

**Trả về:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```


Trả về bộ sưu tập các slide bố cục con cho slide master này. Chỉ đọc [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Bạn có thể truy cập API thay thế để thêm/chèn/xóa/nhân bản các slide bố cục bằng cách sử dụng thuộc tính ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) property.

**Trả về:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```


Xác định liệu master tương ứng có bị xóa khi tất cả các slide kế tiếp master đó bị xóa hay không. Lưu ý: Aspose.Slides sẽ không bao giờ tự động xóa bất kỳ master không sử dụng nào, để thực sự xóa các master không sử dụng, gọi [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Đọc/ghi boolean .

**Trả về:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```


Xác định liệu master tương ứng có bị xóa khi tất cả các slide kế tiếp master đó bị xóa hay không. Lưu ý: Aspose.Slides sẽ không bao giờ tự động xóa bất kỳ master không sử dụng nào, để thực sự xóa các master không sử dụng, gọi [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Đọc/ghi boolean .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```


Trả về một mảng chứa tất cả các slide phụ thuộc vào slide master này.

**Trả về:**
com.aspose.slides.ISlide[] - Mảng của [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```


Trả về true nếu tồn tại ít nhất một slide phụ thuộc vào slide master này. Chỉ đọc boolean .

**Trả về:**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```


Trả về trình quản lý theme. Chỉ đọc [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Trả về:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```


Trả về hoặc thiết lập tên của một slide master. Đọc/ghi String.

**Trả về:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Trả về hoặc thiết lập tên của một slide master. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Xác định nếu các hình dạng trên slide master có nên được hiển thị trên các slide hay không. Đối với chính slide master, thuộc tính này luôn trả về false. Đọc/ghi boolean .

**Trả về:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Xác định nếu các hình dạng trên slide master có nên được hiển thị trên các slide hay không. Đối với chính slide master, thuộc tính này luôn trả về false. Đọc/ghi boolean .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Trả về một bộ sưu tập các hướng dẫn vẽ cho slide master. Chỉ đọc [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Thêm hướng dẫn vẽ dọc mới vào bên phải trung tâm slide
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)