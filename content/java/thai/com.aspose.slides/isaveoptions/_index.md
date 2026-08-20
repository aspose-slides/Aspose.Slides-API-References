---
title: ISaveOptions
second_title: Aspose.Slides for Java API Reference
description: Options that control how a presentation is saved.
type: docs
url: /th/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | คืนค่า หรือกำหนดอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | คืนค่า หรือกำหนดอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก |
| [getProgressCallback()](#getProgressCallback--) | แสดงอ็อบเจกต์ callback สำหรับอัปเดตความคืบหน้าในการบันทึกเป็นเปอร์เซ็นต์ |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | แสดงอ็อบเจกต์ callback สำหรับอัปเดตความคืบหน้าในการบันทึกเป็นเปอร์เซ็นต์ |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | คืนค่า หรือกำหนดฟอนต์ที่ใช้เมื่อไม่พบฟอนต์ต้นฉบับ |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | คืนค่า หรือกำหนดฟอนต์ที่ใช้เมื่อไม่พบฟอนต์ต้นฉบับ |
| [getGradientStyle()](#getGradientStyle--) | คืนค่า หรือกำหนดรูปแบบการแสดงผลของ gradient |
| [setGradientStyle(int value)](#setGradientStyle-int-) | คืนค่า หรือกำหนดรูปแบบการแสดงผลของ gradient |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกการนำเสนอ |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกการนำเสนอ |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

คืนค่า หรือกำหนดอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก. อ่าน/เขียน [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**ผลลัพธ์:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

คืนค่า หรือกำหนดอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก. อ่าน/เขียน [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```

แสดงอ็อบเจกต์ callback สำหรับอัปเดตความคืบหน้าในการบันทึกเป็นเปอร์เซ็นต์. ดู [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**ผลลัพธ์:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```

แสดงอ็อบเจกต์ callback สำหรับอัปเดตความคืบหน้าในการบันทึกเป็นเปอร์เซ็นต์. ดู [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

คืนค่า หรือกำหนดฟอนต์ที่ใช้เมื่อไม่พบฟอนต์ต้นฉบับ. อ่าน-เขียน String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**ผลลัพธ์:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

คืนค่า หรือกำหนดฟอนต์ที่ใช้เมื่อไม่พบฟอนต์ต้นฉบับ. อ่าน-เขียน String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public abstract int getGradientStyle()
```

คืนค่า หรือกำหนดรูปแบบการแสดงผลของ gradient. อ่าน/เขียน [GradientStyle](../../com.aspose.slides/gradientstyle).

**ผลลัพธ์:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```

คืนค่า หรือกำหนดรูปแบบการแสดงผลของ gradient. อ่าน/เขียน [GradientStyle](../../com.aspose.slides/gradientstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```

ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกการนำเสนอ. อ่าน/เขียน boolean. ค่าเริ่มต้นคือ false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


เมื่อคุณสมบัตินี้ตั้งค่าเป็น true, ไฮเปอร์ลิงก์ที่มีการเรียก JavaScript จะถูกละเว้นขณะบันทึก.

เมื่อคุณสมบัตินี้ตั้งค่าเป็น false, ไฮเปอร์ลิงก์ทั้งหมดจะถูกบันทึก.

**ผลลัพธ์:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
```

ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกการนำเสนอ. อ่าน/เขียน boolean. ค่าเริ่มต้นคือ false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

เมื่อคุณสมบัตินี้ตั้งค่าเป็น true, ไฮเปอร์ลิงก์ที่มีการเรียก JavaScript จะถูกละเว้นขณะบันทึก.

เมื่อคุณสมบัตินี้ตั้งค่าเป็น false, ไฮเปอร์ลิงก์ทั้งหมดจะถูกบันทึก.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |