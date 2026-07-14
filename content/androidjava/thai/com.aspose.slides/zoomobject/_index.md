---
title: ZoomObject
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API Java
description: แสดงอ็อบเจกต์ Zoom ในสไลด์
type: docs
url: /th/com.aspose.slides/zoomobject/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**อินเทอร์เฟสที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)  
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

แสดงอ็อบเจกต์ Zoom ในสไลด์หนึ่ง.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getImageType()](#getImageType--) | รับหรือกำหนดประเภทภาพของอ็อบเจกต์ Zoom. |
| [setImageType(int value)](#setImageType-int-) | รับหรือกำหนดประเภทภาพของอ็อบเจกต์ Zoom. |
| [getReturnToParent()](#getReturnToParent--) | รับหรือกำหนดพฤติกรรมการนำทางในสไลด์โชว์. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | รับหรือกำหนดพฤติกรรมการนำทางในสไลด์โชว์. |
| [getShowBackground()](#getShowBackground--) | รับหรือกำหนดค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | รับหรือกำหนดค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่. |
| [getZoomImage()](#getZoomImage--) | รับหรือกำหนดภาพสำหรับอ็อบเจกต์ Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | รับหรือกำหนดภาพสำหรับอ็อบเจกต์ Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | รับหรือกำหนดระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom กับสไลด์. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | รับหรือกำหนดระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom กับสไลด์. |

### getImageType() {#getImageType--}
```
public final int getImageType()
```

รับหรือกำหนดประเภทภาพของอ็อบเจกต์ Zoom. อ่าน/เขียน [ZoomImageType](../../com.aspose.slides/zoomimagetype). ค่าเริ่มต้น: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
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

ระบุว่าอ็อบเจกต์ Zoom กำลังใช้ภาพพรีวิวของสไลด์หรือภาพปก.

**คืนค่า:**  
int

### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

รับหรือกำหนดประเภทภาพของอ็อบเจกต์ Zoom. อ่าน/เขียน [ZoomImageType](../../com.aspose.slides/zoomimagetype). ค่าเริ่มต้น: Preview

--------------------

> ```
> ตัวอย่างต่อไปนี้สาธิตการเปลี่ยน Image Type เป็นค่า Preview. 
>  ในกรณีนี้ภาพปัจจุบันของอ็อบเจกต์ Zoom จะเปลี่ยนเป็นภาพสไลด์:
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

ระบุว่าอ็อบเจกต์ Zoom กำลังใช้ภาพพรีวิวของสไลด์หรือภาพปก.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

รับหรือกำหนดพฤติกรรมการนำทางในสไลด์โชว์. อ่าน/เขียน boolean. ค่าเริ่มต้น: false

--------------------

> ```
> ตัวอย่าง:
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

ค่าจริงของคุณสมบัตินี้ระบุพฤติกรรมการนำกลับไปยังพาเรนท์ในสไลด์โชว์.

**คืนค่า:**  
boolean

### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

รับหรือกำหนดพฤติกรรมการนำทางในสไลด์โชว์. อ่าน/เขียน boolean. ค่าเริ่มต้น: false

--------------------

> ```
> ตัวอย่าง:
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

ค่าจริงของคุณสมบัตินี้ระบุพฤติกรรมการนำกลับไปยังพาเรนท์ในสไลด์โชว์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
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


**คืนค่า:**  
boolean

### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public final void setShowBackground(boolean value)
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
public final IPPImage getZoomImage()
```

รับหรือกำหนดภาพสำหรับอ็อบเจกต์ Zoom. อ่าน/เขียน [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> ตัวอย่างนี้แสดงการเปลี่ยนภาพของอ็อบเจกต์ Zoom:
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
public final void setZoomImage(IPPImage value)
```

รับหรือกำหนดภาพสำหรับอ็อบเจกต์ Zoom. อ่าน/เขียน [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> ตัวอย่างนี้แสดงการเปลี่ยนภาพของอ็อบเจกต์ Zoom:
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public final float getTransitionDuration()
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

หากไม่ได้ระบุ (TransitionDur = 0) จะใช้การเปลี่ยนผ่านของสไลด์ปลายทางและเวลาที่เกี่ยวข้องกับการเปลี่ยนนั้น.

**คืนค่า:**  
float

### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
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

หากไม่ได้ระบุ (TransitionDur = 0) จะใช้การเปลี่ยนผ่านของสไลด์ปลายทางและเวลาที่เกี่ยวข้องกับการเปลี่ยนนั้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |