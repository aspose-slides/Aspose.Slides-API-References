---
title: OleObjectFrame
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: แสดงวัตถุ OLE บนสไลด์.
type: docs
url: /th/com.aspose.slides/oleobjectframe/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

เป็นวัตถุ OLE บนสไลด์.

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // โหลดไฟล์ PPTX ไปยังอ็อบเจ็กต์ Presentation
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // เข้าถึงสไลด์แรก
>      ISlide sld = pres.getSlides().get_Item(0);
>      // แคสรูปทรงเป็น OleObjectFrame
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // อ่าน OLE Object และเขียนลงดิสก์
>      if (oleObjectFrame != null) {
>          // รับข้อมูลไฟล์ที่ฝังไว้
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // รับส่วนขยายไฟล์ที่ฝังไว้
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // สร้างเส้นทางเพื่อบันทึกไฟล์ที่สกัดออก
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // บันทึกข้อมูลที่สกัดออก
>          Files.write(Paths.get(extractedPath), data);
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | คืนค่าอ็อบเจกต์คุณสมบัติการเติมภาพ OleObject. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | คืนค่า หรือ ตั้งค่าชื่อเรื่องสำหรับไอคอน OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | คืนค่า หรือ ตั้งค่าชื่อเรื่องสำหรับไอคอน OleObject. |
| [getObjectName()](#getObjectName--) | คืนค่า หรือ ตั้งค่าชื่อของวัตถุ. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | คืนค่า หรือ ตั้งค่าชื่อของวัตถุ. |
| [getObjectProgId()](#getObjectProgId--) | คืนค่า ProgID ของวัตถุ. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | คืนค่า ProgID ของวัตถุ. |
| [getLinkFileName()](#getLinkFileName--) | คืนค่าเส้นทางเต็มไปยังไฟล์ที่เชื่อมโยง. |
| [getLinkPathLong()](#getLinkPathLong--) | คืนค่าเส้นทางเต็มไปยังไฟล์ที่เชื่อมโยง. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | คืนค่าเส้นทางเต็มไปยังไฟล์ที่เชื่อมโยง. |
| [getLinkPathRelative()](#getLinkPathRelative--) | คืนค่าเส้นทางสัมพันธ์ของไฟล์ที่เชื่อมโยง หากมีอยู่ มิฉะนั้นคืนสตริงว่าง. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | คืนค่าชื่อไฟล์ของวัตถุ OLE ที่ฝังอยู่ |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | คืนค่าเส้นทางของวัตถุ OLE ที่ฝังอยู่ |
| [getEmbeddedData()](#getEmbeddedData--) | รับหรือกำหนดข้อมูลเกี่ยวกับข้อมูลที่ฝัง OLE. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | กำหนดข้อมูลเกี่ยวกับข้อมูลที่ฝัง OLE. |
| [isObjectIcon()](#isObjectIcon--) | กำหนดว่าวัตถุแสดงเป็นไอคอนหรือไม่. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | กำหนดว่าวัตถุแสดงเป็นไอคอนหรือไม่. |
| [isObjectLink()](#isObjectLink--) | กำหนดว่าวัตถุเชื่อมโยงกับไฟล์ภายนอกหรือไม่. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | กำหนดว่าวัตถุฝังที่เชื่อมโยงจะอัปเดตโดยอัตโนมัติเมื่อการนำเสนอถูกเปิดหรือพิมพ์หรือไม่. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | กำหนดว่าวัตถุฝังที่เชื่อมโยงจะอัปเดตโดยอัตโนมัติเมื่อการนำเสนอถูกเปิดหรือพิมพ์หรือไม่. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

คืนค่าอ็อบเจกต์คุณสมบัติการเติมภาพ OleObject. อ่านอย่างเดียว [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**คืนค่า:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

คืนค่า หรือ ตั้งค่าชื่อเรื่องสำหรับไอคอน OleObject. อ่าน/เขียน String.

--------------------

เมื่อ IsObjectIcon == false ค่าดังกล่าวจะถูกละเลย สตริงอาจถูกตัดตามขนาดของไอคอน Ole.

**คืนค่า:**
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

คืนค่า หรือ ตั้งค่าชื่อเรื่องสำหรับไอคอน OleObject. อ่าน/เขียน String.

--------------------

เมื่อ IsObjectIcon == false ค่าดังกล่าวจะถูกละเลย สตริงอาจถูกตัดตามขนาดของไอคอน Ole.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

คืนค่า หรือ ตั้งค่าชื่อของวัตถุ. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

คืนค่า หรือ ตั้งค่าชื่อของวัตถุ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

คืนค่า ProgID ของวัตถุ. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String

### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

คืนค่า ProgID ของวัตถุ. อ่านอย่างเดียว String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

คืนค่าเส้นทางเต็มไปยังไฟล์ที่เชื่อมโยง. จะใช้ชื่อไฟล์สั้น. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

คืนค่าเส้นทางเต็มไปยังไฟล์ที่เชื่อมโยง. จะใช้ชื่อไฟล์ยาว. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

คืนค่าเส้นทางเต็มไปยังไฟล์ที่เชื่อมโยง. จะใช้ชื่อไฟล์ยาว. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

คืนค่าเส้นทางสัมพันธ์ของไฟล์ที่เชื่อมโยง หากมีอยู่ มิฉะนั้นคืนสตริงว่าง. อ่านอย่างเดียว String.

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

ในงานนำเสนอ Ppt, ลิงก์วัตถุ Ole บางส่วนอาจมีลักษณะเป็นสัมพันธ์.

**คืนค่า:**
java.lang.String

### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```

คืนค่าชื่อไฟล์ของวัตถุ OLE ที่ฝังอยู่

**คืนค่า:**
java.lang.String

### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

คืนค่าเส้นทางของวัตถุ OLE ที่ฝังอยู่

**คืนค่า:**
java.lang.String

### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

รับหรือกำหนดข้อมูลเกี่ยวกับข้อมูลที่ฝัง OLE. อ่าน/เขียน [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**คืนค่า:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

กำหนดข้อมูลเกี่ยวกับข้อมูลที่ฝัง OLE.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
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
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Embedded data [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

เมธอดนี้เปลี่ยนแปลงคุณสมบัติของวัตถุเพื่อสะท้อนข้อมูลใหม่และตั้งค่าสถานะ IsObjectLink เป็น false, บ่งชี้ว่าวัตถุ OLE ถูกฝังไว้. |

### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

กำหนดว่าวัตถุแสดงเป็นไอคอนหรือไม่. อ่าน/เขียน boolean .

**คืนค่า:**
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

กำหนดว่าวัตถุแสดงเป็นไอคอนหรือไม่. อ่าน/เขียน boolean .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

กำหนดว่าวัตถุเชื่อมโยงกับไฟล์ภายนอกหรือไม่. อ่านอย่างเดียว boolean .

**คืนค่า:**
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

กำหนดว่าวัตถุฝังที่เชื่อมโยงจะอัปเดตโดยอัตโนมัติเมื่อการนำเสนอถูกเปิดหรือพิมพ์หรือไม่. อ่าน/เขียน boolean .

**คืนค่า:**
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

กำหนดว่าวัตถุฝังที่เชื่อมโยงจะอัปเดตโดยอัตโนมัติเมื่อการนำเสนอถูกเปิดหรือพิมพ์หรือไม่. อ่าน/เขียน boolean .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |