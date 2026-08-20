---
title: GifOptions
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho các tùy chọn xuất GIF.
type: docs
url: /vi/com.aspose.slides/gifoptions/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

Đại diện cho các tùy chọn xuất GIF.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new Dimension(960, 720)); // kích thước của GIF kết quả
>      gifOptions.setDefaultDelay(2000); // thời gian mỗi slide sẽ được hiển thị cho tới khi chuyển sang slide tiếp theo
>      gifOptions.setTransitionFps(35); // tăng FPS để cải thiện chất lượng hoạt ảnh chuyển tiếp
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [GifOptions()](#GifOptions--) | Khởi tạo một thể hiện mới của lớp GifOptions. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Lấy hoặc đặt kích thước khung. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | Lấy hoặc đặt kích thước khung. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Xác định liệu các slide ẩn có được xuất hay không. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Xác định liệu các slide ẩn có được xuất hay không. |
| [getTransitionFps()](#getTransitionFps--) | Lấy hoặc đặt FPS chuyển đổi [frames/sec] Giá trị mặc định là 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Lấy hoặc đặt FPS chuyển đổi [frames/sec] Giá trị mặc định là 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Lấy hoặc đặt thời gian trễ mặc định [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Lây hoặc đặt thời gian trễ mặc định [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```

Khởi tạo một thể hiện mới của lớp GifOptions.

### getFrameSize() {#getFrameSize--}
```
public final Dimension getFrameSize()
```

Lấy hoặc đặt kích thước khung.

--------------------

Nếu kích thước trống, giá trị sẽ được lấy từ [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Giá trị trả về:**
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public final void setFrameSize(Dimension value)
```

Lấy hoặc đặt kích thước khung.

--------------------

Nếu kích thước trống, giá trị sẽ được lấy từ [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

Xác định liệu các slide ẩn có được xuất hay không. Giá trị mặc định là false.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setExportHiddenSlides(false);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Giá trị trả về:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```

Xác định liệu các slide ẩn có được xuất hay không. Giá trị mặc định là false.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setExportHiddenSlides(false);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public final int getTransitionFps()
```

Lấy hoặc đặt FPS chuyển đổi [frames/sec] Giá trị mặc định là 25.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Giá trị trả về:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```

Lấy hoặc đặt FPS chuyển đổi [frames/sec] Giá trị mặc định là 25.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```

Lấy hoặc đặt thời gian trễ mặc định [ms]. Giá trị này sẽ được sử dụng nếu [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) không được đặt. Giá trị mặc định là 1000.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setDefaultDelay(2000);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Giá trị trả về:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

Lấy hoặc đặt thời gian trễ mặc định [ms]. Giá trị này sẽ được sử dụng nếu [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) không được đặt. Giá trị mặc định là 1000.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setDefaultDelay(2000);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |