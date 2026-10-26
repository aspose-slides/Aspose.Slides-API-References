---
title: IControl
second_title: Aspose.Slides สำหรับ Android ผ่านเอกสารอ้างอิง API ของ Java
description: แทน ActiveX control.
type: docs
url: /th/com.aspose.slides/icontrol/
---
**อินเทอร์เฟซที่ทำการนำไปใช้ทั้งหมด:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

แทน ActiveX control.
## วิธีการ

| Method | Description |
| --- | --- |
| [getName()](#getName--) | คืนชื่อของคอนโทรลนี้. |
| [setName(String value)](#setName-java.lang.String-) | คืนชื่อของคอนโทรลนี้. |
| [getClassId()](#getClassId--) | ดึงค่า class id ของคอนโทรลนี้. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | คืนอ็อบเจกต์คุณสมบัติการเติมรูปภาพ ControlEx. |
| [getFrame()](#getFrame--) | คืนหรือกำหนดกรอบของคอนโทรล. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | คืนหรือกำหนดกรอบของคอนโทรล. |
| [getProperties()](#getProperties--) | คืนคอลเลกชันของคุณสมบัติ ActiveX. |
| [getPersistence()](#getPersistence--) | รับวิธีการที่ใช้เก็บคุณสมบัติของคอนโทรล ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | ระบุการคงอยู่ของคอนโทรล ActiveX เมื่อวิธีการที่ใช้ในการคงอยู่เป็น PersistStream, PersistStreamInit หรือ PersistStorage. |
### getName() {#getName--}
```
public abstract String getName()
```

คืนชื่อของคอนโทรลนี้. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

คืนชื่อของคอนโทรลนี้. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

รับ class id ของคอนโทรลนี้. อ่านอย่างเดียว java.util.UUID.

**คืนค่า:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

คืนอ็อบเจกต์คุณสมบัติการเติมรูปภาพ ControlEx. อ่านอย่างเดียว [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**คืนค่า:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

คืนหรือกำหนดกรอบของคอนโทรล. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

**คืนค่า:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

คืนหรือกำหนดกรอบของคอนโทรล. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

คืนคอลเลกชันของคุณสมบัติ ActiveX. อ่านอย่างเดียว [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**คืนค่า:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

รับวิธีการที่ใช้เก็บคุณสมบัติของคอนโทรล ActiveX. อ่านอย่างเดียว [PersistenceType](../../com.aspose.slides/persistencetype).

**คืนค่า:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

ระบุการคงอยู่ของคอนโทรล ActiveX เมื่อวิธีการที่ใช้ในการคงอยู่เป็น PersistStream, PersistStreamInit หรือ PersistStorage.

**คืนค่า:**
byte[]