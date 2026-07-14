---
title: IViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: คุณสมบัตุมุมมองระดับการนำเสนอ
type: docs
url: /th/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

คุณสมบัตุมุมมองระดับการนำเสนอ
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLastView()](#getLastView--) | Specifies the view mode that was used when the presentation document was last saved. |
| [setLastView(int value)](#setLastView-int-) | Specifies the view mode that was used when the presentation document was last saved. |
| [getShowComments()](#getShowComments--) | Specifies whether the slide comments should be shown. |
| [setShowComments(byte value)](#setShowComments-byte-) | Specifies whether the slide comments should be shown. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Specifies common view properties associated with the slide view mode. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Specifies common view properties associated with the notes view mode. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Represents normal view properties. |
| [getGridSpacing()](#getGridSpacing--) | Returns or sets the grid spacing that should be used for the grid underlying the presentation document, in points. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Returns or sets the grid spacing that should be used for the grid underlying the presentation document, in points. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

ระบุโหมดการมองเห็นที่ใช้เมื่อบันทึกเอกสารการนำเสนอเป็นครั้งสุดท้าย. อ่าน/เขียน [ViewType](../../com.aspose.slides/viewtype).

**คืนค่า:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

ระบุโหมดการมองเห็นที่ใช้เมื่อบันทึกเอกสารการนำเสนอเป็นครั้งสุดท้าย. อ่าน/เขียน [ViewType](../../com.aspose.slides/viewtype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

ระบุว่าจะต้องแสดงความคิดเห็นของสไลด์หรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

ระบุว่าจะต้องแสดงความคิดเห็นของสไลด์หรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

ระบุคุณสมบัตมุมมองทั่วไปที่เกี่ยวข้องกับโหมดมุมมองสไลด์. อ่านอย่างเดียว [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**คืนค่า:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

ระบุคุณสมบัตมุมมองทั่วไปที่เกี่ยวข้องกับโหมดมุมมองบันทึกย่อ. อ่านอย่างเดียว [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**คืนค่า:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

เป็นการแสดงผลแบบปกติ. การแสดงผลแบบปกติมีพื้นที่เนื้อหา 3 ส่วน: สไลด์เอง, พื้นที่เนื้อหาด้านข้าง, และพื้นที่เนื้อหาด้านล่าง. อ่านอย่างเดียว [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**คืนค่า:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

คืนค่า หรือกำหนดระยะห่างของเส้นกริดที่ใช้สำหรับกริดภายใต้เอกสารการนำเสนอ, หน่วยเป็นพ้อยต์. อ่าน/เขียน float.

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

ค่าระยะห่างของเส้นกริดต้องเป็นจำนวนบวก. ช่วงค่าที่ทั่วไปคือจาก 1 มม. (2.8349607 พ้อยต์) ถึง 2 นิ้ว (144 พ้อยต์).

**คืนค่า:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

คืนค่า หรือกำหนดระยะห่างของเส้นกริดที่ใช้สำหรับกริดภายใต้เอกสารการนำเสนอ, หน่วยเป็นพ้อยต์. อ่าน/เขียน float.

--------------------

> ```
> โค้ดตัวอย่างต่อไปนี้แสดงวิธีเปลี่ยนระยะห่างของกริดในงานนำเสนอ PowerPoint.
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

ค่าระยะห่างของเส้นกริดต้องเป็นจำนวนบวก. ช่วงค่าที่ทั่วไปคือจาก 1 มม. (2.8349607 พ้อยต์) ถึง 2 นิ้ว (144 พ้อยต์).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |