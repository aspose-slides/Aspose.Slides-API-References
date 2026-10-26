---
title: IOleObjectFrame
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงอ็อบเจ็กต์ OLE บนสไลด์.
type: docs
url: /th/com.aspose.slides/ioleobjectframe/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

แสดงถึงวัตถุ OLE บนสไลด์.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | ส่งคืนอ็อบเจ็กต์คุณสมบัติการเติมรูปภาพของ OleObject. |
| [getObjectName()](#getObjectName--) | ส่งคืนหรือกำหนดชื่อของวัตถุ. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | ส่งคืนหรือกำหนดชื่อของวัตถุ. |
| [getEmbeddedData()](#getEmbeddedData--) | รับข้อมูลเกี่ยวกับข้อมูลที่ฝังอยู่ของ OLE. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | กำหนดข้อมูลเกี่ยวกับข้อมูลที่ฝังอยู่ของ OLE. |
| [getObjectProgId()](#getObjectProgId--) | ส่งคืน ProgID ของวัตถุ. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | ส่งคืน ProgID ของวัตถุ. |
| [getLinkFileName()](#getLinkFileName--) | ส่งคืนเส้นทางเต็มของไฟล์ที่เชื่อมโยง. |
| [getLinkPathLong()](#getLinkPathLong--) | ส่งคืนเส้นทางเต็มของไฟล์ที่เชื่อมโยง. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | ส่งคืนเส้นทางเต็มของไฟล์ที่เชื่อมโยง. |
| [getLinkPathRelative()](#getLinkPathRelative--) | ส่งคืนเส้นทางสัมพันธ์ของไฟล์ที่เชื่อมโยงหากมีอยู่, มิฉะนั้นส่งคืนสตริงว่าง. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | ส่งคืนชื่อไฟล์ของวัตถุ OLE ที่ฝังอยู่ |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | ส่งคืนเส้นทางของวัตถุ OLE ที่ฝังอยู่ |
| [isObjectIcon()](#isObjectIcon--) | กำหนดว่าวัตถุแสดงเป็นไอคอนหรือไม่. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | กำหนดว่าวัตถุแสดงเป็นไอคอนหรือไม่. |
| [isObjectLink()](#isObjectLink--) | กำหนดว่าวัตถุเชื่อมโยงกับไฟล์ภายนอกหรือไม่. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | กำหนดว่าวัตถุที่ฝังและเชื่อมโยงจะอัปเดตอัตโนมัติเมื่อเปิดหรือพิมพ์การนำเสนอหรือไม่. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | กำหนดว่าวัตถุที่ฝังและเชื่อมโยงจะอัปเดตอัตโนมัติเมื่อเปิดหรือพิมพ์การนำเสนอหรือไม่. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | ส่งคืนหรือกำหนดชื่อเรื่องสำหรับไอคอน OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | ส่งคืนหรือกำหนดชื่อเรื่องสำหรับไอคอน OleObject. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

ส่งคืนอ็อบเจ็กต์คุณสมบัติการเติมรูปภาพของ OleObject. อ่านอย่างเดียว [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**ส่งคืน:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

ส่งคืนหรือกำหนดชื่อของวัตถุ. อ่าน/เขียน String.

**ส่งคืน:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

ส่งคืนหรือกำหนดชื่อของวัตถุ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

รับข้อมูลเกี่ยวกับข้อมูลที่ฝังอยู่ของ OLE. อ่านอย่างเดียว [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**ส่งคืน:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

กำหนดข้อมูลเกี่ยวกับข้อมูลที่ฝังอยู่ของ OLE.

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
>          BufferedInputStream bis = null;
>          DataInputStream dis = null;
>          try {
>              File file = new File("Picture.png");
>              byte[] bytes = new byte[(int) file.length()];
>              bis = new BufferedInputStream(new FileInputStream(file));
>              dis = new DataInputStream(bis);
>              dis.readFully(bytes);
>              IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(bytes, "png");
>              oof.setEmbeddedData(newData);
>          } finally {
>              if (dis != null) {
>                  dis.close();
>              if (bis != null)
>                  bis.close();
>              }
>          }
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | ข้อมูลฝัง [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------
เมธอดนี้เปลี่ยนแปลงคุณสมบัติของวัตถุเพื่อสะท้อนข้อมูลใหม่และตั้งค่าแฟล็ก IsObjectLink เป็น false ซึ่งบ่งบอกว่าวัตถุ OLE ถูกฝังอยู่. |
### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

ส่งคืน ProgID ของวัตถุ. อ่านอย่างเดียว String.

**ส่งคืน:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

ส่งคืน ProgID ของวัตถุ. อ่านอย่างเดียว String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

ส่งคืนเส้นทางเต็มของไฟล์ที่เชื่อมโยง. จะใช้ชื่อไฟล์สั้น. อ่านอย่างเดียว String.

**ส่งคืน:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

ส่งคืนเส้นทางเต็มของไฟล์ที่เชื่อมโยง. จะใช้ชื่อไฟล์ยาว. อ่าน/เขียน String.

**ส่งคืน:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

ส่งคืนเส้นทางเต็มของไฟล์ที่เชื่อมโยง. จะใช้ชื่อไฟล์ยาว. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

ส่งคืนเส้นทางสัมพันธ์ของไฟล์ที่เชื่อมโยงหากมีอยู่, มิฉะนั้นส่งคืนสตริงว่าง. อ่านอย่างเดียว String.

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
ในงานนำเสนอ Ppt, ลิงก์วัตถุ Ole บางส่วนอาจมีการแสดงเป็นแบบสัมพันธ์.

**ส่งคืน:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

ส่งคืนชื่อไฟล์ของวัตถุ OLE ที่ฝังอยู่

**ส่งคืน:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

ส่งคืนเส้นทางของวัตถุ OLE ที่ฝังอยู่

**ส่งคืน:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

กำหนดว่าวัตถุแสดงเป็นไอคอนหรือไม่. อ่าน/เขียน boolean.

**ส่งคืน:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

กำหนดว่าวัตถุแสดงเป็นไอคอนหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

กำหนดว่าวัตถุเชื่อมโยงกับไฟล์ภายนอกหรือไม่. อ่านอย่างเดียว boolean.

**ส่งคืน:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

กำหนดว่าวัตถุที่ฝังและเชื่อมโยงจะอัปเดตอัตโนมัติเมื่อเปิดหรือพิมพ์การนำเสนอหรือไม่. อ่าน/เขียน boolean.

**ส่งคืน:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

กำหนดว่าวัตถุที่ฝังและเชื่อมโยงจะอัปเดตอัตโนมัติเมื่อเปิดหรือพิมพ์การนำเสนอหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

ส่งคืนหรือกำหนดชื่อเรื่องสำหรับไอคอน OleObject. อ่าน/เขียน String.

--------------------
เมื่อ IsObjectIcon == false ค่าตัวนี้จะถูกละเมิด. สตริงอาจถูกตัดตามขนาดของไอคอน OLE.

**ส่งคืน:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

ส่งคืนหรือกำหนดชื่อเรื่องสำหรับไอคอน OleObject. อ่าน/เขียน String.

--------------------
เมื่อ IsObjectIcon == false ค่าตัวนี้จะถูกละเมิด. สตริงอาจถูกตัดตามขนาดของไอคอน OLE.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |