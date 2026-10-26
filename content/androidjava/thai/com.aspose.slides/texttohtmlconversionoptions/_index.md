---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: ตัวเลือกสำหรับการแยก HTML จากข้อความ Pptx.
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

ตัวเลือกสำหรับการแยก HTML จากข้อความ Pptx.
## คอนสตรักเตอร์

| คอนสตรักเตอร์ | คำอธิบาย |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | คืนค่าหรือกำหนดค่า ซึ่งระบุว่าควรเพิ่มส่วนหัว Clipboard หรือไม่. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | คืนค่าหรือกำหนดค่า ซึ่งระบุว่าควรเพิ่มส่วนหัว Clipboard หรือไม่. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | คืนค่าหรือกำหนดค่าความลึกของการสืบทอดสำหรับคุณสมบัติข้อความ. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | คืนค่าหรือกำหนดค่าความลึกของการสืบทอดสำหรับคุณสมบัติข้อความ. |
| [getLinkEmbedController()](#getLinkEmbedController--) | คืนค่าหรือกำหนดออบเจกต์ callback ที่ควบคุมวิธีที่ออบเจกต์ภายนอกจะถูกจัดเก็บ. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | คืนค่าหรือกำหนดออบเจกต์ callback ที่ควบคุมวิธีที่ออบเจกต์ภายนอกจะถูกจัดเก็บ. |
| [getEncodingName()](#getEncodingName--) | คืนค่าหรือกำหนดชื่อการเข้ารหัส HTML. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | คืนค่าหรือกำหนดชื่อการเข้ารหัส HTML. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


คืนค่าหรือกำหนดค่า ซึ่งระบุว่าควรเพิ่มส่วนหัว Clipboard หรือไม่. อ่าน/เขียน boolean.

**Returns:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


คืนค่าหรือกำหนดค่า ซึ่งระบุว่าควรเพิ่มส่วนหัว Clipboard หรือไม่. อ่าน/เขียน boolean.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


คืนค่าหรือกำหนดค่าความลึกของการสืบทอดสำหรับคุณสมบัติข้อความ. อ่าน/เขียน [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Returns:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


คืนค่าหรือกำหนดค่าความลึกของการสืบทอดสำหรับคุณสมบัติข้อความ. อ่าน/เขียน [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


คืนค่าหรือกำหนดออบเจกต์ callback ที่ควบคุมวิธีที่ออบเจกต์ภายนอกจะถูกจัดเก็บ. อ่าน/เขียน [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Returns:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


คืนค่าหรือกำหนดออบเจกต์ callback ที่ควบคุมวิธีที่ออบเจกต์ภายนอกจะถูกจัดเก็บ. อ่าน/เขียน [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


คืนค่าหรือกำหนดชื่อการเข้ารหัส HTML. ค่านี้จะถูกบันทึกลงในไฟล์ HTML ที่สร้างขึ้น แต่ผู้เรียกต้องรับรองว่าไฟล์จะถูกบันทึกด้วยการเข้ารหัสนี้. อ่าน/เขียน String.

**Returns:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


คืนค่าหรือกำหนดชื่อการเข้ารหัส HTML. ค่านี้จะถูกบันทึกลงในไฟล์ HTML ที่สร้างขึ้น แต่ผู้เรียกต้องรับรองว่าไฟล์จะถูกบันทึกด้วยการเข้ารหัสนี้. อ่าน/เขียน String.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |