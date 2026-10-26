---
title: ZoomObject
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một đối tượng Zoom trong slide.
type: docs
url: /vi/com.aspose.slides/zoomobject/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

Đại diện cho một đối tượng Zoom trong slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getImageType()](#getImageType--) | Lấy hoặc đặt loại hình ảnh của đối tượng Zoom. |
| [setImageType(int value)](#setImageType-int-) | Lấy hoặc đặt loại hình ảnh của đối tượng Zoom. |
| [getReturnToParent()](#getReturnToParent--) | Lấy hoặc đặt hành vi điều hướng trong trình chiếu. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Lấy hoặc đặt hành vi điều hướng trong trình chiếu. |
| [getShowBackground()](#getShowBackground--) | Lấy hoặc đặt giá trị xác định liệu Zoom có sử dụng nền của slide đích hay không. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Lấy hoặc đặt giá trị xác định liệu Zoom có sử dụng nền của slide đích hay không. |
| [getZoomImage()](#getZoomImage--) | Lấy hoặc đặt hình ảnh cho đối tượng Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Lấy hoặc đặt hình ảnh cho đối tượng Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | Lấy hoặc đặt thời gian chuyển đổi giữa Zoom và slide. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Lấy hoặc đặt thời gian chuyển đổi giữa Zoom và slide. |
### getImageType() {#getImageType--}
```
public final int getImageType()
```


Lấy hoặc đặt loại hình ảnh của đối tượng Zoom. Đọc/ghi [ZoomImageType](../../com.aspose.slides/zoomimagetype). Giá trị mặc định: Preview

--------------------

> ```
> Ví dụ tiếp theo minh họa cách thay đổi Image Type thành giá trị Preview. 
>  Trong trường hợp này hình ảnh hiện tại của đối tượng Zoom sẽ thay đổi thành hình ảnh của slide:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Xác định liệu đối tượng Zoom có sử dụng bản xem trước của slide hay một hình ảnh bìa hay không.

**Trả về:** 
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```


Lấy hoặc đặt loại hình ảnh của đối tượng Zoom. Đọc/ghi [ZoomImageType](../../com.aspose.slides/zoomimagetype). Giá trị mặc định: Preview

--------------------

> ```
> Ví dụ tiếp theo minh họa việc thay đổi Image Type thành giá trị Preview. 
>  Trong trường hợp này hình ảnh hiện tại của đối tượng Zoom sẽ thay đổi thành hình ảnh của slide:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Xác định liệu đối tượng Zoom có sử dụng bản xem trước của slide hay một hình ảnh bìa hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```


Lấy hoặc đặt hành vi điều hướng trong trình chiếu. Đọc/ghi boolean. Giá trị mặc định: false

--------------------

> ```
> Ví dụ:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Giá trị true của thuộc tính chỉ định hành vi quay lại cha trong trình chiếu.

**Trả về:** 
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```


Lấy hoặc đặt hành vi điều hướng trong trình chiếu. Đọc/ghi boolean. Giá trị mặc định: false

--------------------

> ```
> Ví dụ:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Giá trị true của thuộc tính chỉ định hành vi quay lại cha trong trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```


Lấy hoặc đặt giá trị xác định liệu Zoom có sử dụng nền của slide đích hay không. Đọc/ghi boolean. Giá trị mặc định: true

--------------------

> ```
> Ví dụ này minh họa việc loại bỏ nền của hình ảnh của một đối tượng Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:** 
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public final void setShowBackground(boolean value)
```


Lấy hoặc đặt giá trị xác định liệu Zoom có sử dụng nền của slide đích hay không. Đọc/ghi boolean. Giá trị mặc định: true

--------------------

> ```
> Ví dụ này minh họa việc loại bỏ nền của hình ảnh của một đối tượng Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getZoomImage() {#getZoomImage--}
```
public final IPPImage getZoomImage()
```


Lấy hoặc đặt hình ảnh cho đối tượng Zoom. Đọc/ghi [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Ví dụ này minh họa việc thay đổi hình ảnh của một đối tượng Zoom:
>  
  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:** 
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```


Lấy hoặc đặt hình ảnh cho đối tượng Zoom. Đọc/ghi [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Ví dụ này minh họa việc thay đổi hình ảnh của một đối tượng Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getTransitionDuration() {#getTransitionDuration--}
```
public final float getTransitionDuration()
```


Lấy hoặc đặt thời gian chuyển đổi giữa Zoom và slide. Đọc/ghi float. Giá trị mặc định: 1.0f

--------------------

> ```
> Ví dụ này minh họa việc thay đổi thời lượng chuyển đổi giữa Zoom và slide:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Nếu không được chỉ định (TransitionDur = 0), nó sẽ sử dụng chuyển đổi slide đích và thời gian liên quan tới chuyển đổi đó.

**Trả về:** 
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```


Lấy hoặc đặt thời gian chuyển đổi giữa Zoom và slide. Đọc/ghi float. Giá trị mặc định: 1.0f

--------------------

> ```
> ví dụ này minh họa việc thay đổi thời lượng chuyển đổi giữa Zoom và slide:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Nếu không được chỉ định (TransitionDur = 0), nó sẽ sử dụng chuyển đổi slide đích và thời gian liên quan tới chuyển đổi đó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |