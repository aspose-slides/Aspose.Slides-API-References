---
title: IBehavior
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงพฤติกรรมคลาสฐานของเอฟเฟกต์
type: docs
url: /th/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

แสดงพฤติกรรมคลาสฐานของเอฟเฟกต์
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | แสดงว่าแอนิเมชันบีเฮเวียร์ถูกสะสมหรือไม่ |
| [setAccumulate(byte value)](#setAccumulate-byte-) | แสดงว่าแอนิเมชันบีเฮเวียร์ถูกสะสมหรือไม่ |
| [getAdditive()](#getAdditive--) | แสดงว่าแอนิเมชันบีเฮเวียร์ปัจจุบันถูกรวมกับแอนิเมชันที่กำลังทำงานอื่นหรือไม่ |
| [setAdditive(int value)](#setAdditive-int-) | แสดงว่าแอนิเมชันบีเฮเวียร์ปัจจุบันถูกรวมกับแอนิเมชันที่กำลังทำงานอื่นหรือไม่ |
| [getProperties()](#getProperties--) | แสดงคุณสมบัติของพฤติกรรม |
| [getTiming()](#getTiming--) | แสดงคุณสมบัติการกำหนดเวลาสำหรับพฤติกรรมเอฟเฟกต์ |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | แสดงคุณสมบัติการกำหนดเวลาสำหรับพฤติกรรมเอฟเฟกต์ |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

แสดงว่าแอนิเมชันบีเฮเวียร์ถูกสะสมหรือไม่ อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

แสดงว่าแอนิเมชันบีเฮเวียร์ถูกสะสมหรือไม่ อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

แสดงว่าแอนิเมชันบีเฮเวียร์ปัจจุบันถูกรวมกับแอนิเมชันที่กำลังทำงานอื่นหรือไม่ อ่าน/เขียน [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**คืนค่า:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

แสดงว่าแอนิเมชันบีเฮเวียร์ปัจจุบันถูกรวมกับแอนิเมชันที่กำลังทำงานอื่นหรือไม่ อ่าน/เขียน [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

แสดงคุณสมบัติของพฤติกรรม อ่านอย่างเดียว [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**คืนค่า:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

แสดงคุณสมบัติการกำหนดเวลาสำหรับพฤติกรรมเอฟเฟกต์ อ่าน/เขียน [ITiming](../../com.aspose.slides/itiming).

**คืนค่า:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

แสดงคุณสมบัติการกำหนดเวลาสำหรับพฤติกรรมเอฟเฟกต์ อ่าน/เขียน [ITiming](../../com.aspose.slides/itiming).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |