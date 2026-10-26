---
title: ViewProperties
second_title: อ้างอิง API Aspose.Slides สำหรับ Java
description: คุณสมบัติมุมมองทั่วทั้งการนำเสนอ.
type: docs
url: /th/com.aspose.slides/viewproperties/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

คุณสมบัติมุมมองทั่วทั้งการนำเสนอ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLastView()](#getLastView--) | ระบุโหมดมุมมองที่ใช้เมื่อบันทึกเอกสารการนำเสนอเป็นครั้งสุดท้าย. |
| [setLastView(int value)](#setLastView-int-) | ระบุโหมดมุมมองที่ใช้เมื่อบันทึกเอกสารการนำเสนอเป็นครั้งสุดท้าย. |
| [getShowComments()](#getShowComments--) | ระบุว่าความคิดเห็นของสไลด์ควรจะแสดงหรือไม่. |
| [setShowComments(byte value)](#setShowComments-byte-) | ระบุว่าความคิดเห็นของสไลด์ควรจะแสดงหรือไม่. |
| [getNormalViewProperties()](#getNormalViewProperties--) | แสดงคุณสมบัติมุมมองปกติ. |
| [getSlideViewProperties()](#getSlideViewProperties--) | ระบุคุณสมบัติมุมมองทั่วไปที่สัมพันธ์กับโหมดมุมมองสไลด์. |
| [getNotesViewProperties()](#getNotesViewProperties--) | ระบุคุณสมบัติมุมมองทั่วไปที่สัมพันธ์กับโหมดมุมมองบันทึกย่อ. |
| [getGridSpacing()](#getGridSpacing--) | คืนค่าหรือกำหนดช่องว่างของกริดที่ควรใช้สำหรับกริดที่เป็นพื้นฐานของเอกสารการนำเสนอเป็นจุด. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | คืนค่าหรือกำหนดช่องว่างของกริดที่ควรใช้สำหรับกริดที่เป็นพื้นฐานของเอกสารการนำเสนอเป็นจุด. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```

ระบุโหมดมุมมองที่ใช้เมื่อบันทึกเอกสารการนำเสนอเป็นครั้งสุดท้าย. อ่าน/เขียน [ViewType](../../com.aspose.slides/viewtype).

**คืนค่า:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

ระบุโหมดมุมมองที่ใช้เมื่อบันทึกเอกสารการนำเสนอเป็นครั้งสุดท้าย. อ่าน/เขียน [ViewType](../../com.aspose.slides/viewtype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

ระบุว่าความคิดเห็นของสไลด์ควรจะแสดงหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

ระบุว่าความคิดเห็นของสไลด์ควรจะแสดงหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

แสดงคุณสมบัติมุมมองปกติ. มุมมองปกติประกอบด้วยสามพื้นที่เนื้อหา: สไลด์เอง, พื้นที่เนื้อหาด้านข้าง, และพื้นที่เนื้อหาด้านล่าง. อ่านอย่างเดียว [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**คืนค่า:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

ระบุคุณสมบัติมุมมองทั่วไปที่สัมพันธ์กับโหมดมุมมองสไลด์. อ่านอย่างเดียว [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**คืนค่า:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

ระบุคุณสมบัติมุมมองทั่วไปที่สัมพันธ์กับโหมดมุมมองบันทึกย่อ. อ่านอย่างเดียว [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**คืนค่า:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

คืนค่าหรือกำหนดช่องว่างของกริดที่ควรใช้สำหรับกริดที่เป็นพื้นฐานของเอกสารการนำเสนอเป็นจุด. อ่าน/เขียน float.

--------------------

> ```
> ตัวอย่างโค้ดต่อไปนี้แสดงวิธีเปลี่ยนช่องว่างของกริดในงานนำเสนอ PowerPoint.
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

ค่าช่องว่างของกริดต้องเป็นจำนวนบวก. ช่วงค่าที่เป็นปกติอยู่ระหว่าง 1 มม. (2.8349607 จุด) ถึง 2 นิ้ว (144 จุด).

**คืนค่า:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

คืนค่าหรือกำหนดช่องว่างของกริดที่ควรใช้สำหรับกริดที่เป็นพื้นฐานของเอกสารการนำเสนอเป็นจุด. อ่าน/เขียน float.

--------------------

> ```
> ตัวอย่างโค้ดต่อไปนี้แสดงวิธีเปลี่ยนช่องว่างของกริดในงานนำเสนอ PowerPoint.
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

ค่าช่องว่างของกริดต้องเป็นจำนวนบวก. ช่วงค่าที่เป็นปกติอยู่ระหว่าง 1 มม. (2.8349607 จุด) ถึง 2 นิ้ว (144 จุด).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าอ็อบเจกต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject