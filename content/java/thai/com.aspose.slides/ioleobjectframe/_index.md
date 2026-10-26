---
title: IOleObjectFrame
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงอ็อบเจ็กต์ OLE บนสไลด์
type: docs
url: /th/com.aspose.slides/ioleobjectframe/
---
**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

แสดงถึงออบเจ็กต์ OLE บนสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | คืนค่าอ็อบเจ็กต์คุณสมบัติการเติมภาพ OleObject. |
| [getObjectName()](#getObjectName--) | คืนค่า หรือ ตั้งค่าชื่อของอ็อบเจ็กต์. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | คืนค่า หรือ ตั้งค่าชื่อของอ็อบเจ็กต์. |
| [getEmbeddedData()](#getEmbeddedData--) | รับข้อมูลเกี่ยวกับข้อมูลฝัง OLE. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | ตั้งค่าข้อมูลเกี่ยวกับข้อมูลฝัง OLE. |
| [getObjectProgId()](#getObjectProgId--) | คืนค่า ProgID ของอ็อบเจ็กต์. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | คืนค่า ProgID ของอ็อบเจ็กต์. |
| [getLinkFileName()](#getLinkFileName--) | คืนค่าเส้นทางเต็มของไฟล์ที่เชื่อมโยง. |
| [getLinkPathLong()](#getLinkPathLong--) | คืนค่าเส้นทางเต็มของไฟล์ที่เชื่อมโยง. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | คืนค่าเส้นทางเต็มของไฟล์ที่เชื่อมโยง. |
| [getLinkPathRelative()](#getLinkPathRelative--) | คืนค่าที่อยู่สัมพันธ์ของไฟล์ที่เชื่อมโยงหากมี, มิฉะนั้นคืนสตริงว่าง. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | คืนค่าชื่อไฟล์ของอ็อบเจ็กต์ OLE ฝัง |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | คืนค่าที่อยู่ของอ็อบเจ็กต์ OLE ฝัง |
| [isObjectIcon()](#isObjectIcon--) | กำหนดว่่อ็อบเจ็กต์แสดงเป็นไอคอนหรือไม่ |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | กำหนดว่่อ็อบเจ็กต์แสดงเป็นไอคอนหรือไม่ |
| [isObjectLink()](#isObjectLink--) | กำหนดว่าอ็อบเจ็กต์เชื่อมโยงกับไฟล์ภายนอกหรือไม่ |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | กำหนดว่าฝังอ็อบเจ็กต์ที่เชื่อมโยงจะอัปเดตอัตโนมัติเมื่อการนำเสนอเปิดหรือพิมพ์หรือไม่ |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | กำหนดว่าฝังอ็อบเจ็กต์ที่เชื่อมโยงจะอัปเดตอัตโนมัติเมื่อการนำเสนอเปิดหรือพิมพ์หรือไม่ |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | คืนค่า หรือ ตั้งค่าชื่อเรื่องสำหรับไอคอน OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | คืนค่า หรือ ตั้งค่าชื่อเรื่องสำหรับไอคอน OleObject. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

คืนค่าอ็อบเจ็กต์คุณสมบัติการเติมภาพ OleObject. อ่านอย่างเดียว [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**ผลลัพธ์:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

คืนค่า หรือ ตั้งค่าชื่อของอ็อบเจ็กต์. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

คืนค่า หรือ ตั้งค่าชื่อของอ็อบเจ็กต์. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

รับข้อมูลเกี่ยวกับข้อมูลฝัง OLE. อ่านอย่างเดียว [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**ผลลัพธ์:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

ตั้งค่าข้อมูลเกี่ยวกับข้อมูลฝัง OLE.

--------------------

> ```
> Following example demonstrates how to change OLE embedded data
>  and its type for existing [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) object 
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(Files.readAllBytes(Paths.get("Picture.png")), "png");
>          oof.setEmbeddedData(newData);
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | ข้อมูลฝัง [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

--------------------

เมธอดนี้เปลี่ยนแปลงคุณสมบัติของอ็อบเจ็กต์เพื่อสะท้อนข้อมูลใหม่และตั้งค่าแฟล็ก IsObjectLink เป็น false, แสดงว่าออบเจ็กต์ OLE ถูกฝัง. |
### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

คืนค่า ProgID ของอ็อบเจ็กต์. อ่านอย่างเดียว String.

**ผลลัพธ์:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

คืนค่า ProgID ของอ็อบเจ็กต์. อ่านอย่างเดียว String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

คืนค่าเส้นทางเต็มของไฟล์ที่เชื่อมโยง. จะใช้ชื่อไฟล์สั้น. อ่านอย่างเดียว String.

**ผลลัพธ์:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

คืนค่าเส้นทางเต็มของไฟล์ที่เชื่อมโยง. จะใช้ชื่อไฟล์ยาว. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

คืนค่าเส้นทางเต็มของไฟล์ที่เชื่อมโยง. จะใช้ชื่อไฟล์ยาว. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

คืนค่าที่อยู่สัมพันธ์ของไฟล์ที่เชื่อมโยงหากมี, มิฉะนั้นคืนสตริงว่าง. อ่านอย่างเดียว String.

--------------------

> ```
> Presentation presentation = new Presentation("demo.ppt");
>  try {
>      IOleObjectFrame oleFrame = (IOleObjectFrame)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oleFrame != null)
>      {
>          System.out.println("The relative path: " + oleFrame.getLinkPathRelative());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

ในงานนำเสนอ Ppt, ลิงก์อ็อบเจ็กต์ Ole บางส่วนอาจมีการแสดงผลแบบสัมพันธ์.

**ผลลัพธ์:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

คืนค่าชื่อไฟล์ของอ็อบเจ็กต์ OLE ฝัง

**ผลลัพธ์:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

คืนค่าที่อยู่ของอ็อบเจ็กต์ OLE ฝัง

**ผลลัพธ์:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

กำหนดว่าอ็อบเจ็กต์แสดงเป็นไอคอนหรือไม่. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

กำหนดว่าอ็อบเจ็กต์แสดงเป็นไอคอนหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

กำหนดว่าอ็อบเจ็กต์เชื่อมโยงกับไฟล์ภายนอกหรือไม่. อ่านอย่างเดียว boolean.

**ผลลัพธ์:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

กำหนดว่าฝังอ็อบเจ็กต์ที่เชื่อมโยงจะอัปเดตอัตโนมัติเมื่อการนำเสนอเปิดหรือพิมพ์หรือไม่. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

กำหนดว่าฝังอ็อบเจ็กต์ที่เชื่อมโยงจะอัปเดตอัตโนมัติเมื่อการนำเสนอเปิดหรือพิมพ์หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

คืนค่า หรือ ตั้งค่าชื่อเรื่องสำหรับไอคอน OleObject. อ่าน/เขียน String.

--------------------

เมื่อ IsObjectIcon == false ค่าตัวนี้จะถูกละเว้น. สตริงอาจถูกตัดตามขนาดของไอคอน OLE.

**ผลลัพธ์:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

คืนค่า หรือ ตั้งค่าชื่อเรื่องสำหรับไอคอน OleObject. อ่าน/เขียน String.

--------------------

เมื่อ IsObjectIcon == false ค่าตัวนี้จะถูกละเว้น. สตริงอาจถูกตัดตามขนาดของไอคอน OLE.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |