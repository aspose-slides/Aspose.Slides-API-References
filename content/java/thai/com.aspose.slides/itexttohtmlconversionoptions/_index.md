---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Java API Reference
description: ตัวเลือกสำหรับการแปลง HTML จากข้อความของไฟล์ Pptx.
type: docs
url: /th/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

ตัวเลือกสำหรับการแปลง HTML จากข้อความของไฟล์ Pptx.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | คืนค่าหรือกำหนดค่า ที่บ่งบอกว่าควรเพิ่มส่วนหัว Clipboard หรือไม่. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | คืนค่าหรือกำหนดค่า ที่บ่งบอกว่าควรเพิ่มส่วนหัว Clipboard หรือไม่. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | คืนค่าหรือกำหนดระดับการสืบทอดของคุณสมบัติข้อความ. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | คืนค่าหรือกำหนดระดับการสืบทอดของคุณสมบัติข้อความ. |
| [getLinkEmbedController()](#getLinkEmbedController--) | คืนค่าหรือกำหนดอ็อบเจ็กต์ callback ที่ควบคุมว่าภายนอกจะถูกเก็บอย่างไร. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | คืนค่าหรือกำหนดอ็อบเจ็กต์ callback ที่ควบคุมว่าภายนอกจะถูกเก็บอย่างไร. |
| [getEncodingName()](#getEncodingName--) | คืนค่าหรือกำหนดชื่อการเข้ารหัส HTML. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | คืนค่าหรือกำหนดชื่อการเข้ารหัส HTML. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```


คืนค่าหรือกำหนดค่า ที่บ่งบอกว่าควรเพิ่มส่วนหัว Clipboard หรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```


คืนค่าหรือกำหนดค่า ที่บ่งบอกว่าควรเพิ่มส่วนหัว Clipboard หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```


คืนค่าหรือกำหนดระดับการสืบทอดของคุณสมบัติข้อความ. อ่าน/เขียน [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**คืนค่า:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```


คืนค่าหรือกำหนดระดับการสืบทอดของคุณสมบัติข้อความ. อ่าน/เขียน [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```


คืนค่าหรือกำหนดอ็อบเจ็กต์ callback ที่ควบคุมว่าภายนอกจะถูกเก็บอย่างไร. อ่าน/เขียน [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**คืนค่า:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```


คืนค่าหรือกำหนดอ็อบเจ็กต์ callback ที่ควบคุมว่าภายนอกจะถูกเก็บอย่างไร. อ่าน/เขียน [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```


คืนค่าหรือกำหนดชื่อการเข้ารหัส HTML. ค่าดังกล่าวจะถูกบันทึกลงไฟล์ HTML ที่สร้างขึ้น แต่ผู้เรียกต้องรับประกันว่าไฟล์จะถูกบันทึกด้วยการเข้ารหัสนี้. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```


คืนค่าหรือกำหนดชื่อการเข้ารหัส HTML. ค่าดังกล่าวจะถูกบันทึกลงไฟล์ HTML ที่สร้างขึ้นแต่ผู้เรียกต้องรับประกันว่าไฟล์จะถูกบันทึกด้วยการเข้ารหัสนี้. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |