---
title: VbaReferenceFactory
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: อนุญาตให้สร้างอ้างอิงโครงการ VBA ผ่านอินเทอร์เฟซ COM
type: docs
url: /th/com.aspose.slides/vbareferencefactory/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการนำมาใช้งานทั้งหมด:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

อนุญาตให้สร้างอ้างอิงโครงการ VBA ผ่านอินเทอร์เฟซ COM
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getInstance()](#getInstance--) | VBA project references factory static instance. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Creates new OLE Automation type library reference. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


VBA project references factory static instance. อ่านอย่างเดียว [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**ส่งคืน:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Creates new OLE Automation type library reference.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**ส่งคืน:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - อ้างอิงไลบรารีประเภท OLE Automation ตัวใหม่