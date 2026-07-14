---
title: OleObjectFrame
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงวัตถุ OLE บนสไลด์
type: docs
url: /th/com.aspose.slides/oleobjectframe/
---
**สืบทอด:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

Represents an OLE object on a slide.

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // โหลดไฟล์ PPTX ไปยังอ็อบเจ็กต์การพรีเซนเทชัน
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // เข้าถึงสไลด์แรก
>      ISlide sld = pres.getSlides().get_Item(0);
>      // แคสต์รูปร่างเป็น OleObjectFrame
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // อ่านวัตถุ OLE และเขียนลงดิสก์
>      if (oleObjectFrame != null) {
>          // ดึงข้อมูลไฟล์ที่ฝังอยู่
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // ดึงส่วนขยายไฟล์ที่ฝังอยู่
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // สร้างเส้นทางเพื่อบันทึกไฟล์ที่แยกออกมา
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // บันทึกข้อมูลที่แยกออกมา
>          FileOutputStream fos = null;
>          try {
>              fos = new FileOutputStream(extractedPath);
>              fos.write(data);
>          } finally {
>              if (fos != null) fos.close();
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | คืนค่า OleObject image fill properties object. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | คืนค่า หรือกำหนดชื่อสำหรับไอคอน OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | คืนค่า หรือกำหนดชื่อสำหรับไอคอน OleObject. |
| [getObjectName()](#getObjectName--) | คืนค่า หรือกำหนดชื่อของวัตถุ. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | คืนค่า หรือกำหนดชื่อของวัตถุ. |
| [getObjectProgId()](#getObjectProgId--) | คืนค่า ProgID ของวัตถุ. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | คืนค่า ProgID ของวัตถุ. |
| [getLinkFileName()](#getLinkFileName--) | คืนค่าเส้นทางเต็มไปยังไฟล์ที่เชื่อมโยง. |
| [getLinkPathLong()](#getLinkPathLong--) | คืนค่าเส้นทางเต็มไปยังไฟล์ที่เชื่อมโยง. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | คืนค่าเส้นทางเต็มไปยังไฟล์ที่เชื่อมโยง. |
| [getLinkPathRelative()](#getLinkPathRelative--) | คืนค่าเส้นทางสัมพันธ์ไปยังไฟล์ที่เชื่อมโยงหากมี, มิฉะนั้นคืนค่าว่าง. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | คืนชื่อไฟล์ของวัตถุ OLE ที่ฝังไว้ |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | คืนค่าเส้นทางของวัตถุ OLE ที่ฝังไว้ |
| [getEmbeddedData()](#getEmbeddedData--) | รับหรือกำหนดข้อมูลเกี่ยวกับข้อมูลที่ฝังใน OLE. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | กำหนดข้อมูลเกี่ยวกับข้อมูลที่ฝังใน OLE. |
| [isObjectIcon()](#isObjectIcon--) | กำหนดว่าวัตถุแสดงเป็นไอคอนหรือไม่. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | กำหนดว่าวัตถุแสดงเป็นไอคอนหรือไม่. |
| [isObjectLink()](#isObjectLink--) | กำหนดว่าวัตถุเชื่อมโยงกับไฟล์ภายนอกหรือไม่. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | กำหนดว่าถ้าออบเจ็กต์ฝังที่เชื่อมโยงจะอัปเดตโดยอัตโนมัติเมื่อเปิดหรือพิมพ์งานนำเสนอหรือไม่. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | กำหนดว่าถ้าออบเจ็กต์ฝังที่เชื่อมโยงจะอัปเดตโดยอัตโนมัติเมื่อเปิดหรือพิมพ์งานนำเสนอหรือไม่. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

คืนค่า OleObject image fill properties object. อ่านอย่างเดียว [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**ค่าที่คืน:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

คืนค่า หรือกำหนดชื่อสำหรับไอคอน OleObject. อ่าน/เขียน String.

--------------------

เมื่อ IsObjectIcon == false ค่าตัวนี้จะถูกละเลย. สตริงอาจถูกตัดสั้นตามขนาดของไอคอน Ole.

**ค่าที่คืน:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

คืนค่า หรือกำหนดชื่อสำหรับไอคอน OleObject. อ่าน/เขียน String.

--------------------

เมื่อ IsObjectIcon == false ค่าตัวนี้จะถูกละเลย. สตริงอาจถูกตัดสั้นตามขนาดของไอคอน Ole.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

คืนค่า หรือกำหนดชื่อของวัตถุ. อ่าน/เขียน String.

**ค่าที่คืน:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

คืนค่า หรือกำหนดชื่อของวัตถุ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

คืนค่า ProgID ของวัตถุ. อ่านอย่างเดียว String.

**ค่าที่คืน:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

คืนค่า ProgID ของวัตถุ. อ่านอย่างเดียว String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

คืนค่าเส้นทางเต็มไปยังไฟล์ที่เชื่อมโยง. ใช้ชื่อไฟล์สั้น. อ่านอย่างเดียว String.

**ค่าที่คืน:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

คืนค่าเส้นทางเต็มไปยังไฟล์ที่เชื่อมโยง. ใช้ชื่อไฟล์ยาว. อ่าน/เขียน String.

**ค่าที่คืน:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

คืนค่าเส้นทางเต็มไปยังไฟล์ที่เชื่อมโยง. ใช้ชื่อไฟล์ยาว. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

คืนค่าเส้นทางสัมพันธ์ไปยังไฟล์ที่เชื่อมโยงหากมี, มิฉะนั้นคืนค่าว่าง. อ่านอย่างเดียว String.

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

ในงานนำเสนอ Ppt ลิงก์วัตถุ Ole บางรายการอาจมีการแสดงเป็นแบบสัมพันธ์.

**ค่าที่คืน:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```

คืนชื่อไฟล์ของวัตถุ OLE ที่ฝังไว้

**ค่าที่คืน:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

คืนค่าเส้นทางของวัตถุ OLE ที่ฝังไว้

**ค่าที่คืน:**
java.lang.String
### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

รับหรือกำหนดข้อมูลเกี่ยวกับข้อมูลที่ฝังใน OLE. อ่าน/เขียน [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**ค่าที่คืน:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

กำหนดข้อมูลเกี่ยวกับข้อมูลที่ฝังใน OLE.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Embedded data [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------

เมธอดนี้เปลี่ยนแปลงคุณสมบัติของออบเจ็กต์เพื่อสะท้อนข้อมูลใหม่และตั้งค่าสถานะ IsObjectLink เป็น false แสดงว่าออบเจ็กต์ OLE ถูกฝังไว้. |
### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

กำหนดว่าวัตถุแสดงเป็นไอคอนหรือไม่. อ่าน/เขียน  boolean .

**ค่าที่คืน:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

กำหนดว่าวัตถุแสดงเป็นไอคอนหรือไม่. อ่าน/เขียน  boolean .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

กำหนดว่าวัตถุเชื่อมโยงกับไฟล์ภายนอกหรือไม่. อ่านอย่างเดียว  boolean .

**ค่าที่คืน:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

กำหนดว่าถ้าออบเจ็กต์ฝังที่เชื่อมโยงจะอัปเดตโดยอัตโนมัติเมื่อเปิดหรือพิมพ์งานนำเสนอหรือไม่. อ่าน/เขียน  boolean .

**ค่าที่คืน:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

กำหนดว่าถ้าออบเจ็กต์ฝังที่เชื่อมโยงจะอัปเดตโดยอัตโนมัติเมื่อเปิดหรือพิมพ์งานนำเสนอหรือไม่. อ่าน/เขียน  boolean .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |