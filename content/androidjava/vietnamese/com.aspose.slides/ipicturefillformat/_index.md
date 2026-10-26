---
title: IPictureFillFormat
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Đại diện cho kiểu tô ảnh.
type: docs
url: /vi/com.aspose.slides/ipicturefillformat/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

Đại diện cho kiểu tô ảnh.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getDpi()](#getDpi--) | Trả về hoặc thiết lập dpi được sử dụng để tô một hình ảnh. |
| [setDpi(int value)](#setDpi-int-) | Trả về hoặc thiết lập dpi được sử dụng để tô một hình ảnh. |
| [getPictureFillMode()](#getPictureFillMode--) | Trả về hoặc thiết lập chế độ tô ảnh. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Trả về hoặc thiết lập chế độ tô ảnh. |
| [getPicture()](#getPicture--) | Trả về hình ảnh. |
| [getCropLeft()](#getCropLeft--) | Trả về hoặc thiết lập số phần trăm chiều rộng thực của ảnh bị cắt bỏ ở phía bên trái của hình ảnh. |
| [setCropLeft(float value)](#setCropLeft-float-) | Trả về hoặc thiết lập số phần trăm chiều rộng thực của ảnh bị cắt bỏ ở phía bên trái của hình ảnh. |
| [getCropTop()](#getCropTop--) | Trả về hoặc thiết lập số phần trăm chiều cao thực của ảnh bị cắt bỏ ở phía trên của hình ảnh. |
| [setCropTop(float value)](#setCropTop-float-) | Trả về hoặc thiết lập số phần trăm chiều cao thực của ảnh bị cắt bỏ ở phía trên của hình ảnh. |
| [getCropRight()](#getCropRight--) | Trả về hoặc thiết lập số phần trăm chiều rộng thực của ảnh bị cắt bỏ ở phía bên phải của hình ảnh. |
| [setCropRight(float value)](#setCropRight-float-) | Trả về hoặc thiết lập số phần trăm chiều rộng thực của ảnh bị cắt bỏ ở phía bên phải của hình ảnh. |
| [getCropBottom()](#getCropBottom--) | Trả về hoặc thiết lập số phần trăm chiều cao thực của ảnh bị cắt bỏ ở phía dưới của hình ảnh. |
| [setCropBottom(float value)](#setCropBottom-float-) | Trả về hoặc thiết lập số phần trăm chiều cao thực của ảnh bị cắt bỏ ở phía dưới của hình ảnh. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Trả về hoặc thiết lập cạnh trái của hình chữ nhật tô được xác định bằng khoảng lệch phần trăm từ cạnh trái của hộp giới hạn của hình dạng. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Trả về hoặc thiết lập cạnh trái của hình chữ nhật tô được xác định bằng khoảng lệch phần trăm từ cạnh trái của hộp giới hạn của hình dạng. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Trả về hoặc thiết lập cạnh trên của hình chữ nhật tô được xác định bằng khoảng lệch phần trăm từ cạnh trên của hộp giới hạn của hình dạng. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Trả về hoặc thiết lập cạnh trên của hình chữ nhật tô được xác định bằng khoảng lệch phần trăm từ cạnh trên của hộp giới hạn của hình dạng. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Trả về hoặc thiết lập cạnh phải của hình chữ nhật tô được xác định bằng khoảng lệch phần trăm từ cạnh phải của hộp giới hạn của hình dạng. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Trả về hoặc thiết lập cạnh phải của hình chữ nhật tô được xác định bằng khoảng lệch phần trăm từ cạnh phải của hộp giới hạn của hình dạng. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Trả về hoặc thiết lập cạnh dưới của hình chữ nhật tô được xác định bằng khoảng lệch phần trăm từ cạnh dưới của hộp giới hạn của hình dạng. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Trả về hoặc thiết lập cạnh dưới của hình chữ nhật tô được xác định bằng khoảng lệch phần trăm từ cạnh dưới của hộp giới hạn của hình dạng. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Xóa các khu vực đã cắt của hình ảnh được tô. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Nén ảnh bằng cách giảm kích thước dựa trên kích thước của hình dạng và độ phân giải đã chỉ định. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Nén ảnh bằng cách giảm kích thước dựa trên kích thước của hình dạng và độ phân giải đã chỉ định. |
| [getTileOffsetX()](#getTileOffsetX--) | Trả về hoặc thiết lập độ lệch ngang của họa tiết từ gốc của hình dạng tính bằng điểm. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Trả về hoặc thiết lập độ lệch ngang của họa tiết từ gốc của hình dạng tính bằng điểm. |
| [getTileOffsetY()](#getTileOffsetY--) | Trả về hoặc thiết lập độ lệch dọc của họa tiết từ gốc của hình dạng tính bằng điểm. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Trả về hoặc thiết lập độ lệch dọc của họa tiết từ gốc của hình dạng tính bằng điểm. |
| [getTileScaleX()](#getTileScaleX--) | Trả về hoặc thiết lập tỉ lệ ngang cho việc tô họa tiết dưới dạng phần trăm. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Trả về hoặc thiết lập tỉ lệ ngang cho việc tô họa tiết dưới dạng phần trăm. |
| [getTileScaleY()](#getTileScaleY--) | Trả về hoặc thiết lập tỉ lệ dọc cho việc tô họa tiết dưới dạng phần trăm. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Trả về hoặc thiết lập tỉ lệ dọc cho việc tô họa tiết dưới dạng phần trăm. |
| [getTileAlignment()](#getTileAlignment--) | Trả về hoặc thiết lập cách mà họa tiết được căn chỉnh bên trong hình dạng. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Trả về hoặc thiết lập cách mà họa tiết được căn chỉnh bên trong hình dạng. |
| [getTileFlip()](#getTileFlip--) | Lật khối họa tiết xung quanh trục ngang, dọc hoặc cả hai. |
| [setTileFlip(int value)](#setTileFlip-int-) | Lật khối họa tiết xung quanh trục ngang, dọc hoặc cả hai. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Trả về hoặc thiết lập dpi được sử dụng để tô một hình ảnh. **Đọc/ghi** int.

**Trả về:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

Trả về hoặc thiết lập dpi được sử dụng để tô một hình ảnh. **Đọc/ghi** int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Trả về hoặc thiết lập chế độ tô ảnh. **Đọc/ghi** [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Trả về:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

Trả về hoặc thiết lập chế độ tô ảnh. **Đọc/ghi** [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Trả về hình ảnh. **Chỉ đọc** [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Trả về:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Trả về hoặc thiết lập số phần trăm chiều rộng thực của ảnh bị cắt bỏ ở phía bên trái của hình ảnh. **Đọc/ghi** float.

**Trả về:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

Trả về hoặc thiết lập số phần trăm chiều rộng thực của ảnh bị cắt bỏ ở phía bên trái của hình ảnh. **Đọc/ghi** float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Trả về hoặc thiết lập số phần trăm chiều cao thực của ảnh bị cắt bỏ ở phía trên của hình ảnh. **Đọc/ghi** float.

**Trả về:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

Trả về hoặc thiết lập số phần trăm chiều cao thực của ảnh bị cắt bỏ ở phía trên của hình ảnh. **Đọc/ghi** float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Trả về hoặc thiết lập số phần trăm chiều rộng thực của ảnh bị cắt bỏ ở phía bên phải của hình ảnh. **Đọc/ghi** float.

**Trả về:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

Trả về hoặc thiết lập số phần trăm chiều rộng thực của ảnh bị cắt bỏ ở phía bên phải của hình ảnh. **Đọc/ghi** float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Trả về hoặc thiết lập số phần trăm chiều cao thực của ảnh bị cắt bỏ ở phía dưới của hình ảnh. **Đọc/ghi** float.

**Trả về:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

Trả về hoặc thiết lập số phần trăm chiều cao thực của ảnh bị cắt bỏ ở phía dưới của hình ảnh. **Đọc/ghi** float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

Trả về hoặc thiết lập cạnh trái của hình chữ nhật tô được xác định bằng khoảng lệch phần trăm từ cạnh trái của hộp giới hạn của hình dạng. Một phần trăm dương chỉ ra việc chèn vào, trong khi phần trăm âm chỉ ra việc mở ra. **Đọc/ghi** float.

**Trả về:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

Trả về hoặc thiết lập cạnh trái của hình chữ nhật tô được xác định bằng khoảng lệch phần trăm từ cạnh trái của hộp giới hạn của hình dạng. Một phần trăm dương chỉ ra việc chèn vào, trong khi phần trăm âm chỉ ra việc mở ra. **Đọc/ghi** float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

Trả về hoặc thiết lập cạnh trên của hình chữ nhật tô được xác định bằng khoảng lệch phần trăm từ cạnh trên của hộp giới hạn của hình dạng. Một phần trăm dương chỉ ra việc chèn vào, trong khi phần trăm âm chỉ ra việc mở ra. **Đọc/ghi** float.

**Trả về:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

Trả về hoặc thiết lập cạnh trên của hình chữ nhật tô được xác định bằng khoảng lệch phần trăm từ cạnh trên của hộp giới hạn của hình dạng. Một phần trăm dương chỉ ra việc chèn vào, trong khi phần trăm âm chỉ ra việc mở ra. **Đọc/ghi** float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

Trả về hoặc thiết lập cạnh phải của hình chữ nhật tô được xác định bằng khoảng lệch phần trăm từ cạnh phải của hộp giới hạn của hình dạng. Một phần trăm dương chỉ ra việc chèn vào, trong khi phần trăm âm chỉ ra việc mở ra. **Đọc/ghi** float.

**Trả về:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

Trả về hoặc thiết lập cạnh phải của hình chữ nhật tô được xác định bằng khoảng lệch phần trăm từ cạnh phải của hộp giới hạn của hình dạng. Một phần trăm dương chỉ ra việc chèn vào, trong khi phần trăm âm chỉ ra việc mở ra. **Đọc/ghi** float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

Trả về hoặc thiết lập cạnh dưới của hình chữ nhật tô được xác định bằng khoảng lệch phần trăm từ cạnh dưới của hộp giới hạn của hình dạng. Một phần trăm dương chỉ ra việc chèn vào, trong khi phần trăm âm chỉ ra việc mở ra. **Đọc/ghi** float.

**Trả về:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

Trả về hoặc thiết lập cạnh dưới của hình chữ nhật tô được xác định bằng khoảng lệch phần trăm từ cạnh dưới của hộp giới hạn của hình dạng. Một phần trăm dương chỉ ra việc chèn vào, trong khi phần trăm âm chỉ ra việc mở ra. **Đọc/ghi** float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

Xóa các khu vực đã cắt của hình ảnh được tô.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Lấy PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Xóa các khu vực đã cắt của ảnh PictureFrame
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage) - Ảnh đã cắt hoặc ảnh gốc nếu không cần cắt.

--------------------

Phương thức này chuyển đổi các tệp metafile WMF/EMF sang ảnh PNG dạng raster đồng thời cắt ảnh.

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Nén ảnh bằng cách giảm kích thước dựa trên kích thước của hình dạng và độ phân giải đã chỉ định. Tùy chọn, nó cũng xóa các khu vực đã cắt.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` method to reduce the size of an image in a presentation by setting a target resolution and removing cropped areas:
>  
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
>      boolean result = picFrame.getPictureFormat().compressImage(true, PicturesCompression.Dpi150);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | If true, the method will remove the cropped areas of the image, potentially further reducing its size. |
| resolution | int | The target resolution for compression, specified as a value of the [PicturesCompression](../../com.aspose.slides/picturescompression) enum.

--------------------

This method changes the image's size and resolution similar to PowerPoint's "Picture Format -> Compress Pictures" feature. |

**Returns:**
boolean - A boolean indicating whether the image was successfully compressed. Returns true if the image was resized or cropped, otherwise false.
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ```
 method to reduce the size of an image in a presentation by setting a target resolution and removing cropped areas:
>   
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
>      boolean result = picFrame.getPictureFormat().compressImage(true, 150f); // Web resolution
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | If true, the method will remove the cropped areas of the image, potentially further reducing its size. |
| resolution | float | The target resolution in DPI. This value must be positive and defines how the image will be resized.

--------------------

This method changes the image's size and resolution similar to PowerPoint's "Picture Format -> Compress Pictures" feature. |

**Returns:**
boolean - A boolean indicating whether the image was successfully compressed. Returns true if the image was resized or cropped, otherwise false.
### getTileOffsetX() {#getTileOffsetX--}
```
public abstract float getTileOffsetX()
```


Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal offset of the texture to 20 points
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Trả về:**
float
### setTileOffsetX(float value) {#setTileOffsetX-float-}
```
public abstract void setTileOffsetX(float value)
```


Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal offset of the texture to 20 points
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getTileOffsetY() {#getTileOffsetY--}
```
public abstract float getTileOffsetY()
```


Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical offset of the texture to -50 points
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Trả về:**
float
### setTileOffsetY(float value) {#setTileOffsetY-float-}
```
public abstract void setTileOffsetY(float value)
```


Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical offset of the texture to -50 points
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getTileScaleX() {#getTileScaleX--}
```
public abstract float getTileScaleX()
```


Returns or sets the horizontal scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Trả về:**
float
### setTileScaleX(float value) {#setTileScaleX-float-}
```
public abstract void setTileScaleX(float value)
```


Returns or sets the horizontal scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileScaleY() {#getTileScaleY--}
```
public abstract float getTileScaleY()
```


Returns or sets the vertical scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Returns:**
float
### setTileScaleY(float value) {#setTileScaleY-float-}
```
public abstract void setTileScaleY(float value)
```


Returns or sets the vertical scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getTileAlignment() {#getTileAlignment--}
```
public abstract byte getTileAlignment()
```


Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the alignment for the tiling to the right bottom
>      pictureFillFormat.setTileAlignment(RectangleAlignment.BottomRight);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
--------------------

Default is [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Returns:**
byte
### setTileAlignment(byte value) {#setTileAlignment-byte-}
```
public abstract void setTileAlignment(byte value)
```


Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the alignment for the tiling to the right bottom
>      pictureFillFormat.setTileAlignment(RectangleAlignment.BottomRight);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Default is [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```


Flips the texture tile around its horizontal, vertical or both axis. Read/write [TileFlip](../../com.aspose.slides/tileflip).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Flips the texture tile around its vertical axis.
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Default is [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Returns:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public abstract void setTileFlip(int value)
```


Flips the texture tile around its horizontal, vertical or both axis. Read/write [TileFlip](../../com.aspose.slides/tileflip).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Flips the texture tile around its vertical axis.
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Mặc định là [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |