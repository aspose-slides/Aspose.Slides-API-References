---
title: IVbaProject
second_title: Aspose.Slides for Java API Reference
description: Sunum makroları içeren VBA projesini temsil eder.
type: docs
url: /tr/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

Sunum makroları içeren VBA projesini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getName()](#getName--) | VBA projesinin adını döndürür. |
| [getModules()](#getModules--) | VBA projesinde bulunan tüm modüllerin listesini döndürür. |
| [getReferences()](#getReferences--) | VBA projesinde bulunan tüm referansların listesini döndürür. |
| [toBinary()](#toBinary--) | VBA projesinin OLE konteyneri olarak ikili temsilini döndürür. |
| [isPasswordProtected()](#isPasswordProtected--) | VBAProject'in proje özelliklerini görüntülemek için bir parola ile korunup korunmadığını gösterir. |
### getName() {#getName--}
```
public abstract String getName()
```

VBA projesinin adını döndürür. Yalnızca okuma String.

**Returns:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```

VBA projesinde bulunan tüm modüllerin listesini döndürür. Yalnızca okuma [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Returns:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```

VBA projesinde bulunan tüm referansların listesini döndürür. Yalnızca okuma [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Returns:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```

VBA projesinin OLE konteyneri olarak ikili temsilini döndürür. Yalnızca okuma byte[].

**Returns:**
byte[] - VBA projesinin OLE konteyneri olarak ikili temsili
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

VBAProject'in proje özelliklerini görüntülemek için bir parola ile korunup korunmadığını gösterir. Yalnızca okuma boolean.

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

**Returns:**
boolean