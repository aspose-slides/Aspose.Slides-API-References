---
title: IVbaProject
second_title: Aspose.Slides for Java API Reference
description: تمثّل مشروع VBA مع ماكرو العرض.
type: docs
url: /ar/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

تمثّل مشروع VBA مع ماكرو العرض.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getName()](#getName--) | تُرجع اسم VBA project. |
| [getModules()](#getModules--) | تُرجع قائمة جميع الوحدات التي تحتويها VBA project. |
| [getReferences()](#getReferences--) | تُرجع قائمة جميع المراجع التي تحتويها VBA project. |
| [toBinary()](#toBinary--) | تُرجع التمثيل الثنائي لـ VBA project كحاوية OLE. |
| [isPasswordProtected()](#isPasswordProtected--) | تشير إلى ما إذا كان VBAProject محميًا بكلمة مرور لعرض خصائص المشروع. |
### getName() {#getName--}
```
public abstract String getName()
```

تُرجع اسم VBA project. للقراءة فقط String.

**القيمة المرجعة:**  
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```

تُرجع قائمة جميع الوحدات التي تحتويها VBA project. للقراءة فقط [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**القيمة المرجعة:**  
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```

تُرجع قائمة جميع المراجع التي تحتويها VBA project. للقراءة فقط [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**القيمة المرجعة:**  
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```

تُرجع التمثيل الثنائي لـ VBA project كحاوية OLE. للقراءة فقط byte[].

**القيمة المرجعة:**  
byte[] - تمثيل ثنائي لـ VBA project كحاوية OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

تشير إلى ما إذا كان VBAProject محميًا بكلمة مرور لعرض خصائص المشروع. للقراءة فقط boolean.

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