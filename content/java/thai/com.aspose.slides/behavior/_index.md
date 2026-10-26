---
title: Behavior
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: แสดงพฤติกรรมของคลาสฐานสำหรับเอฟเฟกต์.
type: docs
url: /th/com.aspose.slides/behavior/
---
**การสืบทอด:**
java.lang.Object

**ทุกอินเทอร์เฟซที่นำไปใช้:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

แสดงพฤติกรรมของคลาสฐานสำหรับเอฟเฟกต์.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | แสดงว่าพฤติกรรมแอนิเมชันถูกสะสมหรือไม่. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | แสดงว่าพฤติกรรมแอนิเมชันถูกสะสมหรือไม่. |
| [getAdditive()](#getAdditive--) | แสดงว่าพฤติกรรมแอนิเมชันปัจจุบันถูกผสานกับแอนิเมชันที่กำลังทำงานอื่นหรือไม่. |
| [setAdditive(int value)](#setAdditive-int-) | แสดงว่าพฤติกรรมแอนิเมชันปัจจุบันถูกผสานกับแอนิเมชันที่กำลังทำงานอื่นหรือไม่. |
| [getProperties()](#getProperties--) | แสดงคุณสมบัติของพฤติกรรม. |
| [getTiming()](#getTiming--) | แสดงคุณสมบัติของเวลาสำหรับพฤติกรรมเอฟเฟกต์. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | แสดงคุณสมบัติของเวลาสำหรับพฤติกรรมเอฟเฟกต์. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


คืนค่าอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```


แสดงว่าพฤติกรรมแอนิเมชันถูกสะสมหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```


แสดงว่าพฤติกรรมแอนิเมชันถูกสะสมหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```


แสดงว่าพฤติกรรมแอนิเมชันปัจจุบันถูกผสานกับแอนิเมชันที่กำลังทำงานอื่นหรือไม่. อ่าน/เขียน [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**คืนค่า:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```


แสดงว่าพฤติกรรมแอนิเมชันปัจจุบันถูกผสานกับแอนิเมชันที่กำลังทำงานอื่นหรือไม่. อ่าน/เขียน [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```


แสดงคุณสมบัติของพฤติกรรม. อ่านอย่างเดียว [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**คืนค่า:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```


แสดงคุณสมบัติของเวลาสำหรับพฤติกรรมเอฟเฟกต์. อ่าน/เขียน [ITiming](../../com.aspose.slides/itiming).

**คืนค่า:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```


แสดงคุณสมบัติของเวลาสำหรับพฤติกรรมเอฟเฟกต์. อ่าน/เขียน [ITiming](../../com.aspose.slides/itiming).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |