---
title: VbaReferenceFactory
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: อนุญาตให้สร้างการอ้างอิงโครงการ VBA ผ่านอินเทอร์เฟซ COM
type: docs
url: /th/com.aspose.slides/vbareferencefactory/
---
**การสืบทอด:**  
java.lang.Object

**ทุกอินเทอร์เฟซที่ทำการใช้งาน:**  
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

อนุญาตให้สร้างการอ้างอิงโครงการ VBA ผ่านอินเทอร์เฟซ COM

## ตัวสร้าง

| Constructor | Description |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |

## เมธอด

| Method | Description |
| --- | --- |
| [getInstance()](#getInstance--) | อินสแตนซ์สถิตของโรงงานการอ้างอิงโครงการ VBA. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | สร้างการอ้างอิงไลบรารีประเภท OLE Automation ใหม่. |

### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```

### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```

อินสแตนซ์สถิตของโรงงานการอ้างอิงโครงการ VBA. อ่านอย่างเดียว [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**ส่งคืน:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

สร้างการอ้างอิงไลบรารีประเภท OLE Automation ใหม่.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**ส่งคืน:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - การอ้างอิงไลบรารีประเภท OLE Automation ใหม่