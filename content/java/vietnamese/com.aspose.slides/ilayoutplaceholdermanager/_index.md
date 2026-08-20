---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Java API Reference
description: Represents manager that allows you to add placeholders to the layout slide.
type: docs
url: /vi/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

Biểu diễn trình quản lý cho phép bạn thêm các placeholder vào slide bố cục.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Thêm một hình placeholder mới vào slide bố cục để chứa nội dung, chẳng hạn như hình ảnh, bảng, phương tiện hoặc văn bản. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Thêm một hình placeholder mới vào slide bố cục để chứa nội dung, chẳng hạn như hình ảnh, bảng, phương tiện hoặc văn bản theo chiều dọc. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Thêm một hình placeholder mới vào slide bố cục để chứa nội dung văn bản. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Thêm một hình placeholder mới vào slide bố cục để chứa nội dung văn bản theo chiều dọc. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Thêm một hình placeholder mới vào slide bố cục để chứa một hình ảnh. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Thêm một hình placeholder mới vào slide bố cục để chứa một biểu đồ. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Thêm một hình placeholder mới vào slide bố cục để chứa một bảng. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Thêm một hình placeholder mới vào slide bố cục để chứa một sơ đồ SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Thêm một hình placeholder mới vào slide bố cục để chứa một đối tượng phương tiện. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Thêm một hình placeholder mới vào slide bố cục để chứa một hình ảnh trực tuyến. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Thêm một hình placeholder mới vào slide bố cục để chứa nội dung, chẳng hạn như hình ảnh, bảng, phương tiện hoặc văn bản.

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  
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
| width | float | Độ rộng của hình placeholder mới. |
| height | float | Độ cao của hình placeholder mới. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Được tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một placeholder loại Content.  
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
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
| width | float | Độ rộng của hình placeholder mới. |
| height | float | Độ cao của hình placeholder mới. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Được tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một placeholder Content (Chiều dọc).  
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
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
| width | float | Độ rộng của hình placeholder mới. |
| height | float | Độ cao của hình placeholder mới. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Được tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một placeholder loại Text.  
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Thêm một hình placeholder mới vào slide bố cục để chứa nội dung văn bản theo chiều dọc.

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalTextPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| x | float | Tọa độ X của hình placeholder mới. |
| y | float | Tọa độ Y của hình placeholder mới. |
| width | float | Độ rộng của hình placeholder mới. |
| height | float | Độ cao của hình placeholder mới. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Được tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một placeholder Text (Chiều dọc).  
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Thêm một hình placeholder mới vào slide bố cục để chứa một hình ảnh.

--------------------

> ```
> Ví dụ sau cho thấy cách thêm hình placeholder Picture vào slide bố cục.
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
| width | float | Độ rộng của hình placeholder mới. |
| height | float | Độ cao của hình placeholder mới. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Được tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một placeholder hình ảnh.  
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Thêm một hình placeholder mới vào slide bố cục để chứa một biểu đồ.

--------------------

> ```
> Ví dụ sau cho thấy cách thêm hình placeholder Chart vào slide bố cục.
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
| width | float | Độ rộng của hình placeholder mới. |
| height | float | Độ cao của hình placeholder mới. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Được tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một placeholder biểu đồ.  
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Thêm một hình placeholder mới vào slide bố cục để chứa một bảng.

--------------------

> ```
> Ví dụ sau cho thấy cách thêm hình placeholder Table vào slide bố cục.
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
| width | float | Độ rộng của hình placeholder mới. |
| height | float | Độ cao của hình placeholder mới. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Được tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một placeholder bảng.  
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Thêm một hình placeholder mới vào slide bố cục để chứa một sơ đồ SmartArt.

--------------------

> ```
> Ví dụ sau cho thấy cách thêm hình placeholder SmartArt vào slide bố cục.
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
| width | float | Độ rộng của hình placeholder mới. |
| height | float | Độ cao của hình placeholder mới. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Được tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một placeholder SmartArt.  
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Thêm một hình placeholder mới vào slide bố cục để chứa một đối tượng phương tiện.

--------------------

> ```
> Ví dụ sau cho thấy cách thêm hình placeholder Media vào slide bố cục.
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
| width | float | Độ rộng của hình placeholder mới. |
| height | float | Độ cao của hình placeholder mới. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Được tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một placeholder phương tiện.  
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Thêm một hình placeholder mới vào slide bố cục để chứa một hình ảnh trực tuyến.

--------------------

> ```
> Ví dụ sau cho thấy cách thêm hình placeholder Online Image vào slide bố cục.
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
| width | float | Độ rộng của hình placeholder mới. |
| height | float | Độ cao của hình placeholder mới. |

**Giá trị trả về:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Được tạo [IAutoShape](../../com.aspose.slides/iautoshape) với một placeholder hình ảnh trực tuyến.