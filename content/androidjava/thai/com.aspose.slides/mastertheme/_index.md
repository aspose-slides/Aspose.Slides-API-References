---
title: MasterTheme
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แทนธีมหลัก.
type: docs
url: /th/com.aspose.slides/mastertheme/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)  
```
public final class MasterTheme extends Theme implements IMasterTheme
```

แทนธีมหลัก.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | ส่งคืนชุดสี |
| [getFontScheme()](#getFontScheme--) | ส่งคืนชุดฟอนต์ |
| [getFormatScheme()](#getFormatScheme--) | ส่งคืนชุดรูปแบบรูปร่าง |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | ส่งคืนคอลเลกชันของชุดสีเพิ่มเติม |
| [getName()](#getName--) | ส่งคืนชื่อของธีม |
| [setName(String value)](#setName-java.lang.String-) | ส่งคืนชื่อของธีม |
| [getVersion()](#getVersion--) |  |

### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```

ส่งคืนชุดสี. อ่านอย่างเดียว [IColorScheme](../../com.aspose.slides/icolorscheme).

**คืนค่า:**  
[IColorScheme](../../com.aspose.slides/icolorscheme)

### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```

ส่งคืนชุดฟอนต์. อ่านอย่างเดียว [IFontScheme](../../com.aspose.slides/ifontscheme).

**คืนค่า:**  
[IFontScheme](../../com.aspose.slides/ifontscheme)

### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

ส่งคืนชุดรูปแบบรูปร่าง. อ่านอย่างเดียว [IFormatScheme](../../com.aspose.slides/iformatscheme).

**คืนค่า:**  
[IFormatScheme](../../com.aspose.slides/iformatscheme)

### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```

ส่งคืนคอลเลกชันของชุดสีเพิ่มเติม. ชุดสีเหล่านี้ไม่ส่งผลต่อรูปลักษณ์ของการนำเสนอ, สามารถเลือกเป็นชุดสีหลักสำหรับสไลด์ได้. อ่านอย่างเดียว [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**คืนค่า:**  
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)

### getName() {#getName--}
```
public final String getName()
```

ส่งคืนชื่อของธีม. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

ส่งคืนชื่อของธีม. อ่าน/เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**  
long