---
title: IViewProperties
second_title: Aspose.Slides for Java API Reference
description: คุณสมบัติการมองเห็นระดับการนำเสนอทั่วทั้งเอกสาร.
type: docs
url: /th/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

คุณสมบัติการมองเห็นระดับการนำเสนอทั่วทั้งเอกสาร.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLastView()](#getLastView--) | ระบุโหมดการแสดงผลที่ใช้เมื่อไฟล์งานนำเสนอถูกบันทึกครั้งสุดท้าย. |
| [setLastView(int value)](#setLastView-int-) | ระบุโหมดการแสดงผลที่ใช้เมื่อไฟล์งานนำเสนอถูกบันทึกครั้งสุดท้าย. |
| [getShowComments()](#getShowComments--) | ระบุว่าจะให้แสดงความคิดเห็นของสไลด์หรือไม่. |
| [setShowComments(byte value)](#setShowComments-byte-) | ระบุว่าจะให้แสดงความคิดเห็นของสไลด์หรือไม่. |
| [getSlideViewProperties()](#getSlideViewProperties--) | ระบุคุณสมบัติการแสดงผลทั่วไปที่เชื่อมโยงกับโหมดการแสดงผลสไลด์. |
| [getNotesViewProperties()](#getNotesViewProperties--) | ระบุคุณสมบัติการแสดงผลทั่วไปที่เชื่อมโยงกับโหมดการแสดงผลโน้ต. |
| [getNormalViewProperties()](#getNormalViewProperties--) | แสดงคุณสมบัติการแสดงผลแบบปกติ. |
| [getGridSpacing()](#getGridSpacing--) | คืนค่า หรือกำหนดค่าระยะห่างของกริดที่ควรใช้สำหรับกริดพื้นฐานของไฟล์งานนำเสนอ หน่วยเป็นพอยต์. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | คืนค่า หรือกำหนดค่าระยะห่างของกริดที่ควรใช้สำหรับกริดพื้นฐานของไฟล์งานนำเสนอ หน่วยเป็นพอยต์. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

ระบุโหมดการแสดงผลที่ใช้เมื่อไฟล์งานนำเสนอถูกบันทึกครั้งสุดท้าย. อ่าน/เขียน [ViewType](../../com.aspose.slides/viewtype).

**คืนค่า:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

ระบุโหมดการแสดงผลที่ใช้เมื่อไฟล์งานนำเสนอถูกบันทึกครั้งสุดท้าย. อ่าน/เขียน [ViewType](../../com.aspose.slides/viewtype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

ระบุว่าจะให้แสดงความคิดเห็นของสไลด์หรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

ระบุว่าจะให้แสดงความคิดเห็นของสไลด์หรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

ระบุคุณสมบัติการแสดงผลทั่วไปที่เชื่อมโยงกับโหมดการแสดงผลสไลด์. อ่านอย่างเดียว [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**คืนค่า:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

ระบุคุณสมบัติการแสดงผลทั่วไปที่เชื่อมโยงกับโหมดการแสดงผลโน้ต. อ่านอย่างเดียว [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**คืนค่า:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

แสดงคุณสมบัติการแสดงผลแบบปกติ. การแสดงผลแบบปกติมีสามส่วนของเนื้อหา: สไลด์เอง, ส่วนเนื้อหาข้างด้าน, และส่วนเนื้อหาด้านล่าง. อ่านอย่างเดียว [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**คืนค่า:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

คืนค่า หรือกำหนดค่าระยะห่างของกริดที่ควรใช้สำหรับกริดพื้นฐานของไฟล์งานนำเสนอ หน่วยเป็นพอยต์. อ่าน/เขียน float.

--------------------

> ```
> ตัวอย่างโค้ดต่อไปนี้แสดงวิธีเปลี่ยนค่าระยะห่างของกริดในงานนำเสนอ PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

ค่าระยะห่างของกริดต้องเป็นจำนวนบวก. ช่วงค่าที่พบโดยทั่วไปอยู่ระหว่าง 1 มม. (2.8349607 พอยต์) ถึง 2 นิ้ว (144 พอยต์).

**คืนค่า:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

คืนค่า หรือกำหนดค่าระยะห่างของกริดที่ควรใช้สำหรับกริดพื้นฐานของไฟล์งานนำเสนอ หน่วยเป็นพอยต์. อ่าน/เขียน float.

--------------------

> ```
> ตัวอย่างโค้ดต่อไปนี้แสดงวิธีเปลี่ยนค่าระยะห่างของกริดในงานนำเสนอ PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

ค่าระยะห่างของกริดต้องเป็นจำนวนบวก. ช่วงค่าที่พบโดยทั่วไปอยู่ระหว่าง 1 มม. (2.8349607 พอยต์) ถึง 2 นิ้ว (144 พอยต์).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |