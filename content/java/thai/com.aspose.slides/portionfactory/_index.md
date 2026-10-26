---
title: PortionFactory
second_title: Aspose.Slides สำหรับ Java API Reference
description: อนุญาตให้สร้างส่วนทดสอบ
type: docs
url: /th/com.aspose.slides/portionfactory/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

อนุญาตให้สร้างส่วนทดสอบ

--------------------

สำหรับความเข้ากันได้ของ COM
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createPortion()](#createPortion--) | Creates an empty text portion. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Creates a text portion from specified string. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Creates a portion with the using of a specified portion data. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


สร้างส่วนข้อความเปล่า

**คืนค่า:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


สร้างส่วนข้อความจากสตริงที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| str | java.lang.String | String. |

**คืนค่า:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```


สร้างส่วนโดยใช้ข้อมูลส่วนที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | A portion to use. |

**คืนค่า:**
[IPortion](../../com.aspose.slides/iportion) - Portion.