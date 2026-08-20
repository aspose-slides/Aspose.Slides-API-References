---
title: MasterSlide
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện một master slide trong bài thuyết trình.
type: docs
url: /vi/com.aspose.slides/masterslide/
---
**Kế thừa:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Tất cả các giao diện đã triển khai:**  
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)  
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

Biểu diễn một master slide trong bài thuyết trình.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Trả về trình quản lý HeaderFooter của master slide. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Tạo một master slide mới dựa trên slide hiện tại, áp dụng một giao diện ngoài cho nó và áp dụng master slide đã tạo cho tất cả các slide phụ thuộc. |
| [getTitleStyle()](#getTitleStyle--) | Trả về kiểu dáng của văn bản tiêu đề. |
| [getBodyStyle()](#getBodyStyle--) | Trả về kiểu dáng của văn bản thân. |
| [getOtherStyle()](#getOtherStyle--) | Trả về kiểu dáng của văn bản khác. |
| [getLayoutSlides()](#getLayoutSlides--) | Trả về tập hợp các slide bố cục con cho master slide này. |
| [getPreserve()](#getPreserve--) | Xác định xem master tương ứng có bị xóa khi tất cả các slide theo sau master đó bị xóa hay không. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Xác định xem master tương ứng có bị xóa khi tất cả các slide theo sau master đó bị xóa hay không. |
| [getDependingSlides()](#getDependingSlides--) | Trả về một mảng chứa tất cả các slide phụ thuộc vào master slide này. |
| [hasDependingSlides()](#hasDependingSlides--) | Trả về true nếu tồn tại ít nhất một slide phụ thuộc vào master slide này. |
| [getThemeManager()](#getThemeManager--) | Trả về trình quản lý giao diện. |
| [getName()](#getName--) | Trả về hoặc đặt tên của một master slide. |
| [setName(String value)](#setName-java.lang.String-) | Trả về hoặc đặt tên của một master slide. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Xác định xem các hình trên master slide có được hiển thị trên slide hay không. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Xác định xem các hình trên master slide có được hiển thị trên slide hay không. |
| [getDrawingGuides()](#getDrawingGuides--) | Trả về tập hợp các hướng dẫn vẽ cho master slide. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Trả về trình quản lý HeaderFooter của master slide. Chỉ đọc [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Giá trị trả về:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Tạo một master slide mới dựa trên slide hiện tại, áp dụng một giao diện ngoài cho nó và áp dụng master slide đã tạo cho tất cả các slide phụ thuộc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fname | java.lang.String | Đường dẫn tới tệp giao diện ngoài (.thmx). |

**Giá trị trả về:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - MasterSlide mới có giao diện.

### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

Trả về kiểu dáng của văn bản tiêu đề. Chỉ đọc [ITextStyle](../../com.aspose.slides/itextstyle).

**Giá trị trả về:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

Trả về kiểu dáng của văn bản thân. Chỉ đọc [ITextStyle](../../com.aspose.slides/itextstyle).

**Giá trị trả về:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

Trả về kiểu dáng của văn bản khác. Chỉ đọc [ITextStyle](../../com.aspose.slides/itextstyle).

**Giá trị trả về:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

Trả về tập hợp các slide bố cục con cho master slide này. Chỉ đọc [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Bạn có thể truy cập API thay thế để thêm/chen/chỉnh/xóa/nhân bản các slide bố cục bằng cách sử dụng thuộc tính ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Giá trị trả về:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

Xác định xem master tương ứng có bị xóa khi tất cả các slide theo sau master đó bị xóa hay không. Lưu ý: Aspose.Slides sẽ không bao giờ tự động xóa bất kỳ master thừa nào; để thực sự xóa các master không dùng, hãy gọi [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Đọc/ghi boolean.

**Giá trị trả về:**
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

Xác định xem master tương ứng có bị xóa khi tất cả các slide theo sau master đó bị xóa hay không. Lưu ý: Aspose.Slides sẽ không bao giờ tự động xóa bất kỳ master thừa nào; để thực sự xóa các master không dùng, hãy gọi [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Trả về một mảng chứa tất cả các slide phụ thuộc vào master slide này.

**Giá trị trả về:**
com.aspose.slides.ISlide[] - Mảng của [ISlide](../../com.aspose.slides/islide)

### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Trả về true nếu tồn tại ít nhất một slide phụ thuộc vào master slide này. Chỉ đọc boolean.

**Giá trị trả về:**
boolean

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Trả về trình quản lý giao diện. Chỉ đọc [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Giá trị trả về:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getName() {#getName--}
```
public String getName()
```

Trả về hoặc đặt tên của một master slide. Đọc/ghi String.

**Giá trị trả về:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Trả về hoặc đặt tên của một master slide. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Xác định xem các hình trên master slide có được hiển thị trên slide hay không. Đối với master slide tự nó, thuộc tính này luôn trả về false. Đọc/ghi boolean.

**Giá trị trả về:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Xác định xem các hình trên master slide có được hiển thị trên slide hay không. Đối với master slide tự nó, thuộc tính này luôn trả về false. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Trả về tập hợp các hướng dẫn vẽ cho master slide. Chỉ đọc [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Thêm hướng dẫn vẽ dọc mới vào phía bên phải của trung tâm slide
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Giá trị trả về:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)