---
title: VbaProjectFactory
second_title: Aspose.Slides لأندرويد عبر مرجع API جافا
description: يسمح بإنشاء مشروع VBA عبر واجهة COM
type: docs
url: /ar/com.aspose.slides/vbaprojectfactory/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

يسمح بإنشاء مشروع VBA عبر واجهة COM
## المُنشئات

| المنشئ | الوصف |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getInstance()](#getInstance--) | مثيل ثابت لمصنع مشروع VBA. |
| [createVbaProject()](#createVbaProject--) | ينشئ مشروع VBA جديد. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | يقرأ مشروع VBA من حاوية OLE. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


مثيل ثابت لمصنع مشروع VBA. للقراءة فقط [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

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


يقرأ مشروع VBA من حاوية OLE.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | byte[] |  |

**الإرجاع:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - مشروع VBA مقروء