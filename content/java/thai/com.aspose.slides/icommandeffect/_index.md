---
title: ICommandEffect
second_title: Aspose.Slides สำหรับอ้างอิง API Java
description: เป็นตัวแทนของผลของคำสั่งสำหรับพฤติกรรมการเคลื่อนไหว.
type: docs
url: /th/com.aspose.slides/icommandeffect/
---
**ส่วนต่อประสานที่ทำการนำไปใช้ทั้งหมด:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface ICommandEffect extends IBehavior
```

แสดงผลของคำสั่งสำหรับพฤติกรรมการเคลื่อนไหว
## เมธอด

| Method | Description |
| --- | --- |
| [getType()](#getType--) | กำหนดประเภทผลของคำสั่งสำหรับพฤติกรรม. |
| [setType(byte value)](#setType-byte-) | กำหนดประเภทผลของคำสั่งสำหรับพฤติกรรม. |
| [getCommandString()](#getCommandString--) | กำหนดสตริงคำสั่ง. |
| [setCommandString(String value)](#setCommandString-java.lang.String-) | กำหนดสตริงคำสั่ง. |
| [getShapeTarget()](#getShapeTarget--) | กำหนดเป้าหมายรูปทรงของผลคำสั่ง. |
| [setShapeTarget(IShape value)](#setShapeTarget-com.aspose.slides.IShape-) | กำหนดเป้าหมายรูปทรงของผลคำสั่ง. |
### getType() {#getType--}
```
public abstract byte getType()
```

กำหนดประเภทผลของคำสั่งสำหรับพฤติกรรม. อ่าน/เขียน [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**คืนค่า:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

กำหนดประเภทผลของคำสั่งสำหรับพฤติกรรม. อ่าน/เขียน [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getCommandString() {#getCommandString--}
```
public abstract String getCommandString()
```

กำหนดสตริงคำสั่ง. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setCommandString(String value) {#setCommandString-java.lang.String-}
```
public abstract void setCommandString(String value)
```

กำหนดสตริงคำสั่ง. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getShapeTarget() {#getShapeTarget--}
```
public abstract IShape getShapeTarget()
```

กำหนดเป้าหมายรูปทรงของผลคำสั่ง. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape)
### setShapeTarget(IShape value) {#setShapeTarget-com.aspose.slides.IShape-}
```
public abstract void setShapeTarget(IShape value)
```

กำหนดเป้าหมายรูปทรงของผลคำสั่ง. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |