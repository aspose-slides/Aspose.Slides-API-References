---
title: IPictureFillFormat
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn kiểu nền ảnh.
type: docs
url: /vi/com.aspose.slides/ipicturefillformat/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

Biểu diễn kiểu nền ảnh.
## Phương thức

| Method | Description |
| --- | --- |
| [getDpi()](#getDpi--) | Trả về hoặc đặt dpi được sử dụng để nền ảnh. |
| [setDpi(int value)](#setDpi-int-) | Trả về hoặc đặt dpi được sử dụng để nền ảnh. |
| [getPictureFillMode()](#getPictureFillMode--) | Trả về hoặc đặt chế độ nền ảnh. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Trả về hoặc đặt chế độ nền ảnh. |
| [getPicture()](#getPicture--) | Trả về ảnh. |
| [getCropLeft()](#getCropLeft--) | Trả về hoặc đặt phần phần trăm của độ rộng thực của ảnh bị cắt ở phía trái của ảnh. |
| [setCropLeft(float value)](#setCropLeft-float-) | Trả về hoặc đặt phần phần trăm của độ rộng thực của ảnh bị cắt ở phía trái của ảnh. |
| [getCropTop()](#getCropTop--) | Trả về hoặc đặt phần phần trăm của độ cao thực của ảnh bị cắt ở phần trên của ảnh. |
| [setCropTop(float value)](#setCropTop-float-) | Trả về hoặc đặt phần phần trăm của độ cao thực của ảnh bị cắt ở phần trên của ảnh. |
| [getCropRight()](#getCropRight--) | Trả về hoặc đặt phần phần trăm của độ rộng thực của ảnh bị cắt ở phía phải của ảnh. |
| [setCropRight(float value)](#setCropRight-float-) | Trả về hoặc đặt phần phần trăm của độ rộng thực của ảnh bị cắt ở phía phải của ảnh. |
| [getCropBottom()](#getCropBottom--) | Trả về hoặc đặt phần phần trăm của độ cao thực của ảnh bị cắt ở phía dưới của ảnh. |
| [setCropBottom(float value)](#setCropBottom-float-) | Trả về hoặc đặt phần phần trăm của độ cao thực của ảnh bị cắt ở phía dưới của ảnh. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Trả về hoặc đặt mép trái của hình chữ nhật nền được định nghĩa bởi khoảng lệch phần trăm từ mép trái của hộp giới hạn hình dạng. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Trả về hoặc đặt mép trái của hình chữ nhật nền được định nghĩa bởi khoảng lệch phần trăm từ mép trái của hộp giới hạn hình dạng. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Trả về hoặc đặt mép trên của hình chữ nhật nền được định nghĩa bởi khoảng lệch phần trăm từ mép trên của hộp giới hạn hình dạng. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Trả về hoặc đặt mép trên của hình chữ nhật nền được định nghĩa bởi khoảng lệch phần trăm từ mép trên của hộp giới hạn hình dạng. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Trả về hoặc đặt mép phải của hình chữ nhật nền được định nghĩa bởi khoảng lệch phần trăm từ mép phải của hộp giới hạn hình dạng. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Trả về hoặc đặt mép phải của hình chữ nhật nền được định nghĩa bởi khoảng lệch phần trăm từ mép phải của hộp giới hạn hình dạng. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Trả về hoặc đặt mép dưới của hình chữ nhật nền được định nghĩa bởi khoảng lệch phần trăm từ mép dưới của hộp giới hạn hình dạng. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Trả về hoặc đặt mép dưới của hình chữ nhật nền được định nghĩa bởi khoảng lệch phần trăm từ mép dưới của hộp giới hạn hình dạng. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Xóa các khu vực đã cắt của ảnh nền. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Nén ảnh bằng cách giảm kích thước dựa trên kích thước hình dạng và độ phân giải đã chỉ định. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Nén ảnh bằng cách giảm kích thước dựa trên kích thước hình dạng và độ phân giải đã chỉ định. |
| [getTileOffsetX()](#getTileOffsetX--) | Trả về hoặc đặt độ lệch ngang của kết cấu từ điểm gốc của hình dạng, tính bằng điểm. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Trả về hoặc đặt độ lệch ngang của kết cấu từ điểm gốc của hình dạng, tính bằng điểm. |
| [getTileOffsetY()](#getTileOffsetY--) | Trả về hoặc đặt độ lệch dọc của kết cấu từ điểm gốc của hình dạng, tính bằng điểm. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Trả về hoặc đặt độ lệch dọc của kết cấu từ điểm gốc của hình dạng, tính bằng điểm. |
| [getTileScaleX()](#getTileScaleX--) | Trả về hoặc đặt tỷ lệ ngang cho nền kết cấu dưới dạng phần trăm. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Trả về hoặc đặt tỷ lệ ngang cho nền kết cấu dưới dạng phần trăm. |
| [getTileScaleY()](#getTileScaleY--) | Trả về hoặc đặt tỷ lệ dọc cho nền kết cấu dưới dạng phần trăm. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Trả về hoặc đặt tỷ lệ dọc cho nền kết cấu dưới dạng phần trăm. |
| [getTileAlignment()](#getTileAlignment--) | Trả về hoặc đặt cách mà kết cấu được căn chỉnh trong hình dạng. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Trả về hoặc đặt cách mà kết cấu được căn chỉnh trong hình dạng. |
| [getTileFlip()](#getTileFlip--) | Lật gạch kết cấu theo trục ngang, dọc hoặc cả hai. |
| [setTileFlip(int value)](#setTileFlip-int-) | Lật gạch kết cấu theo trục ngang, dọc hoặc cả hai. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Trả về hoặc đặt dpi được sử dụng để nền ảnh. Đọc/ghi int.

**Trả về:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

Trả về hoặc đặt dpi được sử dụng để nền ảnh. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Trả về hoặc đặt chế độ nền ảnh. Đọc/ghi [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Trả về:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

Trả về hoặc đặt chế độ nền ảnh. Đọc/ghi [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Trả về ảnh. Chỉ đọc [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Trả về:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Trả về hoặc đặt phần phần trăm của độ rộng thực của ảnh bị cắt ở phía trái của ảnh. Đọc/ghi float.

**Trả về:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

Trả về hoặc đặt phần phần trăm của độ rộng thực của ảnh bị cắt ở phía trái của ảnh. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Trả về hoặc đặt phần phần trăm của độ cao thực của ảnh bị cắt ở phần trên của ảnh. Đọc/ghi float.

**Trả về:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

Trả về hoặc đặt phần phần trăm của độ cao thực của ảnh bị cắt ở phần trên của ảnh. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Trả về hoặc đặt phần phần trăm của độ rộng thực của ảnh bị cắt ở phía phải của ảnh. Đọc/ghi float.

**Trả về:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

Trả về hoặc đặt phần phần trăm của độ rộng thực của ảnh bị cắt ở phía phải của ảnh. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Trả về hoặc đặt phần phần trăm của độ cao thực của ảnh bị cắt ở phía dưới của ảnh. Đọc/ghi float.

**Trả về:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

Trả về hoặc đặt phần phần trăm của độ cao thực của ảnh bị cắt ở phía dưới của ảnh. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

Trả về hoặc đặt mép trái của hình chữ nhật nền được định nghĩa bởi khoảng lệch phần trăm từ mép trái của hộp giới hạn hình dạng. Giá trị phần trăm dương là nội suy, giá trị âm là ngoại suy. Đọc/ghi float.

**Trả về:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

Trả về hoặc đặt mép trái của hình chữ nhật nền được định nghĩa bởi khoảng lệch phần trăm từ mép trái của hộp giới hạn hình dạng. Giá trị phần trăm dương là nội suy, giá trị âm là ngoại suy. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

Trả về hoặc đặt mép trên của hình chữ nhật nền được định nghĩa bởi khoảng lệch phần trăm từ mép trên của hộp giới hạn hình dạng. Giá trị phần trăm dương là nội suy, giá trị âm là ngoại suy. Đọc/ghi float.

**Trả về:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

Trả về hoặc đặt mép trên của hình chữ nhật nền được định nghĩa bởi khoảng lệch phần trăm từ mép trên của hộp giới hạn hình dạng. Giá trị phần trăm dương là nội suy, giá trị âm là ngoại suy. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

Trả về hoặc đặt mép phải của hình chữ nhật nền được định nghĩa bởi khoảng lệch phần trăm từ mép phải của hộp giới hạn hình dạng. Giá trị phần trăm dương là nội suy, giá trị âm là ngoại suy. Đọc/ghi float.

**Trả về:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

Trả về hoặc đặt mép phải của hình chữ nhật nền được định nghĩa bởi khoảng lệch phần trăm từ mép phải của hộp giới hạn hình dạng. Giá trị phần trăm dương là nội suy, giá trị âm là ngoại suy. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

Trả về hoặc đặt mép dưới của hình chữ nhật nền được định nghĩa bởi khoảng lệch phần trăm từ mép dưới của hộp giới hạn hình dạng. Giá trị phần trăm dương là nội suy, giá trị âm là ngoại suy. Đọc/ghi float.

**Trả về:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

Trả về hoặc đặt mép dưới của hình chữ nhật nền được định nghĩa bởi khoảng lệch phần trăm từ mép dưới của hộp giới hạn hình dạng. Giá trị phần trăm dương là nội suy, giá trị âm là ngoại suy. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

Xóa các khu vực đã cắt của ảnh nền.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Lấy PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Xóa các khu vực đã cắt của hình ảnh PictureFrame
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
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Nén ảnh bằng cách giảm kích thước dựa trên kích thước hình dạng và độ phân giải đã chỉ định. Tùy chọn, nó cũng sẽ xóa các khu vực đã cắt.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` phương thức để giảm kích thước ảnh trong bản trình chiếu bằng cách đặt độ phân giải mục tiêu và loại bỏ các khu vực đã cắt:
>  
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Nén ảnh với độ phân giải mục tiêu 150 DPI (độ phân giải web) và loại bỏ các khu vực đã cắt
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
> Ví dụ dưới đây minh họa cách sử dụng phương thức ```
> CompressImage
> ``` để giảm kích thước ảnh trong bản trình chiếu bằng cách đặt độ phân giải mục tiêu và loại bỏ các khu vực đã cắt:
>   
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Lấy PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Nén ảnh với độ phân giải mục tiêu 150 DPI (độ phân giải web) và loại bỏ các khu vực đã cắt
>      boolean result = picFrame.getPictureFormat().compressImage(true, 150f); // Độ phân giải web
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
>      // Lấy định dạng nền ảnh của hình dạng
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Đặt chế độ nền ảnh thành Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Đặt độ lệch ngang của kết cấu thành 20 điểm
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
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
>      // Lấy định dạng nền ảnh của hình dạng
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Đặt chế độ nền ảnh thành Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Đặt độ lệch ngang của kết cấu thành 20 điểm
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
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
>      // Lấy định dạng nền ảnh của hình dạng
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Đặt chế độ nền ảnh thành Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Đặt độ lệch dọc của kết cấu thành -50 điểm
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float

```
public abstract void setTileOffsetY(float value)
```


Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Lấy định dạng nền ảnh của hình dạng
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Đặt chế độ nền ảnh thành Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Đặt độ lệch dọc của kết cấu thành -50 điểm
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
public abstract float getTileScaleX()
```

Returns or sets the horizontal scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Lấy định dạng nền ảnh của hình dạng
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Đặt chế độ nền ảnh thành Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Đặt tỷ lệ ngang cho kết cấu thành 120 phần trăm
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
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
>      // Lấy định dạng nền ảnh của hình dạng
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Đặt chế độ nền ảnh thành Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Đặt tỷ lệ ngang cho kết cấu thành 120 phần trăm
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
public abstract float getTileScaleY()
```

Returns or sets the vertical scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Lấy định dạng nền ảnh của hình dạng
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Đặt chế độ nền ảnh thành Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Đặt tỷ lệ dọc cho kết cấu thành 120 phần trăm
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Trả về:**
float
### setTileScaleY(float value) {#setTileOffsetY-float-}
```
public abstract void setTileScaleY(float value)
```


Returns or sets the vertical scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Lấy định dạng nền ảnh của hình dạng
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Đặt chế độ nền ảnh thành Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Đặt tỷ lệ dọc cho kết cấu thành 120 phần trăm
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
public abstract byte getTileAlignment()
```


Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Lấy định dạng nền ảnh của hình dạng
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Đặt chế độ nền ảnh thành Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Đặt căn chỉnh cho việc lát gạch sang góc dưới bên phải
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
>      // Lấy định dạng nền ảnh của hình dạng
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Đặt chế độ nền ảnh thành Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Đặt căn chỉnh cho việc lát gạch sang góc dưới bên phải
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
>      // Lấy định dạng nền ảnh của hình dạng
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Đặt chế độ nền ảnh thành Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Lật gạch kết cấu quanh trục dọc.
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
>      // Lấy định dạng nền ảnh của hình dạng
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Đặt chế độ nền ảnh thành Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Lật gạch kết cấu quanh trục dọc.
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