---
title: IGifOptions
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Đại diện cho các tùy chọn xuất GIF.
type: docs
url: /vi/com.aspose.slides/igifoptions/
---
**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

Đại diện cho các tùy chọn xuất GIF.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Lấy hoặc đặt kích thước khung hình. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Lấy hoặc đặt kích thước khung hình. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Xác định liệu các slide ẩn có được xuất hay không. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Xác định liệu các slide ẩn có được xuất hay không. |
| [getTransitionFps()](#getTransitionFps--) | Lấy hoặc đặt FPS chuyển đổi [khung/giây] Giá trị mặc định là 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Lấy hoặc đặt FPS chuyển đổi [khung/giây] Giá trị mặc định là 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Lấy hoặc đặt thời gian trễ mặc định [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Lấy hoặc đặt thời gian trễ mặc định [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Size getFrameSize()
```


Lấy hoặc đặt kích thước khung hình.

--------------------

Nếu kích thước trống thì giá trị sẽ được lấy từ [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Trả về:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public abstract void setFrameSize(Size value)
```


Lấy hoặc đặt kích thước khung hình.

--------------------

Nếu kích thước trống thì giá trị sẽ được lấy từ [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
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


**Trả về:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
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
public abstract int getTransitionFps()
```


Lấy hoặc đặt FPS chuyển đổi [khung/giây] Giá trị mặc định là 25.

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
public abstract void setTransitionFps(int value)
```


Lấy hoặc đặt FPS chuyển đổi [khung/giây] Giá trị mặc định là 25.

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
public abstract int getDefaultDelay()
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
public abstract void setDefaultDelay(int value)
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