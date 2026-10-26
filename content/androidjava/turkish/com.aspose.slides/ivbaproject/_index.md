---
title: IVbaProject
second_title: Aspose.Slides for Android via Java API Referansı
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
| [toBinary()](#toBinary--) | VBA projesinin OLE konteyneri olarak ikili temsili döndürür. |
| [isPasswordProtected()](#isPasswordProtected--) | VBAProject'in proje özelliklerini görüntülemek için bir parola ile korunduğunu gösterir. |
### getName() {#getName--}
```
public abstract String getName()
```


VBA projesinin adını döndürür. Yalnızca okunur String.

**Döndürür:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```


VBA projesinde bulunan tüm modüllerin listesini döndürür. Yalnızca okunur [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Döndürür:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```


VBA projesinde bulunan tüm referansların listesini döndürür. Yalnızca okunur [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Döndürür:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```


VBA projesinin OLE konteyneri olarak ikili temsili döndürür. Yalnızca okunur byte[].

**Döndürür:**
byte[] - VBA projesinin OLE konteyneri olarak ikili temsili
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


VBAProject'in proje özelliklerini görüntülemek için bir parola ile korunduğunu gösterir. Yalnızca okunur boolean.

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


**Döndürür:**
boolean