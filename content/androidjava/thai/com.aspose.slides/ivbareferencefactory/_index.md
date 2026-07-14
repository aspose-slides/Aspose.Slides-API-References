---
title: IVbaReferenceFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create VBA project references via COM interface
type: docs
url: /th/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

อนุญาตให้สร้างการอ้างอิงโครงการ VBA ผ่านอินเทอร์เฟซ COM

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | สร้างการอ้างอิงไลบรารีประเภท OLE Automation ใหม่. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

สร้างการอ้างอิงไลบรารีประเภท OLE Automation ใหม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของการอ้างอิงโครงการ VBA String |
| libid | java.lang.String | ตัวระบุของไลบรารีประเภท Automation String |

**ผลลัพธ์:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - การอ้างอิงไลบรารีประเภท OLE Automation ใหม่ [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)