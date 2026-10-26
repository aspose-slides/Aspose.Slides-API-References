---
title: FieldType
second_title: การอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของประเภทของฟิลด์.
type: docs
url: /th/com.aspose.slides/fieldtype/
---
**การสืบทอด:**
java.lang.Object

**ทุกอินเทอร์เฟซที่ทำการ Implement:**
[com.aspose.slides.IFieldType](../../com.aspose.slides/ifieldtype)
```
public final class FieldType implements IFieldType
```

เป็นตัวแทนของประเภทของฟิลด์ ค่านี้กำหนดข้อความที่จะตั้งค่าให้กับส่วนของฟิลด์เมื่อมีการอัปเดต

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [FieldType(String str)](#FieldType-java.lang.String-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส FieldType. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getInternalString()](#getInternalString--) | ส่งคืนชื่อภายในของอ็อบเจ็กต์ FieldType นี้. |
| [setInternalString(String value)](#setInternalString-java.lang.String-) | ส่งคืนชื่อภายในของอ็อบเจ็กต์ FieldType นี้. |
| [equals(Object obj)](#equals-java.lang.Object-) | ตรวจสอบว่า ฟิลด์นี้เท่ากับฟิลด์อื่นหรือไม่. |
| [hashCode()](#hashCode--) | ส่งคืนค่า hashcode ของอ็อบเจ็กต์นี้. |
| [op_Equality(FieldType a, FieldType b)](#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | ตรวจสอบว่าสองอ็อบเจ็กต์ FieldType เท่ากันหรือไม่. |
| [op_Inequality(FieldType a, FieldType b)](#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | ตรวจสอบว่าสองอ็อบเจ็กต์ FieldType ไม่เท่ากันหรือไม่. |
| [getSlideNumber()](#getSlideNumber--) | หมายเลขสไลด์ปัจจุบัน. |
| [getFooter()](#getFooter--) | ส่วนท้ายของสไลด์. |
| [getHeader()](#getHeader--) | ส่วนหัวของสไลด์. |
| [getDateTime()](#getDateTime--) | วันที่และเวลาปัจจุบันในรูปแบบวันที่/เวลาเริ่มต้นของแอปพลิเคชันการแสดงผล. |
| [getDateTime1()](#getDateTime1--) | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับแรก (MM/DD/YYYY สำหรับภาษาอังกฤษ). |
| [getDateTime2()](#getDateTime2--) | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับสอง (Day, Month DD, YYYY สำหรับภาษาอังกฤษ). |
| [getDateTime3()](#getDateTime3--) | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับสาม (DD Month YYYY สำหรับภาษาอังกฤษ). |
| [getDateTime4()](#getDateTime4--) | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับสี่ (Month DD, YYYY สำหรับภาษาอังกฤษ). |
| [getDateTime5()](#getDateTime5--) | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับห้า (DD-Mon-YY สำหรับภาษาอังกฤษ). |
| [getDateTime6()](#getDateTime6--) | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับหก (Month YY สำหรับภาษาอังกฤษ). |
| [getDateTime7()](#getDateTime7--) | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับเจ็ด (Mon-YY สำหรับภาษาอังกฤษ). |
| [getDateTime8()](#getDateTime8--) | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับแปด (MM/DD/YYYY hh:mm AM/PM สำหรับภาษาอังกฤษ). |
| [getDateTime9()](#getDateTime9--) | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับเก้า (MM/DD/YYYY hh:mm:ss AM/PM สำหรับภาษาอังกฤษ). |
| [getDateTime10()](#getDateTime10--) | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับสิบ (hh:mm สำหรับภาษาอังกฤษ). |
| [getDateTime11()](#getDateTime11--) | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับสิบเอ็ด (hh:mm:ss สำหรับภาษาอังกฤษ). |
| [getDateTime12()](#getDateTime12--) | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับสิบสอง (hh:mm AM/PM สำหรับภาษาอังกฤษ). |
| [getDateTime13()](#getDateTime13--) | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับสิบสาม (hh:mm:ss AM/PM สำหรับภาษาอังกฤษ). |

### FieldType(String str) {#FieldType-java.lang.String-}
```
public FieldType(String str)
```

เริ่มต้นอินสแตนซ์ใหม่ของคลาส FieldType.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| str | java.lang.String |  |

### getInternalString() {#getInternalString--}
```
public final String getInternalString()
```

ส่งคืนชื่อภายในของอ็อบเจ็กต์ FieldType นี้. อ่าน/เขียน String.

**ส่งคืน:**
java.lang.String

### setInternalString(String value) {#setInternalString-java.lang.String-}
```
public final void setInternalString(String value)
```

ส่งคืนชื่อภายในของอ็อบเจ็กต์ FieldType นี้. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

ตรวจสอบว่า ฟิลด์นี้เท่ากับฟิลด์อื่นหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | ฟิลด์ที่เปรียบเทียบ. |

**ส่งคืน:**
boolean - true หากฟิลด์เท่ากัน.

### hashCode() {#hashCode--}
```
public int hashCode()
```

ส่งคืนค่า hashcode ของอ็อบเจ็กต์นี้.

**ส่งคืน:**
int - ค่าตัวเลขของ hashcode.

### op_Equality(FieldType a, FieldType b) {#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Equality(FieldType a, FieldType b)
```

ตรวจสอบว่าสองอ็อบเจ็กต์ FieldType เท่ากันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | FieldType ตัวแรกที่เปรียบเทียบ. |
| b | [FieldType](../../com.aspose.slides/fieldtype) | FieldType ตัวที่สองที่เปรียบเทียบ. |

**ส่งคืน:**
boolean - true หากอ็อบเจ็กต์ FieldType เท่ากัน.

### op_Inequality(FieldType a, FieldType b) {#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Inequality(FieldType a, FieldType b)
```

ตรวจสอบว่าสองอ็อบเจ็กต์ FieldType ไม่เท่ากันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | FieldType ตัวแรกที่เปรียบเทียบ. |
| b | [FieldType](../../com.aspose.slides/fieldtype) | FieldType ตัวที่สองที่เปรียบเทียบ. |

**ส่งคืน:**
boolean - true หากอ็อบเจ็กต์ FieldType ไม่เท่ากัน.

### getSlideNumber() {#getSlideNumber--}
```
public static FieldType getSlideNumber()
```

หมายเลขสไลด์ปัจจุบัน. อ่านอย่างเดียว [FieldType](../../com.aspose.slides/fieldtype).

**ส่งคืน:**
[FieldType](../../com.aspose.slides/fieldtype)

### getFooter() {#getFooter--}
```
public static FieldType getFooter()
```

ส่วนท้ายของสไลด์. อ่านอย่างเดียว [FieldType](../../com.aspose.slides/fieldtype).

**ส่งคืน:**
[FieldType](../../com.aspose.slides/fieldtype)

### getHeader() {#getHeader--}
```
public static FieldType getHeader()
```

ส่วนหัวของสไลด์. อ่านอย่างเดียว [FieldType](../../com.aspose.slides/fieldtype).

**ส่งคืน:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime() {#getDateTime--}
```
public static FieldType getDateTime()
```

วันที่และเวลาปัจจุบันในรูปแบบวันที่/เวลาเริ่มต้นของแอปพลิเคชันการแสดงผล. อ่านอย่างเดียว [FieldType](../../com.aspose.slides/fieldtype).

**ส่งคืน:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime1() {#getDateTime1--}
```
public static FieldType getDateTime1()
```

วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับแรก (MM/DD/YYYY สำหรับภาษาอังกฤษ). อ่านอย่างเดียว [FieldType](../../com.aspose.slides/fieldtype).

**ส่งคืน:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime2() {#getDateTime2--}
```
public static FieldType getDateTime2()
```

วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับสอง (Day, Month DD, YYYY สำหรับภาษาอังกฤษ). อ่านอย่างเดียว [FieldType](../../com.aspose.slides/fieldtype).

**ส่งคืน:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime3() {#getDateTime3--}
```
public static FieldType getDateTime3()
```

วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับสาม (DD Month YYYY สำหรับภาษาอังกฤษ). อ่านอย่างเดียว [FieldType](../../com.aspose.slides/fieldtype).

**ส่งคืน:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime4() {#getDateTime4--}
```
public static FieldType getDateTime4()
```

วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับสี่ (Month DD, YYYY สำหรับภาษาอังกฤษ). อ่านอย่างเดียว [FieldType](../../com.aspose.slides/fieldtype).

**ส่งคืน:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime5() {#getDateTime5--}
```
public static FieldType getDateTime5()
```

วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับห้า (DD-Mon-YY สำหรับภาษาอังกฤษ). อ่านอย่างเดียว [FieldType](../../com.aspose.slides/fieldtype).

**ส่งคืน:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime6() {#getDateTime6--}
```
public static FieldName getDateTime6()
```

วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับหก (Month YY สำหรับภาษาอังกฤษ). อ่านอย่างเดียว [FieldType](../../com.aspose.slides/fieldtype).

**ส่งคืน:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime7() {#getDateTime7--}
```
public static FieldType getDateTime7()
```

วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับเจ็ด (Mon-YY สำหรับภาษาอังกฤษ). อ่านอย่างเดียว [FieldType](../../com.aspose.slides/fieldtype).

**ส่งคืน:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime8() {#getDateTime8--}
```
public static FieldType getDateTime8()
```

วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับแปด (MM/DD/YYYY hh:mm AM/PM สำหรับภาษาอังกฤษ). อ่านอย่างเดียว [FieldType](../../com.aspose.slides/fieldtype).

**ส่งคืน:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime9() {#getDateTime9--}
```
public static FieldType getDateTime9()
```

วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับเก้า (MM/DD/YYYY hh:mm:ss AM/PM สำหรับภาษาอังกฤษ). อ่านอย่างเดียว [FieldType](../../com.aspose.slides/fieldtype).

**ส่งคืน:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime10() {#getDateTime10--}
```
public static FieldType getDateTime10()
```

วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับสิบ (hh:mm สำหรับภาษาอังกฤษ). อ่านอย่างเดียว [FieldType](../../com.aspose.slides/fieldtype).

**ส่งคืน:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime11() {#getDateTime11--}
```
public static FieldType getDateTime11()
```

วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับสิบเอ็ด (hh:mm:ss สำหรับภาษาอังกฤษ). อ่านอย่างเดียว [FieldType](../../com.aspose.slides/fieldtype).

**ส่งคืน:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime12() {#getDateTime12--}
```
public static FieldType getDateTime12()
```

วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับสิบสอง (hh:mm AM/PM สำหรับภาษาอังกฤษ). อ่านอย่างเดียว [FieldType](../../com.aspose.slides/fieldtype).

**ส่งคืน:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime13() {#getDateTime13--}
```
public static FieldType getDateTime13()
```

วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดล่วงหน้าอันดับสิบสาม (hh:mm:ss AM/PM สำหรับภาษาอังกฤษ). อ่านอย่างเดียว [FieldType](../../com.aspose.slides/fieldtype).

**ส่งคืน:**
[FieldType](../../com.aspose.slides/fieldtype)