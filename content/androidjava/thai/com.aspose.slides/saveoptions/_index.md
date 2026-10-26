---
title: SaveOptions
second_title: Aspose.Slides สำหรับ Android ผ่านเอกสารอ้างอิง API ของ Java
description: คลาสเชิงนามธรรมที่มีตัวเลือกควบคุมวิธีการบันทึกงานนำเสนอ
type: docs
url: /th/com.aspose.slides/saveoptions/
---
**Inheritance:**  
สืบทอด

java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

คลาสเชิงนามธรรมที่มีตัวเลือกควบคุมวิธีการบันทึกงานนำเสนอ
## Constructors

| Constructor | Description |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | ส่งคืนหรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อไปหรือจะถูกยกเลิก |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | ส่งคืนหรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อไปหรือจะถูกยกเลิก |
| [getProgressCallback()](#getProgressCallback--) | แทนอ็อบเจ็กต์ callback สำหรับอัปเดตความคืบหน้าการบันทึกเป็นเปอร์เซ็นต์ |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | แทนอ็อบเจ็กต์ callback สำหรับอัปเดตความคืบหน้าการบันทึกเป็นเปอร์เซ็นต์ |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | ส่งคืนหรือกำหนดแบบอักษรที่ใช้เมื่อไม่พบแบบอักษรต้นฉบับ |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | ส่งคืนหรือกำหนดแบบอักษรที่ใช้เมื่อไม่พบแบบอักษรต้นฉบับ |
| [getGradientStyle()](#getGradientStyle--) | ส่งคืนหรือกำหนดสไตล์ภาพกราดเซ็นต์ของการไล่ระดับสี |
| [setGradientStyle(int value)](#setGradientStyle-int-) | ส่งคืนหรือกำหนดสไตล์ภาพกราดเซ็นต์ของการไล่ระดับสี |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | ระบุต้องข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่ขณะบันทึกงานนำเสนอ |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | ระบุต้องข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่ขณะบันทึกงานนำเสนอ |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


ส่งคืนหรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อไปหรือจะถูกยกเลิก อ่าน/เขียน [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**คืนค่า:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


ส่งคืนหรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อไปหรือจะถูกยกเลิก อ่าน/เขียน [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```


แทนอ็อบเจ็กต์ callback สำหรับอัปเดตความคืบหน้าการบันทึกเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**คืนค่า:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```


แทนอ็อบเจ็กต์ callback สำหรับอัปเดตความคืบหน้าการบันทึกเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


ส่งคืนหรือกำหนดแบบอักษรที่ใช้เมื่อไม่พบแบบอักษรต้นฉบับ อ่าน-เขียน String.

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
public final void setDefaultRegularFont(String value)
```


ส่งคืนหรือกำหนดแบบอักษรที่ใช้เมื่อไม่พบแบบอักษรต้นฉบับ อ่าน-เขียน String.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public final int getGradientStyle()
```


ส่งคืนหรือกำหนดสไตล์ภาพกราดเซ็นต์ของการไล่ระดับสี อ่าน/เขียน [GradientStyle](../../com.aspose.slides/gradientstyle).

**คืนค่า:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```


ส่งคืนหรือกำหนดสไตล์ภาพกราดเซ็นต์ของการไล่ระดับสี อ่าน/เขียน [GradientStyle](../../com.aspose.slides/gradientstyle).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```


ระบุต้องข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่ขณะบันทึกงานนำเสนอ อ่าน/เขียน boolean ค่าเริ่มต้นคือ false.

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

เมื่อคุณสมบัตินี้ตั้งค่าเป็น true ไฮเปอร์ลิงก์ที่มีการเรียก JavaScript จะถูกละเลยขณะบันทึก

เมื่อคุณสมบัตินี้ตั้งค่าเป็น false ไฮเปอร์ลิงก์ทั้งหมดจะถูกบันทึก

**คืนค่า:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```


ระบุต้องข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่ขณะบันทึกงานนำเสนอ อ่าน/เขียน boolean ค่าเริ่มต้นคือ false.

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

เมื่อคุณสมบัตินี้ตั้งค่าเป็น true ไฮเปอร์ลิงก์ที่มีการเรียก JavaScript จะถูกละเลยขณะบันทึก

เมื่อคุณสมบัตินี้ตั้งค่าเป็น false ไฮเปอร์ลิงก์ทั้งหมดจะถูกบันทึก

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |