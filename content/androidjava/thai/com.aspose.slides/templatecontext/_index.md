---
title: TemplateContext
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นอินเทอร์เฟซอ็อบเจ็กต์โมเดลสำหรับเครื่องมือเทมเพลต.
type: docs
url: /th/com.aspose.slides/templatecontext/
---
**การสืบทอด:**  
java.lang.Object  
```
public final class TemplateContext<TObject>
```

เป็นอินเทอร์เฟซอ็อบเจ็กต์โมเดลสำหรับเครื่องมือเทมเพลต

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Creates a child template context. |
| [getObject()](#getObject--) | Returns the model object. |
| [getOutput()](#getOutput--) | Returns collection of output elements of the host document. |
| [getLocal()](#getLocal--) | Returns local storage of the current template context. |
| [getGlobal()](#getGlobal--) | Returns global storage of the host document. |

### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```

สร้างบริบทเทมเพลตลูก

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| subModel | TSubModel | อ็อบเจ็กต์โมเดลลูก. |

**ค่าที่ส่งกลับ:**
[TemplateContext](../../com.aspose.slides/templatecontext) - คอนเท็กซ์เทมเพลตใหม่พร้อมโมเดลที่กำหนดและคอลเลคชันผลลัพธ์ของพาเรนท์และที่เก็บข้อมูลทั่วโลก

### getObject() {#getObject--}
```
public final TObject getObject()
```

ส่งคืนอ็อบเจ็กต์โมเดล อ่านอย่างเดียว Object.

**ค่าที่ส่งกลับ:**
TObject

### getOutput() {#getOutput--}
```
public final Output getOutput()
```

ส่งคืนคอลเลคชันขององค์ประกอบผลลัพธ์ของเอกสารโฮสต์ อ่านอย่างเดียว [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**ค่าที่ส่งกลับ:**
[Output](../../com.aspose.slides/output)

### getLocal() {#getLocal--}
```
public final Storage getLocal()
```

ส่งคืนที่เก็บข้อมูลโลคัลของบริบทเทมเพลตปัจจุบัน อ่านอย่างเดียว [Storage](../../com.aspose.slides/storage).

**ค่าที่ส่งกลับ:**
[Storage](../../com.aspose.slides/storage)

### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

ส่งคืนที่เก็บข้อมูลทั่วโลกของเอกสารโฮสต์ อ่านอย่างเดียว [Storage](../../com.aspose.slides/storage).

**ค่าที่ส่งกลับ:**
[Storage](../../com.aspose.slides/storage)