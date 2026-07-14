---
title: ISaveOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Options that control how a presentation is saved.
type: docs
url: /th/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอ
## เมธอด

| Method | Description |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | คืนค่า หรือ ตั้งค่าอ็อบเจ็กต์ที่รับคำเตือนและกำหนดว่ากระบวนการโหลดจะดำเนินต่อหรือจะถูกยกเลิก. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | คืนค่า หรือ ตั้งค่าอ็อบเจ็กต์ที่รับคำเตือนและกำหนดว่ากระบวนการโหลดจะดำเนินต่อหรือจะถูกยกเลิก. |
| [getProgressCallback()](#getProgressCallback--) | เป็นอ็อบเจ็กต์ callback ที่แสดงการอัปเดตความคืบหน้าการบันทึกเป็นเปอร์เซ็นต์. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | เป็นอ็อบเจ็กต์ callback ที่แสดงการอัปเดตความคืบหน้าการบันทึกเป็นเปอร์เซ็นต์. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | คืนค่า หรือ ตั้งค่าแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | คืนค่า หรือ ตั้งค่าแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ. |
| [getGradientStyle()](#getGradientStyle--) | คืนค่า หรือ ตั้งค่าสไตล์การแสดงผลของการไล่สี. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | คืนค่า หรือ ตั้งค่าสไตล์การแสดงผลของการไล่สี. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกงานนำเสนอ. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกงานนำเสนอ. |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```


คืนค่า หรือ ตั้งค่าอ็อบเจ็กต์ที่รับคำเตือนและกำหนดว่ากระบวนการโหลดจะดำเนินต่อหรือจะถูกยกเลิก. อ่าน/เขียน [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**คืนค่า:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```


คืนค่า หรือ ตั้งค่าอ็อบเจ็กต์ที่รับคำเตือนและกำหนดว่ากระบวนการโหลดจะดำเนินต่อหรือจะถูกยกเลิก. อ่าน/เขียน [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```


เป็นอ็อบเจ็กต์ callback ที่แสดงการอัปเดตความคืบหน้าการบันทึกเป็นเปอร์เซ็นต์. ดู [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**คืนค่า:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```


เป็นอ็อบเจ็กต์ callback ที่แสดงการอัปเดตความคืบหน้าการบันทึกเป็นเปอร์เซ็นต์. ดู [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```


คืนค่า หรือ ตั้งค่าแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ. อ่าน-เขียน String.

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

**คืนค่า:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```


คืนค่า หรือ ตั้งค่าแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ.อ่าน-เขียน String.

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


คืนค่า หรือ ตั้งค่าสไตล์การแสดงผลของการไล่สี. อ่าน/เขียน [GradientStyle](../../com.aspose.slides/gradientstyle).

**คืนค่า:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```


คืนค่า หรือ ตั้งค่าสไตล์การแสดงผลของการไล่สี. อ่าน/เขียน [GradientStyle](../../com.aspose.slides/gradientstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```


ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกงานนำเสนอ. อ่าน/เขียน boolean. ค่าเริ่มต้นคือ false.

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

เมื่อกำหนดคุณสมบัตินี้เป็น true, ไฮเปอร์ลิงก์ที่มีการเรียก JavaScript จะถูกละเว้นขณะบันทึก.

เมื่อกำหนดคุณสมบัตินี้เป็น false, ไฮเปอร์ลิงก์ทั้งหมดจะถูกบันทึก.

**คืนค่า:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
```


ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกงานนำเสนอ. อ่าน/เขียน boolean. ค่าเริ่มต้นคือ false.

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

เมื่อกำหนดคุณสมบัตินี้เป็น true, ไฮเปอร์ลิงก์ที่มีการเรียก JavaScript จะถูกละเว้นขณะบันทึก.

เมื่อกำหนดคุณสมบัตินี้เป็น false, ไฮเปอร์ลิงก์ทั้งหมดจะถูกบันทึก.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |