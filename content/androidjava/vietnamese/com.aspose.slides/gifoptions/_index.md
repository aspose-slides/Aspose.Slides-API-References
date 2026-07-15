---
title: GifOptions
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Đại diện các tùy chọn xuất GIF.
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

Đại diện các tùy chọn xuất GIF.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // kích thước của GIF kết quả
>      gifOptions.setDefaultDelay(2000); // thời gian mỗi slide sẽ hiển thị cho đến khi chuyển sang slide tiếp theo
>      gifOptions.setTransitionFps(35); // tăng FPS để cải thiện chất lượng chuyển động chuyển tiếp
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Hàm tạo

| Constructor | Description |
| --- | --- |
| [GifOptions()](#GifOptions--) | Khởi tạo một thể hiện mới của lớp GifOptions. |
## Phương thức

| Method | Description |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Lấy hoặc đặt kích thước khung. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Lấy hoặc đặt kích thước khung. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Xác định xem các slide ẩn có được xuất hay không. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Xác định xem các slide ẩn có được xuất hay không. |
| [getTransitionFps()](#getTransitionFps--) | Lấy hoặc đặt FPS chuyển tiếp [frames/sec] Giá trị mặc định là 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Lấy hoặc đặt FPS chuyển tiếp [frames/sec] Giá trị mặc định là 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Lấy hoặc đặt thời gian trễ mặc định [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Lấy hoặc đặt thời gian trễ mặc định [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```

Khởi tạo một thể hiện mới của lớp GifOptions.

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```

Lấy hoặc đặt kích thước khung.

--------------------

Nếu kích thước trống thì giá trị sẽ được lấy từ [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Trả về:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
```

Lấy hoặc đặt kích thước khung.

--------------------

Nếu kích thước trống thì giá trị sẽ được lấy từ [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

Xác định xem các slide ẩn có được xuất hay không. Giá trị mặc định là false.

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

**Trả về:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```

Xác định xem các slide ẩn có được xuất hay không. Giá trị mặc định là false.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public final int getTransitionFps()
```

Lấy hoặc đặt FPS chuyển tiếp [frames/sec] Giá trị mặc định là 25.

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

**Trả về:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```

Lấy hoặc đặt FPS chuyển tiếp [frames/sec] Giá trị mặc định là 25.

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
| Parameter | Type | Description |
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

**Trả về:**
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |