---
title: PortionFactory
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: อนุญาตให้สร้างส่วนทดสอบ
type: docs
url: /th/com.aspose.slides/portionfactory/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ Implement ทั้งหมด:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

อนุญาตให้สร้างส่วนทดสอบ

--------------------

เพื่อความเข้ากันได้กับ COM
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createPortion()](#createPortion--) | สร้างส่วนข้อความเปล่า |
| [createPortion(String str)](#createPortion-java.lang.String-) | สร้างส่วนข้อความจากสตริงที่ระบุ |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | สร้างส่วนโดยใช้ข้อมูลส่วนที่ระบุ |
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | ส่วนที่จะใช้. |

**คืนค่า:**
[IPortion](../../com.aspose.slides/iportion) - Portion.