---
title: SlideShowSettings
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn các cài đặt trình chiếu cho bài thuyết trình.
type: docs
url: /vi/com.aspose.slides/slideshowsettings/
---
**Kế thừa:**
java.lang.Object
```
public class SlideShowSettings
```

Biểu diễn các cài đặt trình chiếu cho bài thuyết trình.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | Lấy hoặc đặt loại trình chiếu. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | Lấy hoặc đặt loại trình chiếu. |
| [getLoop()](#getLoop--) | Trình chiếu vòng lặp |
| [setLoop(boolean value)](#setLoop-boolean-) | Trình chiếu vòng lặp |
| [getShowNarration()](#getShowNarration--) | Hiển thị lời thuyết minh trong trình chiếu |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Hiển thị lời thuyết minh trong trình chiếu |
| [getShowAnimation()](#getShowAnimation--) | Hiển thị hoạt ảnh trong trình chiếu |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Hiển thị hoạt ảnh trong trình chiếu |
| [getPenColor()](#getPenColor--) | Màu bút cho trình chiếu |
| [getSlides()](#getSlides--) | Phạm vi slide |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Phạm vi slide |
| [getUseTimings()](#getUseTimings--) | Sử dụng thời gian trong trình chiếu |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Sử dụng thời gian trong trình chiếu |
| [getShowMediaControls()](#getShowMediaControls--) | Hiển thị điều khiển media |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Hiển thị điều khiển media |

### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

Lấy hoặc đặt loại trình chiếu. Được đại diện bởi SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) các tổ tiên: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) và [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // để đặt loại "Browsed at a kiosk (full screen)" type
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // để đặt loại "Browsed by individual (window)" type
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // để đặt loại "Presented by a speaker (full screen)" type
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
[SlideShowType](../../com.aspose.slides/slideshowtype)

### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

Lấy hoặc đặt loại trình chiếu. Được đại diện bởi SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) các tổ tiên: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) và [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // để đặt loại "Browsed at a kiosk (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // để đặt loại "Browsed by individual (window)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // để đặt loại "Presented by a speaker (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```

Trình chiếu vòng lặp

**Trả về:**
boolean

### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

Trình chiếu vòng lặp

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

Hiển thị lời thuyết minh trong trình chiếu

**Trả về:**
boolean

### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

Hiển thị lời thuyết minh trong trình chiếu

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

Hiển thị hoạt ảnh trong trình chiếu

**Trả về:**
boolean

### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

Hiển thị hoạt ảnh trong trình chiếu

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

Màu bút cho trình chiếu

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```

Phạm vi slide

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SlidesRange slidesRange = new SlidesRange();
>      slidesRange.setStart(1);
>      slidesRange.setEnd(3);
>      pres.getSlideShowSettings().setSlides(slidesRange);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
[SlidesRange](../../com.aspose.slides/slidesrange)

### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```

Phạm vi slide

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SlidesRange slidesRange = new SlidesRange();
>      slidesRange.setStart(1);
>      slidesRange.setEnd(3);
>      pres.getSlideShowSettings().setSlides(slidesRange);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```

Sử dụng thời gian trong trình chiếu

**Trả về:**
boolean

### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

Sử dụng thời gian trong trình chiếu

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```

Hiển thị điều khiển media

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
boolean

### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```

Hiển thị điều khiển media

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |