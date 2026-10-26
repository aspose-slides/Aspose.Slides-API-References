---
title: LayoutPlaceholderManager
second_title: Tham chiếu API Java của Aspose.Slides
description: Đại diện cho trình quản lý cho phép bạn thêm placeholder vào slide bố cục.
type: docs
url: /vi/com.aspose.slides/layoutplaceholdermanager/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

Đại diện cho trình quản lý cho phép bạn thêm các trình giữ chỗ vào slide bố cục.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Thêm một hình dạng trình giữ chỗ mới vào slide bố cục để chứa nội dung, chẳng hạn như ảnh, bảng, phương tiện hoặc văn bản. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Thêm một hình dạng trình giữ chỗ mới vào slide bố cục để chứa nội dung, chẳng hạn như ảnh, bảng, phương tiện hoặc văn bản theo hướng dọc. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Thêm một hình dạng trình giữ chỗ mới vào slide bố cục để chứa nội dung văn bản. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Thêm một hình dạng trình giữ chỗ mới vào slide bố cục để chứa nội dung văn bản theo hướng dọc. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Thêm một hình dạng trình giữ chỗ mới vào slide bố cục để chứa một hình ảnh. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Thêm một hình dạng trình giữ chỗ mới vào slide bố cục để chứa một biểu đồ. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Thêm một hình dạng trình giữ chỗ mới vào slide bố cục để chứa một bảng. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Thêm một hình dạng trình giữ chỗ mới vào slide bố cục để chứa một sơ đồ SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Thêm một hình dạng trình giữ chỗ mới vào slide bố cục để chứa một đối tượng phương tiện. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Thêm một hình dạng trình giữ chỗ mới vào slide bố cục để chứa một hình ảnh trực tuyến. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Thêm một hình dạng trình giữ chỗ mới vào slide bố cục để chứa nội dung, chẳng hạn như ảnh, bảng, phương tiện hoặc văn bản.

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addContentPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ X của hình dạng trình giữ chỗ mới. |
| y | float | Tọa độ Y của hình dạng trình giữ chỗ mới. |
| width | float | Chiều rộng của hình dạng trình giữ chỗ mới. |
| height | float | Chiều cao của hình dạng trình giữ chỗ mới. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Đã tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một trình giữ chỗ Content.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Thêm một hình dạng trình giữ chỗ mới vào slide bố cục để chứa nội dung, chẳng hạn như ảnh, bảng, phương tiện hoặc văn bản theo hướng dọc.

--------------------

> ```
> The following example shows how to add the Content (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalContentPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ X của hình dạng trình giữ chỗ mới. |
| y | float | Tọa độ Y của hình dạng trình giữ chỗ mới. |
| width | float | Chiều rộng của hình dạng trình giữ chỗ mới. |
| height | float | Chiều cao của hình dạng trình giữ chỗ mới. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Đã tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một trình giữ chỗ Content (Vertical).
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Thêm một hình dạng trình giữ chỗ mới vào slide bố cục để chứa nội dung văn bản.

--------------------

> ```
> The following example shows how to add the Text placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ X của hình dạng trình giữ chỗ mới. |
| y | float | Tọa độ Y của hình dạng trình giữ chỗ mới. |
| width | float | Chiều rộng của hình dạng trình giữ chỗ mới. |
| height | float | Chiều cao của hình dạng trình giữ chỗ mới. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Đã tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một trình giữ chỗ Text.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Thêm một hình dạng trình giữ chỗ mới vào slide bố cục để chứa nội dung văn bản theo hướng dọc.

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ X của hình dạng trình giữ chỗ mới. |
| y | float | Tọa độ Y của hình dạng trình giữ chỗ mới. |
| width | float | Chiều rộng của hình dạng trình giữ chỗ mới. |
| height | float | Chiều cao của hình dạng trình giữ chỗ mới. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Đã tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một trình giữ chỗ Text (Vertical).
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Thêm một hình dạng trình giữ chỗ mới vào slide bố cục để chứa một hình ảnh.

--------------------

> ```
> The following example shows how to add the Picture placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addPicturePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ X của hình dạng trình giữ chỗ mới. |
| y | float | Tọa độ Y của hình dạng trình giữ chỗ mới. |
| width | float | Chiều rộng của hình dạng trình giữ chỗ mới. |
| height | float | Chiều cao của hình dạng trình giữ chỗ mới. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Đã tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một trình giữ chỗ Picture.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Thêm một hình dạng trình giữ chỗ mới vào slide bố cục để chứa một biểu đồ.

--------------------

> ```
> The following example shows how to add the Chart placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addChartPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ X của hình dạng trình giữ chỗ mới. |
| y | float | Tọa độ Y của hình dạng trình giữ chỗ mới. |
| width | float | Chiều rộng của hình dạng trình giữ chỗ mới. |
| height | float | Chiều cao của hình dạng trình giữ chỗ mới. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Đã tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một trình giữ chỗ Chart.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Thêm một hình dạng trình giữ chỗ mới vào slide bố cục để chứa một bảng.

--------------------

> ```
> The following example shows how to add the Table placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTablePlaceholder(20, 20, 500, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ X của hình dạng trình giữ chỗ mới. |
| y | float | Tọa độ Y của hình dạng trình giữ chỗ mới. |
| width | float | Chiều rộng của hình dạng trình giữ chỗ mới. |
| height | float | Chiều cao của hình dạng trình giữ chỗ mới. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Đã tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một trình giữ chỗ Table.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Thêm một hình dạng trình giữ chỗ mới vào slide bố cục để chứa một sơ đồ SmartArt.

--------------------

> ```
> The following example shows how to add the SmartArt placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addSmartArtPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ X của hình dạng trình giữ chỗ mới. |
| y | float | Tọa độ Y của hình dạng trình giữ chỗ mới. |
| width | float | Chiều rộng của hình dạng trình giữ chỗ mới. |
| height | float | Chiều cao của hình dạng trình giữ chỗ mới. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Đã tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một trình giữ chỗ SmartArt.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Thêm một hình dạng trình giữ chỗ mới vào slide bố cục để chứa một đối tượng phương tiện.

--------------------

> ```
> The following example shows how to add the Media placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addMediaPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ X của hình dạng trình giữ chỗ mới. |
| y | float | Tọa độ Y của hình dạng trình giữ chỗ mới. |
| width | float | Chiều rộng của hình dạng trình giữ chỗ mới. |
| height | float | Chiều cao của hình dạng trình giữ chỗ mới. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Đã tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một trình giữ chỗ Media.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Thêm một hình dạng trình giữ chỗ mới vào slide bố cục để chứa một hình ảnh trực tuyến.

--------------------

> ```
> The following example shows how to add the Online Image placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ X của hình dạng trình giữ chỗ mới. |
| y | float | Tọa độ Y của hình dạng trình giữ chỗ mới. |
| width | float | Chiều rộng của hình dạng trình giữ chỗ mới. |
| height | float | Chiều cao của hình dạng trình giữ chỗ mới. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Đã tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một trình giữ chỗ Online Image.