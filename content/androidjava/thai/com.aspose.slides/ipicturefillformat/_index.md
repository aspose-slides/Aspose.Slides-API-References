---
title: IPictureFillFormat
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงสไตล์การเติมรูปภาพ.
type: docs
url: /th/com.aspose.slides/ipicturefillformat/
---
**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

แสดงถึงสไตล์การเติมรูปภาพ

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getDpi()](#getDpi--) | คืนค่า หรือกำหนดค่า dpi ที่ใช้ในการเติมรูปภาพ |
| [setDpi(int value)](#setDpi-int-) | คืนค่า หรือกำหนดค่า dpi ที่ใช้ในการเติมรูปภาพ |
| [getPictureFillMode()](#getPictureFillMode--) | คืนค่า หรือกำหนดค่าโหมดการเติมรูปภาพ |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | คืนค่า หรือกำหนดค่าโหมดการเติมรูปภาพ |
| [getPicture()](#getPicture--) | คืนค่ารูปภาพ |
| [getCropLeft()](#getCropLeft--) | คืนค่า หรือกำหนดค่าร้อยละของความกว้างภาพจริงที่ถูกตัดออกทางซ้ายของรูปภาพ |
| [setCropLeft(float value)](#setCropLeft-float-) | คืนค่า หรือกำหนดค่าร้อยละของความกว้างภาพจริงที่ถูกตัดออกทางซ้ายของรูปภาพ |
| [getCropTop()](#getCropTop--) | คืนค่า หรือกำหนดค่าร้อยละของความสูงภาพจริงที่ถูกตัดออกทางบนของรูปภาพ |
| [setCropTop(float value)](#setCropTop-float-) | คืนค่า หรือกำหนดค่าร้อยละของความสูงภาพจริงที่ถูกตัดออกทางบนของรูปภาพ |
| [getCropRight()](#getCropRight--) | คืนค่า หรือกำหนดค่าร้อยละของความกว้างภาพจริงที่ถูกตัดออกทางขวาของรูปภาพ |
| [setCropRight(float value)](#setCropRight-float-) | คืนค่า หรือกำหนดค่าร้อยละของความกว้างภาพจริงที่ถูกตัดออกทางขวาของรูปภาพ |
| [getCropBottom()](#getCropBottom--) | คืนค่า หรือกำหนดค่าร้อยละของความสูงภาพจริงที่ถูกตัดออกทางล่างของรูปภาพ |
| [setCropBottom(float value)](#setCropBottom-float-) | คืนค่า หรือกำหนดค่าร้อยละของความสูงภาพจริงที่ถูกตัดออกทางล่างของรูปภาพ |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | คืนค่า หรือกำหนดขอบซ้ายของสี่เหลี่ยมเติมที่กำหนดโดยการออฟเซ็ตเป็นเปอร์เซ็นต์จากขอบซ้ายของกล่องขอบเขตรูปทรง |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | คืนค่า หรือกำหนดขอบซ้ายของสี่เหลี่ยมเติมที่กำหนดโดยการออฟเซ็ตเป็นเปอร์เซ็นต์จากขอบซ้ายของกล่องขอบเขตรูปทรง |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | คืนค่า หรือกำหนดขอบบนของสี่เหลี่ยมเติมที่กำหนดโดยการออฟเซ็ตเป็นเปอร์เซ็นต์จากขอบบนของกล่องขอบเขตรูปทรง |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | คืนค่า หรือกำหนดขอบบนของสี่เหลี่ยมเติมที่กำหนดโดยการออฟเซ็ตเป็นเปอร์เซ็นต์จากขอบบนของกล่องขอบเขตรูปทรง |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | คืนค่า หรือกำหนดขอบขวาของสี่เหลี่ยมเติมที่กำหนดโดยการออฟเซ็ตเป็นเปอร์เซ็นต์จากขอบขวาของกล่องขอบเขตรูปทรง |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | คืนค่า หรือกำหนดขอบขวาของสี่เหลี่ยมเติมที่กำหนดโดยการออฟเซ็ตเป็นเปอร์เซ็นต์จากขอบขวาของกล่องขอบเขตรูปทรง |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | คืนค่า หรือกำหนดขอบล่างของสี่เหลี่ยมเติมที่กำหนดโดยการออฟเซ็ตเป็นเปอร์เซ็นต์จากขอบล่างของกล่องขอบเขตรูปทรง |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | คืนค่า หรือกำหนดขอบล่างของสี่เหลี่ยมเติมที่กำหนดโดยการออฟเซ็ตเป็นเปอร์เซ็นต์จากขอบล่างของกล่องขอบเขตรูปทรง |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | ลบส่วนที่ถูกตัดของรูปภาพที่เติม |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | บีบอัดภาพโดยลดขนาดตามขนาดรูปทรงและความละเอียดที่ระบุ |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | บีบอัดภาพโดยลดขนาดตามขนาดรูปทรงและความละเอียดที่ระบุ |
| [getTileOffsetX()](#getTileOffsetX--) | คืนค่า หรือกำหนดค่าออฟเซ็ตแนวนอนของพื้นผิวจากจุดกำเนิดของรูปทรงเป็นจุด |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | คืนค่า หรือกำหนดค่าออฟเซ็ตแนวนอนของพื้นผิวจากจุดกำเนิดของรูปทรงเป็นจุด |
| [getTileOffsetY()](#getTileOffsetY--) | คืนค่า หรือกำหนดค่าออฟเซ็ตแนวตั้งของพื้นผิวจากจุดกำเนิดของรูปทรงเป็นจุด |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | คืนค่า หรือกำหนดค่าออฟเซ็ตแนวตั้งของพื้นผิวจากจุดกำเนิดของรูปทรงเป็นจุด |
| [getTileScaleX()](#getTileScaleX--) | คืนค่า หรือกำหนดอัตราส่วนแนวนอนของพื้นผิวเป็นเปอร์เซ็นต์ |
| [setTileScaleX(float value)](#setTileScaleX-float-) | คืนค่า หรือกำหนดอัตราส่วนแนวนอนของพื้นผิวเป็นเปอร์เซ็นต์ |
| [getTileScaleY()](#getTileScaleY--) | คืนค่า หรือกำหนดอัตราส่วนแนวตั้งของพื้นผิวเป็นเปอร์เซ็นต์ |
| [setTileScaleY(float value)](#setTileScaleY-float-) | คืนค่า หรือกำหนดอัตราส่วนแนวตั้งของพื้นผิวเป็นเปอร์เซ็นต์ |
| [getTileAlignment()](#getTileAlignment--) | คืนค่า หรือกำหนดการจัดตำแหน่งของพื้นผิวภายในรูปทรง |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | คืนค่า หรือกำหนดการจัดตำแหน่งของพื้นผิวภายในรูปทรง |
| [getTileFlip()](#getTileFlip--) | พลิกไทล์พื้นผิวตามแกนแนวนอน แนวตั้ง หรือทั้งสองแกน |
| [setTileFlip(int value)](#setTileFlip-int-) | พลิกไทล์พื้นผิวตามแกนแนวนอน แนวตั้ง หรือทั้งสองแกน |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

คืนค่า หรือกำหนดค่า dpi ที่ใช้ในการเติมรูปภาพ อ่าน/เขียน int.

**คืนค่า:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

คืนค่า หรือกำหนดค่า dpi ที่ใช้ในการเติมรูปภาพ อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

คืนค่า หรือกำหนดค่าโหมดการเติมรูปภาพ อ่าน/เขียน [PictureFillMode](../../com.aspose.slides/picturefillmode).

**คืนค่า:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

คืนค่า หรือกำหนดค่าโหมดการเติมรูปภาพ อ่าน/เขียน [PictureFillMode](../../com.aspose.slides/picturefillmode).

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

คืนค่า หรือกำหนดค่าร้อยละของความกว้างภาพจริงที่ถูกตัดออกทางซ้ายของรูปภาพ อ่าน/เขียน float.

**คืนค่า:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

คืนค่า หรือกำหนดค่าร้อยละของความกว้างภาพจริงที่ถูกตัดออกทางซ้ายของรูปภาพ อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

คืนค่า หรือกำหนดค่าร้อยละของความสูงภาพจริงที่ถูกตัดออกทางบนของรูปภาพ อ่าน/เขียน float.

**คืนค่า:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

คืนค่า หรือกำหนดค่าร้อยละของความสูงภาพจริงที่ถูกตัดออกทางบนของรูปภาพ อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

คืนค่า หรือกำหนดค่าร้อยละของความกว้างภาพจริงที่ถูกตัดออกทางขวาของรูปภาพ อ่าน/เขียน float.

**คืนค่า:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

คืนค่า หรือกำหนดค่าร้อยละของความกว้างภาพจริงที่ถูกตัดออกทางขวาของรูปภาพ อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

คืนค่า หรือกำหนดค่าร้อยละของความสูงภาพจริงที่ถูกตัดออกทางล่างของรูปภาพ อ่าน/เขียน float.

**คืนค่า:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

คืนค่า หรือกำหนดค่าร้อยละของความสูงภาพจริงที่ถูกตัดออกทางล่างของรูปภาพ อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

คืนค่า หรือกำหนดค่าขอบซ้ายของสี่เหลี่ยมเติมที่กำหนดโดยการออฟเซ็ตเป็นเปอร์เซ็นต์จากขอบซ้ายของกล่องขอบเขตรูปทรง ค่าระบุเป็นเปอร์เซ็นต์บวกจะหมายถึงการอินเซ็ต ส่วนค่าติดลบจะหมายถึงการเอาท์เซ็ต อ่าน/เขียน float.

**คืนค่า:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

คืนค่า หรือกำหนดค่าขอบซ้ายของสี่เหลี่ยมเติมที่กำหนดโดยการออฟเซ็ตเป็นเปอร์เซ็นต์จากขอบซ้ายของกล่องขอบเขตรูปทรง ค่าระบุเป็นเปอร์เซ็นต์บวกจะหมายถึงการอินเซ็ต ส่วนค่าติดลบจะหมายถึงการเอาท์เซ็ต อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

คืนค่า หรือกำหนดค่าขอบบนของสี่เหลี่ยมเติมที่กำหนดโดยการออฟเซ็ตเป็นเปอร์เซ็นต์จากขอบบนของกล่องขอบเขตรูปทรง ค่าระบุเป็นเปอร์เซ็นต์บวกจะหมายถึงการอินเซ็ต ส่วนค่าติดลบจะหมายถึงการเอาท์เซ็ต อ่าน/เขียน float.

**คืนค่า:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

คืนค่า หรือกำหนดค่าขอบบนของสี่เหลี่ยมเติมที่กำหนดโดยการออฟเซ็ตเป็นเปอร์เซ็นต์จากขอบบนของกล่องขอบเขตรูปทรง ค่าระบุเป็นเปอร์เซ็นต์บวกจะหมายถึงการอินเซ็ต ส่วนค่าติดลบจะหมายถึงการเอาท์เซ็ต อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

คืนค่า หรือกำหนดค่าขอบขวาของสี่เหลี่ยมเติมที่กำหนดโดยการออฟเซ็ตเป็นเปอร์เซ็นต์จากขอบขวาของกล่องขอบเขตรูปทรง ค่าระบุเป็นเปอร์เซ็นต์บวกจะหมายถึงการอินเซ็ต ส่วนค่าติดลบจะหมายถึงการเอาท์เซ็ต อ่าน/เขียน float.

**คืนค่า:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

คืนค่า หรือกำหนดค่าขอบขวาของสี่เหลี่ยมเติมที่กำหนดโดยการออฟเซ็ตเป็นเปอร์เซ็นต์จากขอบขวาของกล่องขอบเขตรูปทรง ค่าระบุเป็นเปอร์เซ็นต์บวกจะหมายถึงการอินเซ็ต ส่วนค่าติดลบจะหมายถึงการเอาท์เซ็ต อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

คืนค่า หรือกำหนดค่าขอบล่างของสี่เหลี่ยมเติมที่กำหนดโดยการออฟเซ็ตเป็นเปอร์เซ็นต์จากขอบล่างของกล่องขอบเขตรูปทรง ค่าระบุเป็นเปอร์เซ็นต์บวกจะหมายถึงการอินเซ็ต ส่วนค่าติดลบจะหมายถึงการเอาท์เซ็ต อ่าน/เขียน float.

**คืนค่า:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

คืนค่า หรือกำหนดค่าขอบล่างของสี่เหลี่ยมเติมที่กำหนดโดยการออฟเซ็ตเป็นเปอร์เซ็นต์จากขอบล่างของกล่องขอบเขตรูปทรง ค่าระบุเป็นเปอร์เซ็นต์บวกจะหมายถึงการอินเซ็ต ส่วนค่าติดลบจะหมายถึงการเอาท์เซ็ต อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

ลบส่วนที่ถูกตัดของรูปภาพที่เติม

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Deletes cropped areas of the PictureFrame image
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - รูปภาพที่ถูกตัดหรือรูปภาพต้นฉบับหากไม่จำเป็นต้องตัด

--------------------

วิธีนี้แปลงไฟล์เมทาฟाइल WMF/EMF เป็นภาพ PNG แบบเรสเตอร์พร้อมการตัดส่วน

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

บีบอัดภาพโดยลดขนาดตามขนาดรูปทรงและความละเอียดที่ระบุ โดยอาจลบส่วนที่ถูกตัดด้วย

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` วิธีลดขนาดของรูปภาพในงานนำเสนอโดยกำหนดความละเอียดเป้าหมายและลบส่วนที่ถูกตัดออก:
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
> ``` เพื่อลดขนาดของรูปภาพในงานนำเสนอโดยกำหนดความละเอียดเป้าหมายและลบส่วนที่ถูกตัดออก:
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

รับ  ซ  อ  ес 



Sorry, content  



The  



This  



... (



...



The 



 



```
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