---
title: IControl
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงคอนโทรล ActiveX.
type: docs
url: /th/com.aspose.slides/icontrol/
---
**อินเทอร์เฟซที่ทำการนำไปใช้ทั้งหมด:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

แสดงถึงคอนโทรล ActiveX.
## เมธอด

| Method | Description |
| --- | --- |
| [getName()](#getName--) | ส่งคืนชื่อของคอนโทรลนี้. |
| [setName(String value)](#setName-java.lang.String-) | ส่งคืนชื่อของคอนโทรลนี้. |
| [getClassId()](#getClassId--) | รับค่า class id ของคอนโทรลนี้. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | ส่งคืนออบเจ็กต์ ControlEx image fill properties. |
| [getFrame()](#getFrame--) | ส่งคืนหรือกำหนดเฟรมของคอนโทรล. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | ส่งคืนหรือกำหนดเฟรมของคอนโทรล. |
| [getProperties()](#getProperties--) | ส่งคืนคอลเลกชันของคุณสมบัติ ActiveX. |
| [getPersistence()](#getPersistence--) | รับวิธีที่ใช้เก็บคุณสมบัติของคอนโทรล ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | ระบุการคงอยู่ของคอนโทรล ActiveX เมื่อวิธีการจัดเก็บเป็น PersistStream, PersistStreamInit หรือ PersistStorage. |
### getName() {#getName--}
```
public abstract String getName()
```

ส่งคืนชื่อของคอนโทรลนี้. อ่าน/เขียน String.

**ส่งคืน:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

ส่งคืนชื่อของคอนโทรลนี้. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

รับค่า class id ของคอนโทรลนี้. อ่านอย่างเดียว java.util.UUID.

**ส่งคืน:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

ส่งคืนออบเจ็กต์ ControlEx image fill properties. อ่านอย่างเดียว [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**ส่งคืน:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

ส่งคืนหรือกำหนดเฟรมของคอนโทรล. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

**ส่งคืน:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

ส่งคืนหรือกำหนดเฟรมของคอนโทรล. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

ส่งคืนคอลเลกชันของคุณสมบัติ ActiveX. อ่านอย่างเดียว [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**ส่งคืน:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

รับวิธีที่ใช้เก็บคุณสมบัติของคอนโทรล ActiveX. อ่านอย่างเดียว [PersistenceType](../../com.aspose.slides/persistencetype).

**ส่งคืน:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

ระบุการคงอยู่ของคอนโทรล ActiveX เมื่อวิธีการจัดเก็บเป็น PersistStream, PersistStreamInit หรือ PersistStorage.

**ส่งคืน:**
byte[]