---
title: PictureFrame
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn một khung chứa hình ảnh bên trong.
type: docs
url: /vi/com.aspose.slides/pictureframe/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

Biểu diễn một khung chứa hình ảnh bên trong.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Thêm một khung âm thanh vào slide với vị trí và kích thước được chỉ định.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // Thêm một hình ảnh vào tài nguyên của bản trình bày.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // Đặt hình ảnh cho khung âm thanh.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //Lưu bản trình bày đã chỉnh sửa vào đĩa
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Trả về các khóa của shape. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | Trả về đối tượng PictureFillFormat cho một khung hình ảnh. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Trả về hoặc đặt tỷ lệ chiều cao (so với kích thước hình ảnh gốc) của khung hình ảnh. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Trả về hoặc đặt tỷ lệ chiều cao (so với kích thước hình ảnh gốc) của khung hình ảnh. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Trả về hoặc đặt tỷ lệ chiều rộng (so với kích thước hình ảnh gốc) của khung hình ảnh. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Trả về hoặc đặt tỷ lệ chiều rộng (so với kích thước hình ảnh gốc) của khung hình ảnh. |
| [isCameo()](#isCameo--) | Xác định liệu PictureFrame có phải là đối tượng Cameo hay không. |

### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```

Trả về các khóa của shape. Chỉ đọc [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Trả về:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Trả về hoặc đặt kiểu AutoShape cho PictureFrame. Có thể sử dụng tất cả các mục trong tập [ShapeType](../../com.aspose.slides/shapetype), ngoại trừ mọi loại đường:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5.

Đọc/ghi [ShapeType](../../com.aspose.slides/shapetype).

**Trả về:**
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Trả về hoặc đặt kiểu AutoShape cho PictureFrame. Có thể sử dụng tất cả các mục trong tập [ShapeType](../../com.aspose.slides/shapetype), ngoại trừ mọi loại đường:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5.

Đọc/ghi [ShapeType](../../com.aspose.slides/shapetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```

Trả về đối tượng PictureFillFormat cho một khung hình ảnh. Chỉ đọc [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Trả về:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```

Trả về hoặc đặt tỷ lệ chiều cao (so với kích thước hình ảnh gốc) của khung hình ảnh. Giá trị 1.0 tương ứng với 100%. Đọc/ghi  float .

**Trả về:**
float

### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```

Trả về hoặc đặt tỷ lệ chiều cao (so với kích thước hình ảnh gốc) của khung hình ảnh. Giá trị 1.0 tương ứng với 100%. Đọc/ghi  float .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```

Trả về hoặc đặt tỷ lệ chiều rộng (so với kích thước hình ảnh gốc) của khung hình ảnh. Giá trị 1.0 tương ứng với 100%. Đọc/ghi  float .

**Trả về:**
float

### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```

Trả về hoặc đặt tỷ lệ chiều rộng (so với kích thước hình ảnh gốc) của khung hình ảnh. Giá trị 1.0 tương ứng với 100%. Đọc/ghi  float .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```

Xác định liệu PictureFrame có phải là đối tượng Cameo hay không. Chỉ đọc boolean.

**Trả về:**
boolean