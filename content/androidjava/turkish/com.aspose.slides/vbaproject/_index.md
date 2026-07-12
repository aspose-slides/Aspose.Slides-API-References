---
title: VbaProject
second_title: Aspose.Slides for Android için Java API Referansı
description: Sunum makroları içeren VBA projesini temsil eder.
type: docs
url: /tr/com.aspose.slides/vbaproject/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

Sunum makroları içeren VBA projesini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [VbaProject()](#VbaProject--) | Bu yapıcı, yeni bir VBA projesini sıfırdan oluşturur. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | Bu yapıcı, OLE konteynerinin ikili temsili üzerinden VBA projesini yükler. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getName()](#getName--) | VBA projesinin adını döndürür. |
| [getModules()](#getModules--) | VBA projesinde bulunan tüm modüllerin listesini döndürür. |
| [getReferences()](#getReferences--) | VBA projesinde bulunan tüm referansların listesini döndürür. |
| [toBinary()](#toBinary--) | VBA projesinin OLE konteyneri olarak ikili temsili döndürür |
| [isPasswordProtected()](#isPasswordProtected--) | VBAProject'in proje özelliklerini görüntülemek için bir şifreyle korunduğunu gösterir. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```

Bu yapıcı, yeni bir VBA projesini sıfırdan oluşturur. Proje 1252 Windows Latin 1 (ANSI) kod sayfasında oluşturulacaktır

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```

Bu yapıcı, OLE konteynerinin ikili temsili üzerinden VBA projesini yükler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```

VBA projesinin adını döndürür. Salt okunur String.

**Döndürür:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```

VBA projesinde bulunan tüm modüllerin listesini döndürür. Salt okunur [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Döndürür:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```

VBA projesinde bulunan tüm referansların listesini döndürür. Salt okunur [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Döndürür:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```

VBA projesinin OLE konteyneri olarak ikili temsili döndürür

**Döndürür:**
byte[] - VBA projesinin OLE konteyneri olarak ikili temsili
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

VBAProject'in proje özelliklerini görüntülemek için bir şifreyle korunduğunu gösterir. Salt okunur boolean .

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