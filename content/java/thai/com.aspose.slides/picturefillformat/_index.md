---
title: PictureFillFormat
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นสไตล์การเติมรูปภาพ.
type: docs
url: /th/com.aspose.slides/picturefillformat/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**ทั้งหมดที่ใช้งานอินเทอร์เฟซ:**  
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)  
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

แสดงถึงสไตล์การเติมรูปภาพ.  
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | ส่งคืนหรือกำหนดค่า dpi ที่ใช้ในการเติมรูปภาพ. |
| [setDpi(int value)](#setDpi-int-) | ส่งคืนหรือกำหนดค่า dpi ที่ใช้ในการเติมรูปภาพ. |
| [getPictureFillMode()](#getPictureFillMode--) | ส่งคืนหรือกำหนดโหมดการเติมรูปภาพ. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | ส่งคืนหรือกำหนดโหมดการเติมรูปภาพ. |
| [getPicture()](#getPicture--) | ส่งคืนรูปภาพ. |
| [getCropLeft()](#getCropLeft--) | ส่งคืนหรือกำหนดจำนวนเปอร์เซ็นต์ของความกว้างภาพจริงที่ถูกตัดออกจากด้านซ้ายของรูปภาพ. |
| [setCropLeft(float value)](#setCropLeft-float-) | ส่งคืนหรือกำหนดจำนวนเปอร์เซ็นต์ของความกว้างภาพจริงที่ถูกตัดออกจากด้านซ้ายของรูปภาพ. |
| [getCropTop()](#getCropTop--) | ส่งคืนหรือกำหนดจำนวนเปอร์เซ็นต์ของความสูงภาพจริงที่ถูกตัดออกจากด้านบนของรูปภาพ. |
| [setCropTop(float value)](#setCropTop-float-) | ส่งคืนหรือกำหนดจำนวนเปอร์เซ็นต์ของความสูงภาพจริงที่ถูกตัดออกจากด้านบนของรูปภาพ. |
| [getCropRight()](#getCropRight--) | ส่งคืนหรือกำหนดจำนวนเปอร์เซ็นต์ของความกว้างภาพจริงที่ถูกตัดออกจากด้านขวาของรูปภาพ. |
| [setCropRight(float value)](#setCropRight-float-) | ส่งคืนหรือกำหนดจำนวนเปอร์เซ็นต์ของความกว้างภาพจริงที่ถูกตัดออกจากด้านขวาของรูปภาพ. |
| [getCropBottom()](#getCropBottom--) | ส่งคืนหรือกำหนดจำนวนเปอร์เซ็นต์ของความสูงภาพจริงที่ถูกตัดออกจากด้านล่างของรูปภาพ. |
| [setCropBottom(float value)](#setCropBottom-float-) | ส่งคืนหรือกำหนดจำนวนเปอร์เซ็นต์ของความสูงภาพจริงที่ถูกตัดออกจากด้านล่างของรูปภาพ. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Delete cropped areas of the fill Picture. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | บีบอัดภาพโดยลดขนาดตามขนาดของรูปร่างและความละเอียดที่กำหนด. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | บีบอัดภาพโดยลดขนาดตามขนาดของรูปร่างและความละเอียดที่กำหนด. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | ส่งคืนหรือกำหนดขอบซ้ายของสี่เหลี่ยมเติมที่กำหนดโดยออฟเซ็ตเปอร์เซ็นต์จากขอบซ้ายของกล่องขอบเขตของรูปร่าง. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | ส่งคืนหรือกำหนดขอบซ้ายของสี่เหลี่ยมเติมที่กำหนดโดยออฟเซ็ตเปอร์เซ็นต์จากขอบซ้ายของกล่องขอบเขตของรูปร่าง. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | ส่งคืนหรือกำหนดขอบบนของสี่เหลี่ยมเติมที่กำหนดโดยออฟเซ็ตเปอร์เซ็นต์จากขอบบนของกล่องขอบเขตของรูปร่าง. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | ส่งคืนหรือกำหนดขอบบนของสี่เหลี่ยมเติมที่กำหนดโดยออฟเซ็ตเปอร์เซ็นต์จากขอบบนของกล่องขอบเขตของรูปร่าง. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | ส่งคืนหรือกำหนดขอบขวาของสี่เหลี่ยมเติมที่กำหนดโดยออฟเซ็ตเปอร์เซ็นต์จากขอบขวาของกล่องขอบเขตของรูปร่าง. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | ส่งคืนหรือกำหนดขอบขวาของสี่เหลี่ยมเติมที่กำหนดโดยออฟเซ็ตเปอร์เซ็นต์จากขอบขวของกล่องขอบเขตของรูปร่าง. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | ส่งคืนหรือกำหนดขอบล่างของสี่เหลี่ยมเติมที่กำหนดโดยออฟเซ็ตเปอร์เซ็นต์จากขอบล่างของกล่องขอบเขตของรูปร่าง. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | ส่งคืนหรือกำหนดขอบล่างของสี่เหลี่ยมเติมที่กำหนดโดยออฟเซ็ตเปอร์เซ็นต์จากขอบล่างของกล่องขอบเขตของรูปร่าง. |
| [getTileOffsetX()](#getTileOffsetX--) | ส่งคืนหรือกำหนดออฟเซ็ตแนวนอนของเทกซ์เจอร์จากจุดกำเนิดของรูปร่างเป็นจุด. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | ส่งคืนหรือกำหนดออฟเซ็ตแนวนอนของเทกซ์เจอร์จากจุดกำเนิดของรูปร่างเป็นจุด. |
| [getTileOffsetY()](#getTileOffsetY--) | ส่งคืนหรือกำหนดออฟเซ็ตแนวตั้งของเทกซ์เจอร์จากจุดกำเนิดของรูปร่างเป็นจุด. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | ส่งคืนหรือกำหนดออฟเซ็ตแนวตั้งของเทกซ์เจอร์จากจุดกำเนิดของรูปร่างเป็นจุด. |
| [getTileScaleX()](#getTileScaleX--) | ส่งคืนหรือกำหนดสเกลแนวนอนสำหรับการเติมเทกซ์เจอร์เป็นเปอร์เซ็นต์. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | ส่งคืนหรือกำหนดสเกลแนวนอนสำหรับการเติมเทกซ์เจอร์เป็นเปอร์เซ็นต์. |
| [getTileScaleY()](#getTileScaleY--) | ส่งคืนหรือกำหนดสเกลแนวตั้งสำหรับการเติมเทกซ์เจอร์เป็นเปอร์เซ็นต์. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | ส่งคืนหรือกำหนดสเกลแนวตั้งสำหรับการเติมเทกซ์เจอร์เป็นเปอร์เซ็นต์. |
| [getTileAlignment()](#getTileAlignment--) | ส่งคืนหรือกำหนดวิธีการจัดตำแหน่งเทกซ์เจอร์ภายในรูปร่าง. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | ส่งคืนหรือกำหนดวิธีการจัดตำแหน่งเทกซ์เจอร์ภายในรูปร่าง. |
| [getTileFlip()](#getTileFlip--) | พลิกเทกซ์เจอร์ไทล์ตามแกนนอน, แนวตั้ง หรือทั้งสองแกน. |
| [setTileFlip(int value)](#setTileFlip-int-) | พลิกเทกซ์เจอร์ไทล์ตามแกนนอน, แนวตั้ง หรือทั้งสองแกน. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

รุ่น. อ่านอย่างเดียว long.

**ส่งคืน:**
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

ส่งคืนหรือกำหนดค่า dpi ที่ใช้ในการเติมรูปภาพ. อ่าน/เขียน int .

**ส่งคืน:**
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

ส่งคืนหรือกำหนดค่า dpi ที่ใช้ในการเติมรูปภาพ. อ่าน/เขียน int .

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

ส่งคืนหรือกำหนดโหมดการเติมรูปภาพ. อ่าน/เขียน [PictureFillMode](../../com.aspose.slides/picturefillmode).

**ส่งคืน:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

ส่งคืนหรือกำหนดโหมดการเติมรูปภาพ. อ่าน/เขียน [PictureFillMode](../../com.aspose.slides/picturefillmode).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

ส่งคืนรูปภาพ. อ่านอย่างเดียว [ISlidesPicture](../../com.aspose.slides/islidespicture).

**ส่งคืน:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

ส่งคืนหรือกำหนดจำนวนเปอร์เซ็นต์ของความกว้างภาพจริงที่ถูกตัดออกจากด้านซ้ายของรูปภาพ. อ่าน/เขียน float .

**ส่งคืน:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

ส่งคืนหรือกำหนดจำนวนเปอร์เซ็นต์ของความกว้างภาพจริงที่ถูกตัดออกจากด้านซ้ายของรูปภาพ. อ่าน/เขียน float .

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

ส่งคืนหรือกำหนดจำนวนเปอร์เซ็นต์ของความสูงภาพจริงที่ถูกตัดออกจากด้านบนของรูปภาพ. อ่าน/เขียน float .

**ส่งคืน:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

ส่งคืนหรือกำหนดจำนวนเปอร์เซ็นต์ของความสูงภาพจริงที่ถูกตัดออกจากด้านบนของรูปภาพ. อ่าน/เขียน float .

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

ส่งคืนหรือกำหนดจำนวนเปอร์เซ็นต์ของความกว้างภาพจริงที่ถูกตัดออกจากด้านขวาของรูปภาพ. อ่าน/เขียน float .

**ส่งคืน:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

ส่งคืนหรือกำหนดจำนวนเปอร์เซ็นต์ของความกว้างภาพจริงที่ถูกตัดออกจากด้านขวาของรูปภาพ. อ่าน/เขียน float .

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

ส่งคืนหรือกำหนดจำนวนเปอร์เซ็นต์ของความสูงภาพจริงที่ถูกตัดออกจากด้านล่างของรูปภาพ. อ่าน/เขียน float .

**ส่งคืน:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

ส่งคืนหรือกำหนดจำนวนเปอร์เซ็นต์ของความสูงภาพจริงที่ถูกตัดออกจากด้านล่างของรูปภาพ. อ่าน/เขียน float .

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

Delete cropped areas of the fill Picture.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // รับ PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // ลบพื้นที่ที่ถูกตัดของรูปภาพ PictureFrame
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**ส่งคืน:**
[IPPImage](../../com.aspose.slides/ippimage) - Cropped image or origin image if cropping is not necessary.

--------------------

วิธีนี้แปลงไฟล์เมตาฟไฟล์ WMF/EMF ไปเป็นรูปภาพ PNG แบบแรสเตอร์พร้อมการครอป

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

บีบอัดภาพโดยลดขนาดตามขนาดของรูปร่างและความละเอียดที่กำหนด. สามารถลบพื้นที่ที่ถูกครอปได้เพิ่มเติม.

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
> The following example demonstrates how to use the ```
> CompressImage
> ``` method to reduce the size of an image in a presentation by setting a target resolution and removing cropped areas:
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

**Parameters:**
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

ค่าเริ่มต้นคือ [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |