---
title: IBehavior
second_title: Aspose.Slides for Java API Reference
description: Represent base class behavior of effect.
type: docs
url: /th/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

แสดงพฤติกรรมของคลาสฐานของเอฟเฟกต์
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | แสดงว่าพฤติกรรมแอนิเมชันจะถูกสั่งรวมกันหรือไม่ |
| [setAccumulate(byte value)](#setAccumulate-byte-) | แสดงว่าพฤติกรรมแอนิเมชันจะถูกสั่งรวมกันหรือไม่ |
| [getAdditive()](#getAdditive--) | แสดงว่าพฤติกรรมแอนิเมชันปัจจุบันจะถูกรวมกับแอนิเมชันอื่นที่กำลังทำงานอยู่หรือไม่ |
| [setAdditive(int value)](#setAdditive-int-) | แสดงว่าพฤติกรรมแอนิเมชันปัจจุบันจะถูกรวมกับแอนิเมชันอื่นที่กำลังทำงานอยู่หรือไม่ |
| [getProperties()](#getProperties--) | แสดงคุณสมบัติของพฤติกรรม |
| [getTiming()](#getTiming--) | แสดงคุณสมบัติการกำหนดเวลา สำหรับพฤติกรรมเอฟเฟกต์ |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | แสดงคุณสมบัติการกำหนดเวลา สำหรับพฤติกรรมเอฟเฟกต์ |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

แสดงว่าพฤติกรรมแอนิเมชันจะถูกสั่งรวมกันหรือไม่ อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

แสดงว่าพฤติกรรมแอนิเมชันจะถูกสั่งรวมกันหรือไม่ อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

แสดงว่าพฤติกรรมแอนิเมชันปัจจุบันจะถูกรวมกับแอนิเมชันอื่นที่กำลังทำงานอยู่หรือไม่ อ่าน/เขียน [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**คืนค่า:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

แสดงว่าพฤติกรรมแอนิเมชันปัจจุบันจะถูกรวมกับแอนิเมชันอื่นที่กำลังทำงานอยู่หรือไม่ อ่าน/เขียน [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

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

แสดงคุณสมบัติการกำหนดเวลา สำหรับพฤติกรรมเอฟเฟกต์ อ่าน/เขียน [ITiming](../../com.aspose.slides/itiming).

**คืนค่า:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

แสดงคุณสมบัติการกำหนดเวลา สำหรับพฤติกรรมเอฟเฟกต์ อ่าน/เขียน [ITiming](../../com.aspose.slides/itiming).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |