---
title: IVbaProjectFactory
second_title: Aspose.Slides for Android عبر مرجع API للغة Java
description: يسمح بإنشاء مشروع VBA عبر واجهة COM
type: docs
url: /ar/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

يسمح بإنشاء مشروع VBA عبر واجهة COM
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | ينشئ مشروع VBA جديد. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | يقرأ مشروع VBA من حاوية OLE. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```


ينشئ مشروع VBA جديد.

**القيمة المرجعة:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - مشروع VBA جديد
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```


يقرأ مشروع VBA من حاوية OLE.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | byte[] | Ole data byte[] |

**القيمة المرجعة:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - مشروع VBA مقروء