---
title: VbaReferenceFactory
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يسمح بإنشاء مراجع مشروع VBA عبر واجهة COM
type: docs
url: /ar/com.aspose.slides/vbareferencefactory/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)  
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

يسمح بإنشاء مراجع مشروع VBA عبر واجهة COM  
## المنشئات

| المنشط | الوصف |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getInstance()](#getInstance--) | مثيل ثابت لمصنع مراجع مشروع VBA. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | ينشئ مرجع مكتبة نوع OLE Automation جديد. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```

### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```

مثيل ثابت لمصنع مراجع مشروع VBA. للقراءة فقط [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**الإرجاع:**  
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

ينشئ مرجع مكتبة نوع OLE Automation جديد.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**الإرجاع:**  
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - إشارة جديدة لمكتبة نوع OLE Automation  