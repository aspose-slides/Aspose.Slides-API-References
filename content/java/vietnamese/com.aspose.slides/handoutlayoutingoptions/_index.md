---
title: HandoutLayoutingOptions
second_title: Tham chiếu API Aspose.Slides cho Java
description: Mô tả chế độ bố cục bản in cho bài thuyết trình khi xuất.
type: docs
url: /vi/com.aspose.slides/handoutlayoutingoptions/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class HandoutLayoutingOptions implements ISlidesLayoutOptions
```

Mô tả chế độ bố cục bản in cho bài thuyết trình khi xuất.
## Các hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [HandoutLayoutingOptions()](#HandoutLayoutingOptions--) | Khởi tạo các giá trị mặc định. |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getHandout()](#getHandout--) | Xác định số slide và thứ tự chúng sẽ được đặt trên trang [HandoutType](../../com.aspose.slides/handouttype). |
| [setHandout(int value)](#setHandout-int-) | Xác định số slide và thứ tự chúng sẽ được đặt trên trang [HandoutType](../../com.aspose.slides/handouttype). |
| [getPrintSlideNumbers()](#getPrintSlideNumbers--) | Xác định có in số slide hiển thị hay không. |
| [setPrintSlideNumbers(boolean value)](#setPrintSlideNumbers-boolean-) | Xác định có in số slide hiển thị hay không. |
| [getPrintFrameSlide()](#getPrintFrameSlide--) | Xác định có vẽ khung quanh các slide hiển thị hay không. |
| [setPrintFrameSlide(boolean value)](#setPrintFrameSlide-boolean-) | Xác định có vẽ khung quanh các slide hiển thị hay không. |
| [getPrintComments()](#getPrintComments--) | Xác định có hiển thị bình luận trên slide hay không |
| [setPrintComments(boolean value)](#setPrintComments-boolean-) | Xác định có hiển thị bình luận trên slide hay không |
### HandoutLayoutingOptions() {#HandoutLayoutingOptions--}
```
public HandoutLayoutingOptions()
```


Khởi tạo các giá trị mặc định.

### getHandout() {#getHandout--}
```
public final int getHandout()
```


Xác định số slide và thứ tự chúng sẽ được đặt trên trang [HandoutType](../../com.aspose.slides/handouttype).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Giá trị mặc định là  **HandoutType.Handouts6Horizontal** .

**Trả về:**
int
### setHandout(int value) {#setHandout-int-}
```
public final void setHandout(int value)
```


Xác định số slide và thứ tự chúng sẽ được đặt trên trang [HandoutType](../../com.aspose.slides/handouttype).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Giá trị mặc định là  **HandoutType.Handouts6Horizontal** .

**Tham số:**
| Tham số | Type | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPrintSlideNumbers() {#getPrintSlideNumbers--}
```
public final boolean getPrintSlideNumbers()
```


Xác định có in số slide hiển thị hay không.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Giá trị mặc định là  **true** .

**Trả về:**
boolean
### setPrintSlideNumbers(boolean value) {#setPrintSlideNumbers-boolean-}
```
public final void setPrintSlideNumbers(boolean value)
```


Xác định có in số slide hiển thị hay không.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Giá trị mặc định là  **true** .

**Tham số:**
| Tham số | Type | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getPrintFrameSlide() {#getPrintFrameSlide--}
```
public final boolean getPrintFrameSlide()
```


Xác định có vẽ khung quanh các slide hiển thị hay không.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintFrameSlide(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Giá trị mặc định là  **true** .

**Trả về:**
boolean
### setPrintFrameSlide(boolean value) {#setPrintFrameSlide-boolean-}
```
public final void setPrintFrameSlide(boolean value)
```


Xác định có vẽ khung quanh các slide hiển thị hay không.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintFrameSlide(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Giá trị mặc định là  **true** .

**Tham số:**
| Tham số | Type | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getPrintComments() {#getPrintComments--}
```
public final boolean getPrintComments()
```


Xác định có hiển thị bình luận trên slide hay không

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintComments(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Giá trị mặc định là  **false** .

**Trả về:**
boolean
### setPrintComments(boolean value) {#setPrintComments-boolean-}
```
public final void setPrintComments(boolean value)
```


Xác định có hiển thị bình luận trên slide hay không

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintComments(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Giá trị mặc định là  **false** .

**Tham số:**
| Tham số | Type | Mô tả |
| --- | --- | --- |
| value | boolean |  |