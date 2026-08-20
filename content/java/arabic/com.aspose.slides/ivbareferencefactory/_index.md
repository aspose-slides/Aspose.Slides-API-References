---
title: IVbaReferenceFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create VBA project references via COM interface
type: docs
url: /ar/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

يسمح بإنشاء مراجع مشروع VBA عبر واجهة COM.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | ينشئ إشارة جديدة إلى مكتبة نوع OLE Automation. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


ينشئ إشارة جديدة إلى مكتبة نوع OLE Automation.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم إشارة مشروع VBA من نوع String |
| libid | java.lang.String | معرّف لمكتبة نوع Automation من نوع String |

**القيمة المرجعة:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - إشارة جديدة إلى مكتبة نوع OLE Automation [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)