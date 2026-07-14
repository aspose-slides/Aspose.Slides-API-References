---
title: IMasterTheme
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของธีมหลัก.
type: docs
url: /th/com.aspose.slides/imastertheme/
---
**ทุกอินเทอร์เฟซที่ใช้งาน:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

เป็นตัวแทนของธีมหลัก.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | คืนค่าคอลเลกชันของโครงสร้างสีเพิ่มเติม. |
| [getName()](#getName--) | คืนค่าชื่อของธีม. |
| [setName(String value)](#setName-java.lang.String-) | คืนค่าชื่อของธีม. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```

คืนค่าคอลเลกชันของโครงสร้างสีเพิ่มเติม โครงสร้างสีเหล่านี้ไม่ส่งผลต่อรูปลักษณ์ของงานนำเสนอ สามารถเลือกเป็นโครงสร้างสีหลักสำหรับสไลด์ได้ อ่านอย่างเดียว [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

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