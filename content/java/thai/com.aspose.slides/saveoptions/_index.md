---
title: SaveOptions
second_title: Aspose.Slides สำหรับ Java API Reference
description: คลาสนามธรรมที่มีตัวเลือกควบคุมการบันทึกการนำเสนอ
type: docs
url: /th/com.aspose.slides/saveoptions/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

คลาสนามธรรมที่มีตัวเลือกควบคุมการบันทึกการนำเสนอ
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | คืนค่า หรือกำหนดอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือจะถูกยกเลิก |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | คืนค่า หรือกำหนดอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือจะถูกยกเลิก |
| [getProgressCallback()](#getProgressCallback--) | แสดงถึงอ็อบเจกต์ callback สำหรับอัปเดตความคืบหน้าการบันทึกเป็นเปอร์เซ็นต์ |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | แสดงถึงอ็อบเจกต์ callback สำหรับอัปเดตความคืบหน้าการบันทึกเป็นเปอร์เซ็นต์ |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | คืนค่า หรือกำหนดฟอนต์ที่ใช้ในกรณีที่ไม่พบฟอนต์ต้นฉบับ |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | คืนค่า หรือกำหนดฟอนต์ที่ใช้ในกรณีที่ไม่พบฟอนต์ต้นฉบับ |
| [getGradientStyle()](#getGradientStyle--) | คืนค่า หรือกำหนดสไตล์ภาพกราดient ของ gradient |
| [setGradientStyle(int value)](#setGradientStyle-int-) | คืนค่า หรือกำหนดสไตล์ภาพกราดient ของ gradient |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกการนำเสนอ |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกการนำเสนอ |

### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

คืนค่า หรือกำหนดอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือจะถูกยกเลิก. อ่าน/เขียน [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**ค่าที่ส่งกลับ:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

คืนค่า หรือกำหนดอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือจะถูกยกเลิก. อ่าน/เขียน [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```

แสดงถึงอ็อบเจกต์ callback สำหรับอัปเดตความคืบหน้าการบันทึกเป็นเปอร์เซ็นต์. ดู [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**ค่าที่ส่งกลับ:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```

แสดงถึงอ็อบเจกต์ callback สำหรับอัปเดตความคืบหน้าการบันทึกเป็นเปอร์เซ็นต์. ดู [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

คืนค่า หรือกำหนดฟอนต์ที่ใช้ในกรณีที่ไม่พบฟอนต์ต้นฉบับ. อ่าน-เขียน String.

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

**ค่าที่ส่งกลับ:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

คืนค่า หรือกำหนดฟอนต์ที่ใช้ในกรณีที่ไม่พบฟอนต์ต้นฉบับ. อ่าน-เขียน String.

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
public final int getGradientStyle()
```

คืนค่า หรือกำหนดสไตล์ภาพกราดient ของ gradient. อ่าน/เขียน [GradientStyle](../../com.aspose.slides/gradientstyle).

**ค่าที่ส่งกลับ:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```

คืนค่า หรือกำหนดสไตล์ภาพกราดient ของ gradient. อ่าน/เขียน [GradientStyle](../../com.aspose.slides/gradientstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
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

--------------------

เมื่อคุณสมบัตินี้ตั้งค่าเป็น true, ไฮเปอร์ลิงก์ที่มีการเรียก JavaScript จะถูกละเลยขณะบันทึก.

เมื่อคุณสมบัตินี้ตั้งค่าเป็น false, ไฮเปอร์ลิงก์ทั้งหมดจะถูกบันทึก.

**ค่าที่ส่งกลับ:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
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

--------------------

เมื่อคุณสมบัตินี้ตั้งค่าเป็น true, ไฮเปอร์ลิงก์ที่มีการเรียก JavaScript จะถูกละเลยขณะบันทึก.

เมื่อคุณสมบัตินี้ตั้งค่าเป็น false, ไฮเปอร์ลิงก์ทั้งหมดจะถูกบันทึก.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |