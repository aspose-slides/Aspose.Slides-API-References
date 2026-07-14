---
title: Behavior
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงพฤติกรรมของคลาสฐานของเอฟเฟกต์.
type: docs
url: /th/com.aspose.slides/behavior/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

แสดงพฤติกรรมของคลาสฐานสำหรับเอฟเฟกต์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | แสดงว่าพฤติกรรมการเคลื่อนที่แบบแอนิเมชันถูกสะสมหรือไม่ |
| [setAccumulate(byte value)](#setAccumulate-byte-) | แสดงว่าพฤติกรรมการเคลื่อนที่แบบแอนิเมชันถูกสะสมหรือไม่ |
| [getAdditive()](#getAdditive--) | แสดงว่าพฤติกรรมการเคลื่อนที่แบบแอนิเมชันปัจจุบันถูกรวมกับแอนิเมชันอื่นที่กำลังทำงานหรือไม่ |
| [setAdditive(int value)](#setAdditive-int-) | แสดงว่าพฤติกรรมการเคลื่อนที่แบบแอนิเมชันปัจจุบันถูกรวมกับแอนิเมชันอื่นที่กำลังทำงานหรือไม่ |
| [getProperties()](#getProperties--) | แสดงคุณสมบัติของพฤติกรรม |
| [getTiming()](#getTiming--) | แสดงคุณสมบัติการจับเวลาสำหรับพฤติกรรมเอฟเฟกต์ |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | แสดงคุณสมบัติการจับเวลาสำหรับพฤติกรรมเอฟเฟกต์ |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งคืนอ็อบเจกต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```

แสดงว่าพฤติกรรมการเคลื่อนที่แบบแอนิเมชันถูกสะสมหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```

แสดงว่าพฤติกรรมการเคลื่อนที่แบบแอนิเมชันถูกสะสมหรือไม่. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```

แสดงว่าพฤติกรรมการเคลื่อนที่แบบแอนิเมชันปัจจุบันถูกรวมกับแอนิเมชันอื่นที่กำลังทำงานหรือไม่. อ่าน/เขียน [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**คืนค่า:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```

แสดงว่าพฤติกรรมการเคลื่อนที่แบบแอนิเมชันปัจจุบันถูกรวมกับแอนิเมชันอื่นที่กำลังทำงานหรือไม่. อ่าน/เขียน [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
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

แสดงคุณสมบัติการจับเวลาสำหรับพฤติกรรมเอฟเฟกต์. อ่าน/เขียน [ITiming](../../com.aspose.slides/itiming).

**คืนค่า:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

แสดงคุณสมบัติการจับเวลาสำหรับพฤติกรรมเอฟเฟกต์. อ่าน/เขียน [ITiming](../../com.aspose.slides/itiming).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |