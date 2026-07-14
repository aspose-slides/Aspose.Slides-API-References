---
title: VbaProject
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة Java
description: يمثل مشروع VBA مع ماكروهات العرض.
type: docs
url: /ar/com.aspose.slides/vbaproject/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

يمثل مشروع VBA مع ماكروهات العرض.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [VbaProject()](#VbaProject--) | هذا المنشئ ينشئ مشروع VBA جديد من الصفر. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | هذا المنشئ يحمل مشروع VBA من التمثيل الثنائي لحاوية OLE. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getName()](#getName--) | يعيد اسم مشروع VBA. |
| [getModules()](#getModules--) | يعيد قائمة بجميع الوحدات الموجودة في مشروع VBA. |
| [getReferences()](#getReferences--) | يعيد قائمة بجميع المراجع الموجودة في مشروع VBA. |
| [toBinary()](#toBinary--) | يعيد التمثيل الثنائي لمشروع VBA كحاوية OLE |
| [isPasswordProtected()](#isPasswordProtected--) | يشير إلى ما إذا كان VBAProject محمياً بكلمة مرور لعرض خصائص المشروع. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


هذا المنشئ ينشئ مشروع VBA جديد من الصفر. سيتم إنشاء المشروع في 1252 Windows Latin 1 (ANSI) codepage

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```


هذا المنشئ يحمل مشروع VBA من التمثيل الثنائي لحاوية OLE.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```


يعيد اسم مشروع VBA. String للقراءة فقط.

**القيمة المرجعة:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```


يعيد قائمة بجميع الوحدات الموجودة في مشروع VBA. [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection) للقراءة فقط.

**القيمة المرجعة:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


يعيد قائمة بجميع المراجع الموجودة في مشروع VBA. [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection) للقراءة فقط.

**القيمة المرجعة:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


يعيد التمثيل الثنائي لمشروع VBA كحاوية OLE

**القيمة المرجعة:**
byte[] - تمثيل ثنائي لمشروع VBA كحاوية OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


يشير إلى ما إذا كان VBAProject محامياً بكلمة مرور لعرض خصائص المشروع. boolean للقراءة فقط .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptm");
>  try {
>      if (presentation.getVbaProject().isPasswordProtected())
>          System.out.println("The VBAProject '" + presentation.getVbaProject().getName() +
>              "' is protected by password to view project properties.");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**القيمة المرجعة:**
boolean