---
title: IZoomObject
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: แสดงวัตถุ Zoom ในสไลด์.
type: docs
url: /th/com.aspose.slides/izoomobject/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

แสดงวัตถุ Zoom ในสไลด์
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getImageType()](#getImageType--) | รับหรือกำหนดประเภทภาพของวัตถุ zoom. |
| [setImageType(int value)](#setImageType-int-) | รับหรือกำหนดประเภทภาพของวัตถุ zoom. |
| [getReturnToParent()](#getReturnToParent--) | รับหรือกำหนดพฤติกรรมการนำทางในสไลด์โชว์. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | รับหรือกำหนดพฤติกรรมการนำทางในสไลด์โชว์. |
| [getShowBackground()](#getShowBackground--) | รับหรือกำหนดค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | รับหรือกำหนดค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่. |
| [getZoomImage()](#getZoomImage--) | รับหรือกำหนดภาพสำหรับวัตถุ zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | รับหรือกำหนดภาพสำหรับวัตถุ zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | รับหรือกำหนดระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom กับสไลด์. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | รับหรือกำหนดระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom กับสไลด์. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

รับหรือกำหนดประเภทภาพของวัตถุ zoom. อ่าน/เขียน [ZoomImageType](../../com.aspose.slides/zoomimagetype). ค่าเริ่มต้น: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

ระบุว่าออบเจกต์ Zoom กำลังใช้ภาพตัวอย่างของสไลด์หรือภาพปกหรือไม่.

**คืนค่า:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```

รับหรือกำหนดประเภทภาพของวัตถุ zoom. อ่าน/เขียน [ZoomImageType](../../com.aspose.slides/zoomimagetype). ค่าเริ่มต้น: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

ระบุว่าออบเจกต์ Zoom กำลังใช้ภาพตัวอย่างของสไลด์หรือภาพปกหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

รับหรือกำหนดพฤติกรรมการนำทางในสไลด์โชว์. อ่าน/เขียน boolean. ค่าเริ่มต้น: false

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

ค่าจริงของคุณสมบัตินี้ระบุการนำทางกลับไปยังพาเรนต์ในสไลด์โชว์.

**คืนค่า:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

รับหรือกำหนดพฤติกรรมการนำทางในสไลด์โชว์. อ่าน/เขียน boolean. ค่าเริ่มต้น: false

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

ค่าจริงของคุณสมบัตินี้ระบุการนำทางกลับไปยังพาเรนต์ในสไลด์โชว์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

รับหรือกำหนดค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่. อ่าน/เขียน boolean. ค่าเริ่มต้น: true

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


**คืนค่า:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public abstract void setShowBackground(boolean value)
```

รับหรือกำหนดค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่. อ่าน/เขียน boolean. ค่าเริ่มต้น: true

--------------------

> ```
> ตัวอย่างนี้แสดงการลบพื้นหลังของภาพของอ็อบเจกต์ Zoom:
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getZoomImage() {#getZoomImage--}
```
public abstract IPPImage getZoomImage()
```

รับหรือกำหนดภาพสำหรับวัตถุ zoom. อ่าน/เขียน [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> ตัวอย่างนี้แสดงการเปลี่ยนภาพของอ็อบเจกต์ Zoom:
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


**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```

รับหรือกำหนดภาพสำหรับวัตถุ zoom. อ่าน/เขียน [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> ตัวอย่างนี้แสดงการเปลี่ยนภาพของอ็อบเจกต์ Zoom:
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


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```

รับหรือกำหนดระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom กับสไลด์. อ่าน/เขียน float. ค่าเริ่มต้น: 1.0f

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

หากไม่ได้ระบุ (TransitionDur = 0) จะใช้การเปลี่ยนผ่านของสไลด์ปลายทางและเวลาที่เกี่ยวข้องกับการเปลี่ยนผ่านนั้น.

**คืนค่า:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

รับหรือกำหนดระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom กับสไลด์. อ่าน/เขียน float. ค่าเริ่มต้น: 1.0f

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

หากไม่ได้ระบุ (TransitionDur = 0) จะใช้การเปลี่ยนผ่านของสไลด์ปลายทางและเวลาที่เกี่ยวข้องกับการเปลี่ยนผ่านนั้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |