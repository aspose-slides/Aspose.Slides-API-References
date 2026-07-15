---
title: LayoutPlaceholderManager
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho trình quản lý cho phép bạn thêm các placeholder vào slide bố cục.
type: docs
url: /vi/com.aspose.slides/layoutplaceholdermanager/
---
**Kế thừa:**  
java.lang.Object

**Tất cả các giao diện được thực hiện:**  
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)  
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

Đại diện cho trình quản lý cho phép bạn thêm các placeholder vào slide bố cục.  

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Thêm một hình placeholder mới vào slide bố cục để chứa nội dung, chẳng hạn như hình ảnh, bảng, phương tiện hoặc văn bản. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Thêm một hình placeholder mới vào slide bố cục để chứa nội dung, chẳng hạn như hình ảnh, bảng, phương tiện hoặc văn bản theo chiều dọc. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Thêm một hình placeholder mới vào slide bố cục để chứa nội dung văn bản. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Thêm một hình placeholder mới vào slide bố cục để chứa nội dung văn bản theo chiều dọc. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Thêm một hình placeholder mới vào slide bố cục để chứa hình ảnh. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Thêm một hình placeholder mới vào slide bố cục để chứa biểu đồ. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Thêm một hình placeholder mới vào slide bố cục để chứa bảng. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Thêm một hình placeholder mới vào slide bố cục để chứa sơ đồ SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Thêm một hình placeholder mới vào slide bố cục để chứa đối tượng phương tiện. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Thêm một hình placeholder mới vào slide bố cục để chứa hình ảnh trực tuyến. |

### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Thêm một hình placeholder mới vào slide bố cục để chứa nội dung, chẳng hạn như hình ảnh, bảng, phương tiện hoặc văn bản.

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
| x | float | Tọa độ X của hình placeholder mới. |
| y | float | Tọa độ Y của hình placeholder mới. |
| width | float | Chiều rộng của hình placeholder mới. |
| height | float | Chiều cao của hình placeholder mới. |

**Giá trị trả về:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Được tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một placeholder Nội dung.

### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Thêm một hình placeholder mới vào slide bố cục để chứa nội dung, chẳng hạn như hình ảnh, bảng, phương tiện hoặc văn bản theo chiều dọc.

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
| x | float | Tọa độ X của hình placeholder mới. |
| y | float | Tọa độ Y của hình placeholder mới. |
| width | float | Chiều rộng của hình placeholder mới. |
| height | float | Chiều cao của hình placeholder mới. |

**Giá trị trả về:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Được tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một placeholder Nội dung (Chiều dọc).

### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Thêm một hình placeholder mới vào slide bố cục để chứa nội dung văn bản.

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
| x | float | Tọa độ X của hình placeholder mới. |
| y | float | Tọa độ Y của hình placeholder mới. |
| width | float | Chiều rộng của hình placeholder mới. |
| height | float | Chiều cao của hình placeholder mới. |

**Giá trị trả về:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Được tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một placeholder Văn bản.

### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Thêm một hình placeholder mới vào slide bố cục để chứa nội dung văn bản theo chiều dọc.

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
| x | float | Tọa độ X của hình placeholder mới. |
| y | float | Tọa độ Y của hình placeholder mới. |
| width | float | Chiều rộng của hình placeholder mới. |
| height | float | Chiều cao của hình placeholder mới. |

**Giá trị trả về:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Được tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một placeholder Văn bản (Chiều dọc).

### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Thêm một hình placeholder mới vào slide bố cục để chứa hình ảnh.

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
| x | float | Tọa độ X của hình placeholder mới. |
| y | float | Tọa độ Y của hình placeholder mới. |
| width | float | Chiều rộng của hình placeholder mới. |
| height | float | Chiều cao của hình placeholder mới. |

**Giá trị trả về:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Được tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một placeholder Hình ảnh.

### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Thêm một hình placeholder mới vào slide bố cục để chứa biểu đồ.

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
| x | float | Tọa độ X của hình placeholder mới. |
| y | float | Tọa độ Y của hình placeholder mới. |
| width | float | Chiều rộng của hình placeholder mới. |
| height | float | Chiều cao của hình placeholder mới. |

**Giá trị trả về:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Được tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một placeholder Biểu đồ.

### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Thêm một hình placeholder mới vào slide bố cục để chứa bảng.

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
| x | float | Tọa độ X của hình placeholder mới. |
| y | float | Tọa độ Y của hình placeholder mới. |
| width | float | Chiều rộng của hình placeholder mới. |
| height | float | Chiều cao của hình placeholder mới. |

**Giá trị trả về:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Được tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một placeholder Bảng.

### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Thêm một hình placeholder mới vào slide bố cục để chứa sơ đồ SmartArt.

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
| x | float | Tọa độ X của hình placeholder mới. |
| y | float | Tọa độ Y của hình placeholder mới. |
| width | float | Chiều rộng của hình placeholder mới. |
| height | float | Chiều cao của hình placeholder mới. |

**Giá trị trả về:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Được tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một placeholder SmartArt.

### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Thêm một hình placeholder mới vào slide bố cục để chứa đối tượng phương tiện.

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
| x | float | Tọa độ X của hình placeholder mới. |
| y | float | Tọa độ Y của hình placeholder mới. |
| width | float | Chiều rộng của hình placeholder mới. |
| height | float | Chiều cao của hình placeholder mới. |

**Giá trị trả về:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Được tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một placeholder Phương tiện.

### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Thêm một hình placeholder mới vào slide bố cục để chứa hình ảnh trực tuyến.

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
| x | float | Tọa độ X của hình placeholder mới. |
| y | float | Tọa độ Y của hình placeholder mới. |
| width | float | Chiều rộng của hình placeholder mới. |
| height | float | Chiều cao của hình placeholder mới. |

**Giá trị trả về:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Được tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một placeholder Hình ảnh trực tuyến.