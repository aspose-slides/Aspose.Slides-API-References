---
title: IPortionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create test portions
type: docs
url: /th/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

อนุญาตให้สร้างส่วนทดสอบ

--------------------

สำหรับความเข้ากันได้กับ COM
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createPortion()](#createPortion--) | สร้างส่วนข้อความเปล่า |
| [createPortion(String str)](#createPortion-java.lang.String-) | สร้างส่วนข้อความจากสตริงที่ระบุ |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | สร้างส่วนโดยใช้ข้อมูลส่วนที่ระบุ |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


สร้างส่วนข้อความเปล่า

**ผลลัพธ์:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```


สร้างส่วนข้อความจากสตริงที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | java.lang.String | String. |

**ผลลัพธ์:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```


สร้างส่วนโดยใช้ข้อมูลส่วนที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | ส่วนที่ใช้. |

**ผลลัพธ์:**
[IPortion](../../com.aspose.slides/iportion) - Portion.