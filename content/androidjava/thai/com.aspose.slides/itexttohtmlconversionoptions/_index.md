---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Options for extracting HTML from the Pptx text.
type: docs
url: /th/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

ตัวเลือกสำหรับการแปลงข้อความใน Pptx เป็น HTML.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | คืนค่า หรือกำหนดค่า ซึ่งบ่งชี้ว่าควรเพิ่มส่วนหัว Clipboard หรือไม่. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | คืนค่า หรือกำหนดค่า ซึ่งบ่งชี้ว่าควรเพิ่มส่วนหัว Clipboard หรือไม่. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | คืนค่า หรือกำหนดค่าความลึกการสืบทอดสำหรับคุณสมบัติข้อความ. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | คืนค่า หรือกำหนดค่าความลึกการสืบทอดสำหรับคุณสมบัติข้อความ. |
| [getLinkEmbedController()](#getLinkEmbedController--) | คืนค่า หรือกำหนดอ็อบเจ็กต์ callback ที่ควบคุมวิธีการจัดเก็บอ็อบเจ็กต์ภายนอก. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | คืนค่า หรือกำหนดอ็อบเจ็กต์ callback ที่ควบคุมวิธีการจัดเก็บอ็อบเจ็กต์ภายนอก. |
| [getEncodingName()](#getEncodingName--) | คืนค่า หรือกำหนดชื่อการเข้ารหัส HTML. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | คืนค่า หรือกำหนดชื่อการเข้ารหัส HTML. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

คืนค่า หรือกำหนดค่า ซึ่งบ่งชี้ว่าควรเพิ่มส่วนหัว Clipboard หรือไม่. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

คืนค่า หรือกำหนดค่า ซึ่งบ่งชี้ว่าควรเพิ่มส่วนหัว Clipboard หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

คืนค่า หรือกำหนดค่าความลึกการสืบทอดสำหรับคุณสมบัติข้อความ. อ่าน/เขียน [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**ผลลัพธ์:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

คืนค่า หรือกำหนดค่าความลึกการสืบทอดสำหรับคุณสมบัติข้อความ. อ่าน/เขียน [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

คืนค่า หรือกำหนดอ็อบเจ็กต์ callback ที่ควบคุมวิธีการจัดเก็บอ็อบเจ็กต์ภายนอก. อ่าน/เขียน [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**ผลลัพธ์:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

คืนค่า หรือกำหนดอ็อบเจ็กต์ callback ที่ควบคุมวิธีการจัดเก็บอ็อบเจ็กต์ภายนอก. อ่าน/เขียน [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

คืนค่า หรือกำหนดชื่อการเข้ารหัส HTML. ค่าดังกล่าวจะถูกบันทึกลงในไฟล์ HTML ที่สร้างขึ้น แต่ผู้เรียกต้องรับผิดชอบให้แน่ใจว่าไฟล์จะถูกบันทึกด้วยการเข้ารหัสนี้. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

คืนค่า หรือกำหนดชื่อการเข้ารหัส HTML. ค่าดังกล่าวจะถูกบันทึกลงในไฟล์ HTML ที่สร้างขึ้น แต่ผู้เรียกต้องรับผิดชอบให้แน่ใจว่าไฟล์จะถูกบันทึกด้วยการเข้ารหัสนี้. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |