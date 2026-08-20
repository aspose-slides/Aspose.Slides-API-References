---
title: VbaProject
second_title: مرجع API Aspose.Slides للـ Java
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

| المُنشئ | الوصف |
| --- | --- |
| [VbaProject()](#VbaProject--) | This constructor creates new VBA project from scratch. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | This constructor loads VBA project from binary representation of OLE container. |
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getName()](#getName--) | Returns the name of the VBA project. |
| [getModules()](#getModules--) | Returns the list of all modules that are contained in the VBA project. |
| [getReferences()](#getReferences--) | Returns the list of all references that are contained in the VBA project. |
| [toBinary()](#toBinary--) | Returns the binary representation of the VBA project as OLE container |
| [isPasswordProtected()](#isPasswordProtected--) | Indicates whether the VBAProject is protected by a password to view project properties. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


يقوم هذا المُنشئ بإنشاء مشروع VBA جديد من الصفر. سيتم إنشاء المشروع في 1252 Windows Latin 1 (ANSI) codepage

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```


This constructor loads VBA project from binary representation of OLE container.

**Parameters:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```


Returns the name of the VBA project. Read-only String.

**الإرجاع:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```


Returns the list of all modules that are contained in the VBA project. Read-only [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**الإرجاع:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


Returns the list of all references that are contained in the VBA project. Read-only [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**الإرجاع:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


Returns the binary representation of the VBA project as OLE container

**الإرجاع:**
byte[] - Binary representation of the VBA project as OLE container
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Indicates whether the VBAProject is protected by a password to view project properties. Read-only  boolean .

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


**الإرجاع:**
boolean