---
title: WebDocument
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงรูปแบบการเปลี่ยนแปลงของงานนำเสนอสำหรับการบันทึกเป็นรูปแบบเว็บ.
type: docs
url: /th/com.aspose.slides/webdocument/
---
**การสืบทอด:**
java.lang.Object
```
public class WebDocument
```

แสดงรูปแบบการเปลี่ยนแปลงของงานนำเสนอสำหรับการบันทึกเป็นรูปแบบเว็บ.
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) ตัวสร้าง. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [save()](#save--) | บันทึกผลลัพธ์ของเอกสาร. |
| [getInput()](#getInput--) | คืนคอลเลกชันขององค์ประกอบอินพุต (เทมเพลต) ของเอกสาร. |
| [getOutput()](#getOutput--) | คืนคอลเลกชันขององค์ประกอบเอาต์พุตของเอกสาร. |
| [getGlobal()](#getGlobal--) | คืนที่เก็บข้อมูลทั่วโลกของเอกสาร. |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```


[WebDocument](../../com.aspose.slides/webdocument) ตัวสร้าง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | ตัวเลือกที่ตั้งค่าสำหรับเอกสาร. |

### save() {#save--}
```
public final void save()
```


บันทึกผลลัพธ์ของเอกสาร.

### getInput() {#getInput--}
```
public final Input getInput()
```


คืนคอลเลกชันขององค์ประกอบอินพุต (เทมเพลต) ของเอกสาร. อ่านอย่างเดียว [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**คืนค่า:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


คืนคอลเลกชันขององค์ประกอบเอาต์พุตของเอกสาร. อ่านอย่างเดียว [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // ใส่คุณสมบัติ "slideMargin" เพื่อใช้จากเทมเพลต
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... ตั้งค่าตัวเลือกอื่นของเอกสารแล้วบันทึกเอกสาร
>   document.save();
> ```


**คืนค่า:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


คืนที่เก็บข้อมูลทั่วโลกของเอกสาร. อ่านอย่างเดียว [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // ใส่คุณสมบัติ "slideMargin" เพื่อใช้จากเทมเพลต
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... ตั้งค่าตัวเลือกอื่นของเอกสารแล้วบันทึกเอกสาร
>   document.save();
> ```


**คืนค่า:**
[Storage](../../com.aspose.slides/storage)