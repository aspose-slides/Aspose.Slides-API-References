---
title: IGifOptions
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn các tùy chọn xuất GIF.
type: docs
url: /vi/com.aspose.slides/igifoptions/
---
**Tất cả các giao diện được thực thi:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

Biểu diễn các tùy chọn xuất GIF.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Lấy hoặc đặt kích thước khung. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | Lấy hoặc đặt kích thước khung. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Xác định xem các slide ẩn có được xuất hay không. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Xác định xem các slide ẩn có được xuất hay không. |
| [getTransitionFps()](#getTransitionFps--) | Lấy hoặc đặt FPS chuyển đổi [frames/sec] Giá trị mặc định là 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Lấy hoặc đặt FPS chuyển đổi [frames/sec] Giá trị mặc định là 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Lấy hoặc đặt thời gian trễ mặc định [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Lấy hoặc đặt thời gian trễ mặc định [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Dimension getFrameSize()
```

Lấy hoặc đặt kích thước khung.

--------------------

Nếu kích thước trống thì giá trị sẽ được lấy từ [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Trả về:**
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public abstract void setFrameSize(Dimension value)
```

Lấy hoặc đặt kích thước khung.

--------------------

Nếu kích thước trống thì giá trị sẽ được lấy từ [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.awt.Dimension |  |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
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
public abstract void setExportHiddenSlides(boolean value)
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
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getTransitionFps() {#getTransitionFps--}
```
public abstract int getTransitionFps()
```

Lấy hoặc đặt FPS chuyển đổi [frames/sec] Giá trị mặc định là 25.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public abstract void setTransitionFps(int value)
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