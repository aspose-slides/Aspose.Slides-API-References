---
title: ICommandEffect
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของเอฟเฟกต์คำสั่งสำหรับพฤติกรรมการเคลื่อนไหว.
type: docs
url: /th/com.aspose.slides/icommandeffect/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface ICommandEffect extends IBehavior
```

เป็นตัวแทนของเอฟเฟกต์คำสั่งสำหรับพฤติกรรมการเคลื่อนไหว.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getType()](#getType--) | กำหนดประเภทของเอฟเฟกต์คำสั่งของพฤติกรรม. |
| [setType(byte value)](#setType-byte-) | กำหนดประเภทของเอฟเฟกต์คำสั่งของพฤติกรรม. |
| [getCommandString()](#getCommandString--) | กำหนดสตริงคำสั่ง. |
| [setCommandString(String value)](#setCommandString-java.lang.String-) | กำหนดสตริงคำสั่ง. |
| [getShapeTarget()](#getShapeTarget--) | กำหนดเป้าหมายรูปร่างของเอฟเฟกต์คำสั่ง. |
| [setShapeTarget(IShape value)](#setShapeTarget-com.aspose.slides.IShape-) | กำหนดเป้าหมายรูปร่างของเอฟเฟกต์คำสั่ง. |
### getType() {#getType--}
```
public abstract byte getType()
```


กำหนดประเภทของเอฟเฟกต์คำสั่งของพฤติกรรม. อ่าน/เขียน [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**คืนค่า:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


กำหนดประเภทของเอฟเฟกต์คำสั่งของพฤติกรรม. อ่าน/เขียน [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getShapeTarget() {#getShapeTarget--}
```
public abstract IShape getShapeTarget()
```


กำหนดเป้าหมายรูปร่างของเอฟเฟกต์คำสั่ง. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape)
### setShapeTarget(IShape value) {#setShapeTarget-com.aspose.slides.IShape-}
```
public abstract void setShapeTarget(IShape value)
```


กำหนดเป้าหมายรูปร่างของเอฟเฟกต์คำสั่ง. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |