---
title: IMasterTheme
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: แสดงถึงธีมหลัก.
type: docs
url: /th/com.aspose.slides/imastertheme/
---
**ส่วนติดต่อที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

แสดงถึงธีมหลัก.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | คืนค่าชุดสีเพิ่มเติม |
| [getName()](#getName--) | คืนค่าชื่อของธีม |
| [setName(String value)](#setName-java.lang.String-) | คืนค่าชื่อของธีม |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```


คืนค่าชุดสีเพิ่มเติมเหล่านี้ไม่ส่งผลต่อรูปแบบของงานนำเสนอ สามารถเลือกเป็นชุดสีหลักสำหรับสไลด์ได้. อ่านอย่างเดียว [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**คืนค่า:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```


คืนค่าชื่อของธีม. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


คืนค่าชื่อของธีม. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |