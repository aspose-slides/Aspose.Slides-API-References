---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides สำหรับ Java API Reference
description: ตัวเลือกสำหรับการสกัด HTML จากข้อความ Pptx.
type: docs
url: /th/com.aspose.slides/texttohtmlconversionoptions/
---
**การสืบทอด:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

ตัวเลือกสำหรับการสกัด HTML จากข้อความ Pptx.
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | คืนค่า หรือ ตั้งค่า value, ระบุว่า ควรเพิ่มส่วนหัว Clipboard หรือไม่. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | คืนค่า หรือ ตั้งค่า value, ระบุว่า ควรเพิ่มส่วนหัว Clipboard หรือไม่. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | คืนค่า หรือ ตั้งค่า inhering depth สำหรับคุณสมบัติดข้อความ. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | คืนค่า หรือ ตั้งค่า inhering depth สำหรับคุณสมบัติดข้อความ. |
| [getLinkEmbedController()](#getLinkEmbedController--) | คืนค่า หรือ ตั้งค่าอ็อบเจกต์ callback ซึ่งควบคุมวิธีที่อ็อบเจกต์ภายนอกจะถูกจัดเก็บ. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | คืนค่า หรือ ตั้งค่าอ็อบเจกต์ callback ซึ่งควบคุมวิธีที่อ็อบเจกต์ภายนอกจะถูกจัดเก็บ. |
| [getEncodingName()](#getEncodingName--) | คืนค่า หรือ ตั้งค่า html encoding name. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | คืนค่า หรือ ตั้งค่า html encoding name. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```

### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```

คืนค่า หรือ ตั้งค่า value, ระบุว่า ควรเพิ่มส่วนหัว Clipboard หรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```

คืนค่า หรือ ตั้งค่า value, ระบุว่า ควรเพิ่มส่วนหัว Clipboard หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```

คืนค่า หรือ ตั้งค่า inhering depth สำหรับคุณสมบัติดข้อความ. อ่าน/เขียน [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**คืนค่า:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```

คืนค่า หรือ ตั้งค่า inhering depth สำหรับคุณสมบัติดข้อความ. อ่าน/เขียน [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```

คืนค่า หรือ ตั้งค่าอ็อบเจกต์ callback ซึ่งควบคุมวิธีที่อ็อบเจกต์ภายนอกจะถูกจัดเก็บ. อ่าน/เขียน [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**คืนค่า:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```

คืนค่า หรือ ตั้งค่าอ็อบเจกต์ callback ซึ่งควบคุมวิธีที่อ็อบเจกต์ภายนอกจะถูกจัดเก็บ. อ่าน/เขียน [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```

คืนค่า หรือ ตั้งค่า html encoding name. ค่าดังกล่าวจะถูกบันทึกลงในไฟล์ HTML ที่สร้างขึ้น, แต่ขึ้นกับผู้เรียกเพื่อให้แน่ใจว่าไฟล์จะถูกบันทึกด้วยการเข้ารหัสนี้. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```

คืนค่า หรือ ตั้งค่า html encoding name. ค่าดังกล่าวจะถูกบันทึกลงในไฟล์ HTML ที่สร้างขึ้น, แต่ขึ้นกับผู้เรียกเพื่อให้แน่ใจว่าไฟล์จะถูกบันทึกด้วยการเข้ารหัสนี้. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |