---
title: IVbaReferenceFactory
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: يسمح بإنشاء مراجع مشروع VBA عبر واجهة COM
type: docs
url: /ar/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

يسمح بإنشاء مراجع مشروع VBA عبر واجهة COM
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | إنشاء إشارة مكتبة نوع OLE Automation جديدة. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

إنشاء إشارة مكتبة نوع OLE Automation جديدة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم مرجع مشروع VBA من النوع String |
| libid | java.lang.String | معرّف مكتبة نوع Automation من النوع String |

**القيمة المرجعة:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - إشارة مكتبة نوع OLE Automation جديدة [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)