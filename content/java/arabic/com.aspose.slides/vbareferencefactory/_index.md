---
title: VbaReferenceFactory
second_title: Aspose.Slides لـ Java مرجع API
description: يسمح بإنشاء مراجع مشروع VBA عبر واجهة COM
type: docs
url: /ar/com.aspose.slides/vbareferencefactory/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

يسمح بإنشاء مراجع مشروع VBA عبر واجهة COM
## البناة

| المُنشئ | الوصف |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getInstance()](#getInstance--) | مثلة ثابتة لمصنع مراجع مشروع VBA. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | ينشئ مرجع جديد لمكتبة نوع OLE Automation. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


مثلة ثابتة لمصنع مراجع مشروع VBA. للقـراءة فقط [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**القيمة المرجعة:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


ينشئ مرجعًا جديدًا لمكتبة نوع OLE Automation.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**القيمة المرجعة:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - مرجع جديد لمكتبة نوع OLE Automation