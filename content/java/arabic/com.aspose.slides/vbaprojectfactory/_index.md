---
title: VbaProjectFactory
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يسمح بإنشاء مشروع VBA عبر واجهة COM
type: docs
url: /ar/com.aspose.slides/vbaprojectfactory/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُطبقة:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

يسمح بإنشاء مشروع VBA عبر واجهة COM
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getInstance()](#getInstance--) | مثيل ثابت لمصنع مشروع VBA. |
| [createVbaProject()](#createVbaProject--) | ينشئ مشروع VBA جديد. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | يقرا مشروع VBA من حاوية OLE. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


مثيل ثابت لمصنع مشروع VBA. قراءة فقط [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**الإرجاع:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


ينشئ مشروع VBA جديد.

**الإرجاع:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - مشروع VBA جديد
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


يقرا مشروع VBA من حاوية OLE.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | byte[] |  |

**الإرجاع:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - قراءة مشروع VBA