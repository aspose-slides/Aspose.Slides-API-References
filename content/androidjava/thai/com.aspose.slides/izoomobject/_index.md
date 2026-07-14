---
title: IZoomObject
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงอ็อบเจ็กต์ Zoom ในสไลด์หนึ่ง.
type: docs
url: /th/com.aspose.slides/izoomobject/
---
**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

แสดงถึงอ็อบเจ็กต์ Zoom ในสไลด์
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getImageType()](#getImageType--) | รับหรือกำหนดประเภทภาพของอ็อบเจ็กต์ Zoom |
| [setImageType(int value)](#setImageType-int-) | รับหรือกำหนดประเภทภาพของอ็อบเจ็กต์ Zoom |
| [getReturnToParent()](#getReturnToParent--) | รับหรือกำหนดพฤติกรรมการนำทางในแสดงสไลด์ |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | รับหรือกำหนดพฤติกรรมการนำทางในแสดงสไลด์ |
| [getShowBackground()](#getShowBackground--) | รับหรือกำหนดค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์เป้าหมายหรือไม่ |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | รับหรือกำหนดค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์เป้าหมายหรือไม่ |
| [getZoomImage()](#getZoomImage--) | รับหรือกำหนดภาพสำหรับอ็อบเจ็กต์ Zoom |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | รับหรือกำหนดภาพสำหรับอ็อบเจ็กต์ Zoom |
| [getTransitionDuration()](#getTransitionDuration--) | รับหรือกำหนดระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom กับสไลด์ |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | รับหรือกำหนดระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom กับสไลด์ |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```


รับหรือกำหนดประเภทภาพของอ็อบเจ็กต์ Zoom อ่าน/เขียน [ZoomImageType](../../com.aspose.slides/zoomimagetype). ค่าเริ่มต้น: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

ระบุว่าอ็อบเจ็กต์ Zoom ใช้ภาพแสดงตัวอย่างของสไลด์หรือภาพหน้าปกหรือไม่

**คืนค่า:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```


รับหรือกำหนดประเภทภาพของอ็อบเจ็กต์ Zoom อ่าน/เขียน [ZoomImageType](../../com.aspose.slides/zoomimagetype). ค่าเริ่มต้น: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

ระบุว่าอ็อบเจ็กต์ Zoom ใช้ภาพแสดงตัวอย่างของสไลด์หรือภาพหน้าปกหรือไม่

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```


รับหรือกำหนดพฤติกรรมการนำทางในแสดงสไลด์ อ่าน/เขียน boolean. ค่าเริ่มต้น: false

--------------------

> ```
> Example:
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

ค่าจริงของคุณสมบัตินี้ระบุพฤติกรรมการนำทาง “กลับไปยังพาเรนท์” ในการแสดงสไลด์

**คืนค่า:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```


รับหรือกำหนดพฤติกรรมการนำทางในแสดงสไลด์ อ่าน/เขียน boolean. ค่าเริ่มต้น: false

--------------------

> ```
> Example:
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

ค่าจริงของคุณสมบัตินี้ระบุพฤติกรรมการนำทาง “กลับไปยังพาเรนท์” ในการแสดงสไลด์

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```


รับหรือกำหนดค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์เป้าหมายหรือไม่ อ่าน/เขียน boolean. ค่าเริ่มต้น: true

--------------------

> ```
> ตัวอย่างนี้แสดงการลบพื้นหลังของภาพของอ็อบเจ็กต์ Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public abstract void setShowBackground(boolean value)
```


รับหรือกำหนดค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์เป้าหมายหรือไม่ อ่าน/เขียน boolean. ค่าเริ่มต้น: true

--------------------

> ```
> The example demonstrates removing the background of an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public abstract IPPImage getZoomImage()
```


รับหรือกำหนดภาพสำหรับอ็อบเจ็กต์ Zoom อ่าน/เขียน [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> The example demonstrates changing an image of a Zoom object:
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

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```


รับหรือกำหนดภาพสำหรับอ็อบเจ็กต์ Zoom อ่าน/เขียน [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> ตัวอย่างนี้แสดงการเปลี่ยนภาพของอ็อบเจ็กต์ Zoom:
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


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```


รับหรือกำหนดระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom กับสไลด์ อ่าน/เขียน float. ค่าเริ่มต้น: 1.0f

--------------------

> ```
> ตัวอย่างนี้แสดงการเปลี่ยนระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom กับสไลด์:
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

หากไม่ได้ระบุ (TransitionDur = 0) จะใช้การเปลี่ยนผ่านของสไลด์เป้าหมายและเวลาที่สัมพันธ์กับการเปลี่ยนผ่านนั้น

**คืนค่า:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```


รับหรือกำหนดระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom กับสไลด์ อ่าน/เขียน float. ค่าเริ่มต้น: 1.0f

--------------------

> ```
> ตัวอย่างนี้แสดงการเปลี่ยนระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom กับสไลด์:
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

หากไม่ได้ระบุ (TransitionDur = 0) จะใช้การเปลี่ยนผ่านของสไลด์เป้าหมายและเวลาที่สัมพันธ์กับการเปลี่ยนผ่านนั้น

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |