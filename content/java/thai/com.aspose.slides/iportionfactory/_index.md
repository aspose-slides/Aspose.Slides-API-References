---
title: IPortionFactory
second_title: Aspose.Slides for Java API Reference
description: อนุญาตให้สร้างส่วนทดสอบ
type: docs
url: /th/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

สำหรับความเข้ากันได้กับ COM
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createPortion()](#createPortion--) | Creates an empty text portion. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Creates a text portion from specified string. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Creates a portion with the using of a specified portion data. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```

สร้างส่วนข้อความเปล่า

**คืนค่า:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```

สร้างส่วนข้อความจากสตริงที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | java.lang.String | สตริง. |

**คืนค่า:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```

สร้างส่วนโดยใช้ข้อมูลส่วนที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | ส่วนที่จะใช้. |

**คืนค่า:**
[IPortion](../../com.aspose.slides/iportion) - Portion.