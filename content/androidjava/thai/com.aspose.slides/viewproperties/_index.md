---
title: ViewProperties
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: คุณสมบัติมุมมองทั่วทั้งงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/viewproperties/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject  
```
public class ViewProperties implements IViewProperties, IDOMObject
```

คุณสมบัติมุมมองทั่วทั้งงานนำเสนอ.
## Methods

| Method | Description |
| --- | --- |
| [getLastView()](#getLastView--) | ระบุโหมดมุมมองที่ใช้เมื่อบันทึกเอกสารงานนำเสนอเป็นครั้งล่าสุด. |
| [setLastView(int value)](#setLastView-int-) | ระบุโหมดมุมมองที่ใช้เมื่อบันทึกเอกสารงานนำเสนอเป็นครั้งล่าสุด. |
| [getShowComments()](#getShowComments--) | ระบุว่าความคิดเห็นสไลด์ควรแสดงหรือไม่. |
| [setShowComments(byte value)](#setShowComments-byte-) | ระบุว่าความคิดเห็นสไลด์ควรแสดงหรือไม่. |
| [getNormalViewProperties()](#getNormalViewProperties--) | แสดงคุณสมบัติมุมมองปกติ. |
| [getSlideViewProperties()](#getSlideViewProperties--) | ระบุคุณสมบัติวiew ทั่วไปที่เกี่ยวข้องกับโหมดมุมมองสไลด์. |
| [getNotesViewProperties()](#getNotesViewProperties--) | ระบุคุณสมบัติวiew ทั่วไปที่เกี่ยวข้องกับโหมดมุมมองบันทึกย่อ. |
| [getGridSpacing()](#getGridSpacing--) | คืนค่า หรือ ตั้งค่าระยะห่างกริดที่ควรใช้สำหรับกริดที่เป็นพื้นฐานของเอกสารงานนำเสนอ, หน่วยเป็นจุด. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | คืนค่า หรือ ตั้งค่าระยะห่างกริดที่ควรใช้สำหรับกริดที่เป็นพื้นฐานของเอกสารงานนำเสนอ, หน่วยเป็นจุด. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getLastView() {#getLastView--}
```
public final int getLastView()
```

ระบุโหมดมุมมองที่ใช้เมื่อบันทึกเอกสารงานนำเสนอเป็นครั้งล่าสุด. อ่าน/เขียน [ViewType](../../com.aspose.slides/viewtype).

**Returns:**  
int

### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

ระบุโหมดมุมมองที่ใช้เมื่อบันทึกเอกสารงานนำเสนอเป็นครั้งล่าสุด. อ่าน/เขียน [ViewType](../../com.aspose.slides/viewtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

ระบุว่าความคิดเห็นสไลด์ควรแสดงหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**  
byte

### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

ระบุว่าความคิดเห็นสไลด์ควรแสดงหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

แสดงคุณสมบัติมุมมองปกติ. มุมมองปกติประกอบด้วยสามพื้นที่เนื้อหา: สไลด์เอง, พื้นที่เนื้อหาด้านข้าง, และพื้นที่เนื้อหาที่ด้านล่าง. อ่านอย่างเดียว [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Returns:**  
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)

### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

ระบุคุณสมบัติวiew ทั่วไปที่เกี่ยวข้องกับโหมดมุมมองสไลด์. อ่านอย่างเดียว [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Returns:**  
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

ระบุคุณสมบัติวiew ทั่วไปที่เกี่ยวข้องกับโหมดมุมมองบันทึกย่อ. อ่านอย่างเดียว [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Returns:**  
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

คืนค่า หรือ ตั้งค่าระยะห่างกริดที่ควรใช้สำหรับกริดที่เป็นพื้นฐานของเอกสารงานนำเสนอ, หน่วยเป็นจุด. อ่าน/เขียน float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
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

ค่าระยะห่างกริดต้องเป็นจำนวนบวก. ช่วงค่าที่ทั่วไปคือจาก 1 มม. (2.8349607 จุด) ถึง 2 นิ้ว (144 จุด).

**Returns:**  
float

### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

คืนค่า หรือ ตั้งค่าระยะห่างกริดที่ควรใช้สำหรับกริดที่เป็นพื้นฐานของเอกสารงานนำเสนอ, หน่วยเป็นจุด. อ่าน/เขียน float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
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

ค่าระยะห่างกริดต้องเป็นจำนวนบวก. ช่วงค่าที่ทั่วไปคือจาก 1 มม. (2.8349607 จุด) ถึง 2 นิ้ว (144 จุด).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**Returns:**  
com.aspose.slides.IDOMObject