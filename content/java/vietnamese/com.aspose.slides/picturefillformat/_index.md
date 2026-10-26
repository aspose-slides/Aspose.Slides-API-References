---
title: PictureFillFormat
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho kiểu tô đầy bằng hình ảnh.
type: docs
url: /vi/com.aspose.slides/picturefillformat/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

Đại diện cho kiểu tô đầy bằng hình ảnh.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | Trả về hoặc đặt dpi được sử dụng để tô đầy một hình ảnh. |
| [setDpi(int value)](#setDpi-int-) | Trả về hoặc đặt dpi được sử dụng để tô đầy một hình ảnh. |
| [getPictureFillMode()](#getPictureFillMode--) | Trả về hoặc đặt chế độ tô đầy hình ảnh. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Trả về hoặc đặt chế độ tô đầy hình ảnh. |
| [getPicture()](#getPicture--) | Trả về hình ảnh. |
| [getCropLeft()](#getCropLeft--) | Trả về hoặc đặt số phần trăm chiều rộng thực của hình ảnh bị cắt ở phía trái của hình. |
| [setCropLeft(float value)](#setCropLeft-float-) | Trả về hoặc đặt số phần trăm chiều rộng thực của hình ảnh bị cắt ở phía trái của hình. |
| [getCropTop()](#getCropTop--) | Trả về hoặc đặt số phần trăm chiều cao thực của hình ảnh bị cắt ở phía trên của hình. |
| [setCropTop(float value)](#setCropTop-float-) | Trả về hoặc đặt số phần trăm chiều cao thực của hình ảnh bị cắt ở phía trên của hình. |
| [getCropRight()](#getCropRight--) | Trả về hoặc đặt số phần trăm chiều rộng thực của hình ảnh bị cắt ở phía phải của hình. |
| [setCropRight(float value)](#setCropRight-float-) | Trả về hoặc đặt số phần trăm chiều rộng thực của hình ảnh bị cắt ở phía phải của hình. |
| [getCropBottom()](#getCropBottom--) | Trả về hoặc đặt số phần trăm chiều cao thực của hình ảnh bị cắt ở phía dưới của hình. |
| [setCropBottom(float value)](#setCropBottom-float-) | Trả về hoặc đặt số phần trăm chiều cao thực của hình ảnh bị cắt ở phía dưới của hình. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Xóa các vùng đã cắt của hình ảnh tô đầy. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Nén hình ảnh bằng cách giảm kích thước dựa trên kích thước hình dạng và độ phân giải được chỉ định. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Nén hình ảnh bằng cách giảm kích thước dựa trên kích thước hình dạng và độ phân giải được chỉ định. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Trả về hoặc đặt cạnh trái của hình chữ nhật tô đầy được xác định bởi khoảng lệ phần trăm tính từ cạnh trái của hộp bao quanh hình dạng. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Trả về hoặc đặt cạnh trái của hình chữ nhật tô đầy được xác định bởi khoảng lệ phần trăm tính từ cạnh trái của hộp bao quanh hình dạng. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Trả về hoặc đặt cạnh trên của hình chữ nhật tô đầy được xác định bởi khoảng lệ phần trăm tính từ cạnh trên của hộp bao quanh hình dạng. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Trả về hoặc đặt cạnh trên của hình chữ nhật tô đầy được xác định bởi khoảng lệ phần trăm tính từ cạnh trên của hộp bao quanh hình dạng. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Trả về hoặc đặt cạnh phải của hình chữ nhật tô đầy được xác định bởi khoảng lệ phần trăm tính từ cạnh phải của hộp bao quanh hình dạng. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Trả về hoặc đặt cạnh phải của hình chữ nhật tô đầy được xác định bởi khoảng lệ phần trăm tính từ cạnh phải của hộp bao quanh hình dạng. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Trả về hoặc đặt cạnh dưới của hình chữ nhật tô đầy được xác định bởi khoảng lệ phần trăm tính từ cạnh dưới của hộp bao quanh hình dạng. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Trả về hoặc đặt cạnh dưới của hình chữ nhật tô đầy được xác định bởi khoảng lệ phần trăm tính từ cạnh dưới của hộp bao quanh hình dạng. |
| [getTileOffsetX()](#getTileOffsetX--) | Trả về hoặc đặt khoảng dịch chuyển ngang của kết cấu từ gốc của hình dạng tính bằng điểm. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Trả về hoặc đặt khoảng dịch chuyển ngang của kết cấu từ gốc của hình dạng tính bằng điểm. |
| [getTileOffsetY()](#getTileOffsetY--) | Trả về hoặc đặt khoảng dịch chuyển dọc của kết cấu từ gốc của hình dạng tính bằng điểm. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Trả về hoặc đặt khoảng dịch chuyển dọc của kết cấu từ gốc của hình dạng tính bằng điểm. |
| [getTileScaleX()](#getTileScaleX--) | Trả về hoặc đặt tỷ lệ ngang cho việc tô đầy kết cấu dưới dạng phần trăm. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Trả về hoặc đặt tỷ lệ ngang cho việc tô đầy kết cấu dưới dạng phần trăm. |
| [getTileScaleY()](#getTileScaleY--) | Trả về hoặc đặt tỷ lệ dọc cho việc tô đầy kết cấu dưới dạng phần trăm. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Trả về hoặc đặt tỷ lệ dọc cho việc tô đầy kết cấu dưới dạng phần trăm. |
| [getTileAlignment()](#getTileAlignment--) | Trả về hoặc đặt cách căn chỉnh kết cấu bên trong hình dạng. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Trả về hoặc đặt cách căn chỉnh kết cấu bên trong hình dạng. |
| [getTileFlip()](#getTileFlip--) | Lật miếng kết cấu quanh trục ngang, dọc hoặc cả hai. |
| [setTileFlip(int value)](#setTileFlip-int-) | Lật miếng kết cấu quanh trục ngang, dọc hoặc cả hai. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Chỉ đọc long.

**Trả về:**
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

Trả về hoặc đặt dpi được sử dụng để tô đầy một hình ảnh. Đọc/ghi int.

**Trả về:**
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

Trả về hoặc đặt dpi được sử dụng để tô đầy một hình ảnh. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

Trả về hoặc đặt chế độ tô đầy hình ảnh. Đọc/ghi [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Trả về:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

Trả về hoặc đặt chế độ tô đầy hình ảnh. Đọc/ghi [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Trả về hình ảnh. Chỉ đọc [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Trả về:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

Trả về hoặc đặt số phần trăm chiều rộng thực của hình ảnh bị cắt ở phía trái của hình. Đọc/ghi float.

**Trả về:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

Trả về hoặc đặt số phần trăm chiều rộng thực của hình ảnh bị cắt ở phía trái của hình. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

Trả về hoặc đặt số phần trăm chiều cao thực của hình ảnh bị cắt ở phía trên của hình. Đọc/ghi float.

**Trả về:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

Trả về hoặc đặt số phần trăm chiều cao thực của hình ảnh bị cắt ở phía trên của hình. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

Trả về hoặc đặt số phần trăm chiều rộng thực của hình ảnh bị cắt ở phía phải của hình. Đọc/ghi float.

**Trả về:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

Trả về hoặc đặt số phần trăm chiều rộng thực của hình ảnh bị cắt ở phía phải của hình. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

Trả về hoặc đặt số phần trăm chiều cao thực của hình ảnh bị cắt ở phía dưới của hình. Đọc/ghi float.

**Trả về:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

Trả về hoặc đặt số phần trăm chiều cao thực của hình ảnh bị cắt ở phía dưới của hình. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

Xóa các vùng đã cắt của hình ảnh tô đầy.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Lấy PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Xóa các vùng đã cắt của ảnh PictureFrame
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage) - Ảnh đã cắt hoặc ảnh gốc nếu không cần cắt.

--------------------

Phương thức này chuyển đổi các tệp WMF/EMF sang ảnh PNG raster trong khi cắt.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Nén hình ảnh bằng cách giảm kích thước dựa trên kích thước hình dạng và độ phân giải được chỉ định. Tùy chọn, nó cũng có thể xóa các vùng đã cắt.

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
boolean - A boolean indicating whether the image was successfully compressed. Returns   if the image was resized or cropped, otherwise  .
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> Ví dụ sau đây minh họa cách sử dụng ```
> CompressImage
> ```
 để giảm kích thước của một hình ảnh trong bản trình chiếu bằng cách đặt độ phân giải mục tiêu và loại bỏ các vùng đã cắt:
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
boolean - A  boolean  indicating whether the image was successfully compressed. Returns   if the image was resized or cropped, otherwise  .
### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public final float getStretchOffsetLeft()
```

Returns or sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public final void setStretchOffsetLeft(float value)
```

Returns or sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public final float getStretchOffsetTop()
```

Returns or sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public final void setStretchOffsetTop(float value)
```

Returns or sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public final float getStretchOffsetRight()
```

Returns or sets right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public final void setStretchOffsetRight(float value)
```

Returns or sets right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public final float getStretchOffsetBottom()
```

Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public final void setStretchOffsetBottom(float value)
```

Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileOffsetX() {#getTileOffsetX--}
```
public final float getTileOffsetX()
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
**Returns:**
float
### setTileOffsetX(float value) {#setTileOffsetX-float-}
```
public final void setTileOffsetX(float value)
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileOffsetY() {#getTileOffsetY--}
```
public final float getTileOffsetY()
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

**Returns:**
float
### setTileOffsetY(float value) {#setTileOffsetY-float-}
```
public final void setTileOffsetY(float value)
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileScaleX() {#getTileScaleX--}
```
public final float getTileScaleX()
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
**Returns:**
float
### setTileScaleX(float value) {#setTileScaleX-float-}
```
public final void setTileScaleX(float value)
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
**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileScaleY() {#getTileScaleY--}
```
public final float getTileScaleY()
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
public final void setTileScaleY(float value)
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileAlignment() {#getTileAlignment--}
```
public final byte getTileAlignment()
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
public final void setTileAlignment(byte value)
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
public final int getTileFlip()
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
public final void setTileFlip(int value)
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