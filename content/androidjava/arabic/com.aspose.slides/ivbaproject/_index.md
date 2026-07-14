---
title: IVbaProject
second_title: Aspose.Slides for Android via Java API Reference
description: Represents VBA project with presentation macros.
type: docs
url: /ar/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

يمثل مشروع VBA مع وحدات ماكرو للعرض.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getName()](#getName--) | إرجاع اسم مشروع VBA. |
| [getModules()](#getModules--) | إرجاع قائمة بجميع الوحدات الموجودة في مشروع VBA. |
| [getReferences()](#getReferences--) | إرجاع قائمة بجميع المراجع الموجودة في مشروع VBA. |
| [toBinary()](#toBinary--) | إرجاع التمثيل الثنائي لمشروع VBA كحاوية OLE. |
| [isPasswordProtected()](#isPasswordProtected--) | الإشارة إلى ما إذا كان VBAProject محميًا بكلمة مرور لعرض خصائص المشروع. |
### getName() {#getName--}
```
public abstract String getName()
```


إرجاع اسم مشروع VBA. للقراءة فقط String.

**إرجاع:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```


إرجاع قائمة بجميع الوحدات الموجودة في مشروع VBA. للقراءة فقط [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**إرجاع:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```


إرجاع قائمة بجميع المراجع الموجودة في مشروع VBA. للقراءة فقط [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**إرجاع:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```


إرجاع التمثيل الثنائي لمشروع VBA كحاوية OLE. للقراءة فقط byte[].

**إرجاع:**
byte[] - Binary representation of the VBA project as OLE container
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


الإشارة إلى ما إذا كان VBAProject محميًا بكلمة مرور لعرض خصائص المشروع. للقراءة فقط boolean.

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

**إرجاع:**
boolean