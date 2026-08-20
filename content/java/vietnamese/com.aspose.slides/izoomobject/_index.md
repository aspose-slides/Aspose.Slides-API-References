---
title: IZoomObject
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một đối tượng Zoom trong slide.
type: docs
url: /vi/com.aspose.slides/izoomobject/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphularObject
```

Biểu diễn một đối tượng Zoom trong slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getImageType()](#getImageType--) | Lấy hoặc đặt loại hình ảnh của một đối tượng zoom. |
| [setImageType(int value)](#setImageType-int-) | Lấy hoặc đặt loại hình ảnh của một đối tượng zoom. |
| [getReturnToParent()](#getReturnToParent--) | Lấy hoặc đặt hành vi điều hướng trong trình chiếu. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Lấy hoặc đặt hành vi điều hướng trong trình chiếu. |
| [getShowBackground()](#getShowBackground--) | Lấy hoặc đặt giá trị xác định xem Zoom có sử dụng nền của slide đích hay không. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Lấy hoặc đặt giá trị xác định xem Zoom có sử dụng nền của slide đích hay không. |
| [getZoomImage()](#getZoomImage--) | Lấy hoặc đặt hình ảnh cho đối tượng zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Lấy hoặc đặt hình ảnh cho đối tượng zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | Lấy hoặc đặt thời lượng chuyển đổi giữa Zoom và slide. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Lấy hoặc đặt thời lượng chuyển đổi giữa Zoom và slide. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```


Lấy hoặc đặt loại hình ảnh của một đối tượng zoom. Đọc/ghi [ZoomImageType](../../com.aspose.slides/zoomimagetype). Giá trị mặc định: Preview

--------------------

> ```
> Ví dụ này minh họa việc thay đổi Image Type thành giá trị Preview. 
>  Trong trường hợp này, hình ảnh hiện tại của đối tượng Zoom sẽ thay đổi thành hình ảnh slide:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Xác định xem đối tượng Zoom có đang sử dụng bản xem trước slide hay hình ảnh bìa hay không.

**Trả về:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```


Lấy hoặc đặt loại hình ảnh của một đối tượng zoom. Đọc/ghi [ZoomImageType](../../com.aspose.slides/zoomimagetype). Giá trị mặc định: Preview

--------------------

> ```
> Ví dụ này minh họa việc thay đổi Image Type thành giá trị Preview. 
>  Trong trường hợp này, hình ảnh hiện tại của đối tượng Zoom sẽ thay đổi thành hình ảnh slide:
>  
  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Xác định xem đối tượng Zoom có đang sử dụng bản xem trước slide hay hình ảnh bìa hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
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

Giá trị true của thuộc tính xác định hành vi điều hướng quay về cha trong trình chiếu.

**Trả về:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
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

Giá trị true của thuộc tính xác định hành vi điều hướng quay về cha trong trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```


Lấy hoặc đặt giá trị xác định xem Zoom có sử dụng nền của slide đích hay không. Đọc/ghi boolean. Giá trị mặc định: true

--------------------

> ```
> Ví dụ minh họa việc loại bỏ nền của hình ảnh của đối tượng Zoom:
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
public abstract void setShowBackground(boolean value)
```


Lấy hoặc đặt giá trị xác định xem Zoom có sử dụng nền của slide đích hay không. Đọc/ghi boolean. Giá trị mặc định: true

--------------------

> ```
> Ví dụ minh họa việc loại bỏ nền của hình ảnh của đối tượng Zoom:
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
public abstract IPPImage getZoomImage()
```


Lấy hoặc đặt hình ảnh cho đối tượng zoom. Đọc/ghi [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Ví dụ minh họa việc thay đổi hình ảnh của một đối tượng Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      zoomFrame.setImage(image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```


Lấy hoặc đặt hình ảnh cho đối tượng zoom. Đọc/ghi [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Ví dụ minh họa việc thay đổi hình ảnh của một đối tượng Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      zoomFrame.setImage(image);
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
public abstract float getTransitionDuration()
```


Lấy hoặc đặt thời lượng chuyển đổi giữa Zoom và slide. Đọc/ghi float. Giá trị mặc định: 1.0f

--------------------

> ```
> ví dụ minh họa việc thay đổi thời lượng chuyển đổi giữa Zoom và slide:
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

Nếu không được chỉ định (TransitionDur = 0), sẽ sử dụng chuyển tiếp của slide đích và thời gian liên quan đến chuyển tiếp đó.

**Trả về:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```


Lấy hoặc đặt thời lượng chuyển đổi giữa Zoom và slide. Đọc/ghi float. Giá trị mặc định: 1.0f

--------------------

> ```
> ví dụ minh họa việc thay đổi thời lượng chuyển đổi giữa Zoom và slide:
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

Nếu không được chỉ định (TransitionDur = 0), sẽ sử dụng chuyển tiếp của slide đích và thời gian liên quan đến chuyển tiếp đó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |