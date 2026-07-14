---
title: Control
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงคอนโทรล ActiveX.
type: docs
url: /th/com.aspose.slides/control/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)  
```
public class Control extends DomObject<ControlCollection> implements IControl
```

เป็นตัวควบคุม ActiveX.  
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPersistence()](#getPersistence--) | รับวิธีการที่ใช้ในการเก็บคุณสมบัติของตัวควบคุม ActiveX. |
| [getName()](#getName--) | รับหรือกำหนดชื่อของตัวควบคุมนี้. |
| [setName(String value)](#setName-java.lang.String-) | รับหรือกำหนดชื่อของตัวควบคุมนี้. |
| [getClassId()](#getClassId--) | รับ class id ของตัวควบคุมนี้. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | รับ class id ของตัวควบคุมนี้. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | ส่งคืนอ็อบเจกต์คุณสมบัติการเติมรูปภาพของคอนโทรล. |
| [getFrame()](#getFrame--) | รับหรือกำหนดเฟรมของคอนโทรล. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | รับหรือกำหนดเฟรมของคอนโทรล. |
| [getProperties()](#getProperties--) | ส่งคืนคอลเลกชันของคุณสมบัติ ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | ระบุการคงสภาพของตัวควบคุม ActiveX เมื่อวิธีที่ใช้ในการคงสภาพคือ PersistStream, PersistStreamInit หรือ PersistStorage. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |

### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

รับวิธีการที่ใช้ในการเก็บคุณสมบัติของตัวควบคุม ActiveX. อ่านอย่างเดียว [PersistenceType](../../com.aspose.slides/persistencetype).

--------------------

> ```
> Next example shows the using Persistence property for checking if properties of ActiveX object may be changed as XML based ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //ใช้เมธอดของคุณเองเพื่อจัดการคุณสมบัติ ActiveX ที่ถูกจัดเก็บในไฟล์ไบนารีของมัน
>  }
> ```


**คืนค่า:**  
int

### getName() {#getName--}
```
public final String getName()
```

รับหรือกำหนดชื่อของตัวควบคุมนี้. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

รับหรือกำหนดชื่อของตัวควบคุมนี้. อ่าน/เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

รับ class id ของตัวควบคุมนี้. อ่านอย่างเดียว java.util.UUID.

**คืนค่า:**  
java.util.UUID

### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

รับ class id ของตัวควบคุมนี้. อ่านอย่างเดียว java.util.UUID.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

ส่งคืนอ็อบเจกต์คุณสมบัติการเติมรูปภาพของคอนโทรล. อ่านอย่างเดียว [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**คืนค่า:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

รับหรือกำหนดเฟรมของคอนโทรล. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

**คืนค่า:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

รับหรือกำหนดเฟรมของคอนโทรล. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

ส่งคืนคอลเลกชันของคุณสมบัติ ActiveX. อ่านอย่างเดียว [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

หมายเหตุ: Aspose.Slides รองรับคุณสมบัติ ActiveX ที่อิง XML เท่านั้น หากคุณสมบัติเก็บในรูปแบบไบนารี คุณสมบัตินี้จะส่งคืนค่า null.

**คืนค่า:**  
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)

### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

ระบุการคงสภาพของตัวควบคุม ActiveX เมื่อวิธีที่ใช้ในการคงสภาพคือ PersistStream, PersistStreamInit หรือ PersistStorage.

--------------------

> ```
> Next example shows the using ActiveXControlBinary property for changing ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //ใช้เมธอดของคุณเองเพื่อจัดการคุณสมบัติ ActiveX ที่ถูกเก็บในไฟล์ไบนารีของมัน
>  }
> 
```

**คืนค่า:**  
byte[]

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

ส่งคืนสไลด์ฐาน. อ่านอย่างเดียว [IBaseSlide](../../com.aspose.slides/ibaseslide).

**คืนค่า:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ส่งคืนการนำเสนอ. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation)