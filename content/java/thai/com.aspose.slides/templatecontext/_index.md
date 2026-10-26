---
title: TemplateContext
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงอินเทอร์เฟซอ็อบเจกต์โมเดลสำหรับเครื่องมือเทมเพลต
type: docs
url: /th/com.aspose.slides/templatecontext/
---
**การสืบทอด:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

แสดงถึงอินเทอร์เฟซอ็อบเจกต์โมเดลสำหรับเครื่องมือเทมเพลต
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | สร้างบริบทเทมเพลตลูก |
| [getObject()](#getObject--) | คืนค่าอ็อบเจกต์โมเดล |
| [getOutput()](#getOutput--) | คืนคอลเลกชันขององค์ประกอบผลลัพธ์ของเอกสารโฮสต์ |
| [getLocal()](#getLocal--) | คืนค่าที่เก็บข้อมูลท้องถิ่นของบริบทเทมเพลตปัจจุบัน |
| [getGlobal()](#getGlobal--) | คืนค่าที่เก็บข้อมูลระดับทั่วโลกของเอกสารโฮสต์ |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```


สร้างบริบทเทมเพลตลูก

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| subModel | TSubModel | อ็อบเจกต์โมเดลลูก |

**คืนค่า:**
[TemplateContext](../../com.aspose.slides/templatecontext) - บริบทเทมเพลตใหม่ที่มีโมเดลที่กำหนดและคอลเลกชันผลลัพธ์ของผู้ปกครองและที่เก็บข้อมูลระดับทั่วโลก
### getObject() {#getObject--}
```
public final TObject getObject()
```


ส่งคืนอ็อบเจกต์โมเดล อ่านอย่างเดียว Object.

**คืนค่า:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


คืนคอลเลกชันขององค์ประกอบผลลัพธ์ของเอกสารโฮสต์ อ่านอย่างเดียว [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**คืนค่า:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```


คืนค่าที่เก็บข้อมูลท้องถิ่นของบริบทเทมเพลตปัจจุบัน อ่านอย่างเดียว [Storage](../../com.aspose.slides/storage).

**คืนค่า:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


คืนค่าที่เก็บข้อมูลระดับทั่วโลกของเอกสารโฮสต์ อ่านอย่างเดียว [Storage](../../com.aspose.slides/storage).

**คืนค่า:**
[Storage](../../com.aspose.slides/storage)