---
title: IPictureFillFormat
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงสไตล์การเติมภาพ.
type: docs
url: /th/com.aspose.slides/ipicturefillformat/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

แสดงถึงสไตล์การเติมรูปภาพ.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getDpi()](#getDpi--) | คืนค่า หรือ ตั้งค่า dpi ที่ใช้เพื่อเติมรูปภาพ |
| [setDpi(int value)](#setDpi-int-) | คืนค่า หรือ ตั้งค่า dpi ที่ใช้เพื่อเติมรูปภาพ |
| [getPictureFillMode()](#getPictureFillMode--) | คืนค่า หรือ ตั้งค่าโหมดการเติมรูปภาพ |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | คืนค่า หรือ ตั้งค่าโหมดการเติมรูปภาพ |
| [getPicture()](#getPicture--) | คืนค่ารูปภาพ |
| [getCropLeft()](#getCropLeft--) | คืนค่า หรือ ตั้งค่าจำนวนเปอร์เซ็นต์ของความกว้างจริงของภาพที่ถูกตัดออกจากด้านซ้ายของรูปภาพ |
| [setCropLeft(float value)](#setCropLeft-float-) | คืนค่า หรือ ตั้งค่าจำนวนเปอร์เซ็นต์ของความกว้างจริงของภาพที่ถูกตัดออกจากด้านซ้ายของรูปภาพ |
| [getCropTop()](#getCropTop--) | คืนค่า หรือ ตั้งค่าจำนวนเปอร์เซ็นต์ของความสูงจริงของภาพที่ถูกตัดออกจากด้านบนของรูปภาพ |
| [setCropTop(float value)](#setCropTop-float-) | คืนค่า หรือ ตั้งค่าจำนวนเปอร์เซ็นต์ของความสูงจริงของภาพที่ถูกตัดออกจากด้านบนของรูปภาพ |
| [getCropRight()](#getCropRight--) | คืนค่า หรือ ตั้งค่าจำนวนเปอร์เซ็นต์ของความกว้างจริงของภาพที่ถูกตัดออกจากด้านขวาของรูปภาพ |
| [setCropRight(float value)](#setCropRight-float-) | คืนค่า หรือ ตั้งค่าจำนวนเปอร์เซ็นต์ของความกว้างจริงของภาพที่ถูกตัดออกจากด้านขวาของรูปภาพ |
| [getCropBottom()](#getCropBottom--) | คืนค่า หรือ ตั้งค่าจำนวนเปอร์เซ็นต์ของความสูงจริงของภาพที่ถูกตัดออกจากด้านล่างของรูปภาพ |
| [setCropBottom(float value)](#setCropBottom-float-) | คืนค่า หรือ ตั้งค่าจำนวนเปอร์เซ็นต์ของความสูงจริงของภาพที่ถูกตัดออกจากด้านล่างของรูปภาพ |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | คืนค่า หรือ ตั้งค่าส่วนขอบซ้ายของสี่เหลี่ยมเติม ที่กำหนดโดยเปอร์เซ็นต์จากขอบซ้ายของกล่องขอบของรูปร่าง |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | คืนค่า หรือ ตั้งค่าส่วนขอบซ้ายของสี่เหลี่ยมเติม ที่กำหนดโดยเปอร์เซ็นต์จากขอบซ้ายของกล่องขอบของรูปร่าง |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | คืนค่า หรือ ตั้งค่าส่วนขอบบนของสี่เหลี่ยมเติม ที่กำหนดโดยเปอร์เซ็นต์จากขอบบนของกล่องขอบของรูปร่าง |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | คืนค่า หรือ ตั้งค่าส่วนขอบบนของสี่เหลี่ยมเติม ที่กำหนดโดยเปอร์เซ็นต์จากขอบบนของกล่องขอบของรูปร่าง |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | คืนค่า หรือ ตั้งค่าส่วนขอบขวาของสี่เหลี่ยมเติม ที่กำหนดโดยเปอร์เซ็นต์จากขอบขวาของกล่องขอบของรูปร่าง |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | คืนค่า หรือ ตั้งค่าส่วนขอบขวาของสี่เหลี่ยมเติม ที่กำหนดโดยเปอร์เซ็นต์จากขอบขวาของกล่องขอบของรูปร่าง |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | คืนค่า หรือ ตั้งค่าส่วนขอบล่างของสี่เหลี่ยมเติม ที่กำหนดโดยเปอร์เซ็นต์จากขอบล่างของกล่องขอบของรูปร_shape |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | คืนค่า หรือ ตั้งค่าส่วนขอบล่างของสี่เหลี่ยมเติม ที่กำหนดโดยเปอร์เซ็นต์จากขอบล่างของกล่องขอบของรูปร_shape |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | ลบส่วนที่ถูกตัดของรูปภาพที่ใช้เติม |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | บีบอัดภาพโดยลดขนาดตามขนาดของรูปร่างและความละเอียดที่ระบุ |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | บีบอัดภาพโดยลดขนาดตามขนาดของรูปร่างและความละเอียดที่ระบุ |
| [getTileOffsetX()](#getTileOffsetX--) | คืนค่า หรือ ตั้งค่าการเยื้องแนวนอนของพื้นผิวจากจุดเริ่มต้นของรูปร่างเป็นจุด |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | คืนค่า หรือ ตั้งค่าการเยื้องแนวนอนของพื้นผิวจากจุดเริ่มต้นของรูปร่างเป็นจุด |
| [getTileOffsetY()](#getTileOffsetY--) | คืนค่า หรือ ตั้งค่าการเยื้องแนวตั้งของพื้นผิวจากจุดเริ่มต้นของรูปร่างเป็นจุด |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | คืนค่า หรือ ตั้งค่าการเยื้องแนวตั้งของพื้นผิวจากจุดเริ่มต้นของรูปร่างเป็นจุด |
| [getTileScaleX()](#getTileScaleX--) | คืนค่า หรือ ตั้งค่าความกว้างแนวนอนของการเติมพื้นผิวเป็นเปอร์เซ็นต์ |
| [setTileScaleX(float value)](#setTileScaleX-float-) | คืนค่า หรือ ตั้งค่าความกว้างแนวนอนของการเติมพื้นผิวเป็นเปอร์เซ็นต์ |
| [getTileScaleY()](#getTileScaleY--) | คืนค่า หรือ ตั้งค่าความสูงแนวตั้งของการเติมพื้นผิวเป็นเปอร์เซ็นต์ |
| [setTileScaleY(float value)](#setTileScaleY-float-) | คืนค่า หรือ ตั้งค่าความสูงแนวตั้งของการเติมพื้นผิวเป็นเปอร์เซ็นต์ |
| [getTileAlignment()](#getTileAlignment--) | คืนค่า หรือ ตั้งค่าการจัดตำแหน่งของพื้นผิวภายในรูปร่าง |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | คืนค่า หรือ ตั้งค่าการจัดตำแหน่งของพื้นผิวภายในรูปร่าง |
| [getTileFlip()](#getTileFlip--) | พลิกแผ่นพื้นผิวตามแนวนอน แนวตั้ง หรือทั้งสองแกน |
| [setTileFlip(int value)](#setTileFlip-int-) | พลิกแผ่นพื้นผิวตามแนวนอน แนวตั้ง หรือทั้งสองแกน |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

คืนค่า หรือ ตั้งค่า dpi ที่ใช้เพื่อเติมรูปภาพ อ่าน/เขียน int.

**คืนค่า:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

คืนค่า หรือ ตั้งค่า dpi ที่ใช้เพื่อเติมรูปภาพ อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

คืนค่า หรือ ตั้งค่าโหมดการเติมรูปภาพ อ่าน/เขียน [PictureFillMode](../../com.aspose.slides/picturefillmode).

**คืนค่า:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

คืนค่า หรือ ตั้งค่าโหมดการเติมรูปภาพ อ่าน/เขียน [PictureFillMode](../../com.aspose.slides/picturefillmode).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

คืนค่ารูปภาพ อ่านอย่างเดียว [ISlidesPicture](../../com.aspose.slides/islidespicture).

**คืนค่า:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

คืนค่า หรือ ตั้งค่าจำนวนเปอร์เซ็นต์ของความกว้างจริงของภาพที่ถูกตัดออกจากด้านซ้ายของรูปภาพ อ่าน/เขียน float.

**คืนค่า:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

คืนค่า หรือ ตั้งค่าจำนวนเปอร์เซ็นต์ของความกว้างจริงของภาพที่ถูกตัดออกจากด้านซ้ายของรูปภาพ อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

คืนค่า หรือ ตั้งค่าจำนวนเปอร์เซ็นต์ของความสูงจริงของภาพที่ถูกตัดออกจากด้านบนของรูปภาพ อ่าน/เขียน float.

**คืนค่า:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

คืนค่า หรือ ตั้งค่าจำนวนเปอร์เซ็นต์ของความสูงจริงของภาพที่ถูกตัดออกจากด้านบนของรูปภาพ อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

คืนค่า หรือ ตั้งค่าจำนวนเปอร์เซ็นต์ของความกว้างจริงของภาพที่ถูกตัดออกจากด้านขวาของรูปภาพ อ่าน/เขียน float.

**คืนค่า:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

คืนค่า หรือ ตั้งค่าจำนวนเปอร์เซ็นต์ของความกว้างจริงของภาพที่ถูกตัดออกจากด้านขวาของรูปภาพ อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

คืนค่า หรือ ตั้งค่าจำนวนเปอร์เซ็นต์ของความสูงจริงของภาพที่ถูกตัดออกจากด้านล่างของรูปภาพ อ่าน/เขียน float.

**คืนค่า:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

คืนค่า หรือ ตั้งค่าจำนวนเปอร์เซ็นต์ของความสูงจริงของภาพที่ถูกตัดออกจากด้านล่างของรูปภาพ อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

คืนค่า หรือ ตั้งค่าส่วนขอบซ้ายของสี่เหลี่ยมเติม ที่กำหนดโดยเปอร์เซ็นต์จากขอบซ้ายของกล่องขอบของรูปร่าง ค่าที่เป็นเปอร์เซ็นต์บวกหมายถึงการย่อเข้า ส่วนค่าที่เป็นเปอร์เซ็นต์ลบหมายถึงการขยายออก อ่าน/เขียน float.

**คืนค่า:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

คืนค่า หรือ ตั้งค่าส่วนขอบซ้ายของสี่เหลี่ยมเติม ที่กำหนดโดยเปอร์เซ็นต์จากขอบซ้ายของกล่องขอบของรูปร่าง ค่าที่เป็นเปอร์เซ็นต์บวกหมายถึงการย่อเข้า ส่วนค่าที่เป็นเปอร์เซ็นต์ลบหมายถึงการขยายออก อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

คืนค่า หรือ ตั้งค่าส่วนขอบบนของสี่เหลี่ยมเติม ที่กำหนดโดยเปอร์เซ็นต์จากขอบบนของกล่องขอบของรูปร่าง ค่าที่เป็นเปอร์เซ็นต์บวกหมายถึงการย่อเข้า ส่วนค่าที่เป็นเปอร์เซ็นต์ลบหมายถึงการขยายออก อ่าน/เขียน float.

**คืนค่า:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

คืนค่า หรือ ตั้งค่าส่วนขอบบนของสี่เหลี่ยมเติม ที่กำหนดโดยเปอร์เซ็นต์จากขอบบนของกล่องขอบของรูปร่าง ค่าที่เป็นเปอร์เซ็นต์บวกหมายถึงการย่อเข้า ส่วนค่าที่เป็นเปอร์เซ็นต์ลบหมายถึงการขยายออก อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

คืนค่า หรือ ตั้งค่าส่วนขอบขวาของสี่เหลี่ยมเติม ที่กำหนดโดยเปอร์เซ็นต์จากขอบขวาของกล่องขอบของรูปร่าง ค่าที่เป็นเปอร์เซ็นต์บวกหมายถึงการย่อเข้า ส่วนค่าที่เป็นเปอร์เซ็นต์ลบหมายถึงการขยายออก อ่าน/เขียน float.

**คืนค่า:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

คืนค่า หรือ ตั้งค่าส่วนขอบขวาของสี่เหลี่ยมเติม ที่กำหนดโดยเปอร์เซ็นต์จากขอบขวาของกล่องขอบของรูปร่าง ค่าที่เป็นเปอร์เซ็นต์บวกหมายถึงการย่อเข้า ส่วนค่าที่เป็นเปอร์เซ็นต์ลบหมายถึงการขยายออก อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

คืนค่า หรือ ตั้งค่าส่วนขอบล่างของสี่เหลี่ยมเติม ที่กำหนดโดยเปอร์เซ็นต์จากขอบล่างของกล่องขอบของรูปร่าง ค่าที่เป็นเปอร์เซ็นต์บวกหมายถึงการย่อเข้า ส่วนค่าที่เป็นเปอร์เซ็นต์ลบหมายถึงการขยายออก อ่าน/เขียน float.

**คืนค่า:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

คืนค่า หรือ ตั้งค่าส่วนขอบล่างของสี่เหลี่ยมเติม ที่กำหนดโดยเปอร์เซ็นต์จากขอบล่างของกล่องขอบของรูปร่าง ค่าที่เป็นเปอร์เซ็นต์บวกหมายถึงการย่อเข้า ส่วนค่าที่เป็นเปอร์เซ็นต์ลบหมายถึงการขยายออก อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

ลบส่วนที่ถูกตัดของรูปภาพที่ใช้เติม

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // รับ PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // ลบพื้นที่ที่ถูกตัดของภาพ PictureFrame
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - Cropped image or origin image if cropping is not necessary.

--------------------

เมธอดนี้แปลงไฟล์เมตาฟายล์ WMF/EMF เป็นภาพ PNG แบบแรสเตอร์พร้อมการตัดส่วน

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

บีบอัดภาพโดยลดขนาดตามขนาดของรูปร่างและความละเอียดที่ระบุ ตัวเลือกเพิ่มเติมคือลบส่วนที่ถูกตัดออก

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` วิธีการลดขนาดของภาพในงานพรีเซนเทชันโดยตั้งค่าความละเอียดเป้าหมายและลบส่วนที่ถูกตัดออก:
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
> ตัวอย่างต่อไปนี้แสดงวิธีใช้เมธอด ```
> CompressImage
> ``` เพื่อลดขนาดของภาพในงานพรีเซนเทชันโดยตั้งค่าความละเอียดเป้าหมายและลบส่วนที่ถูกตัดออก:
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

**Returns:**
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

ค่าเริ่มต้นคือ [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |