---
title: VbaProjectFactory
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: COM arabirimi üzerinden VBA projesi oluşturulmasını sağlar
type: docs
url: /tr/com.aspose.slides/vbaprojectfactory/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

COM arayüzü üzerinden VBA projesi oluşturulmasını sağlar
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getInstance()](#getInstance--) | VBA proje fabrikası statik örneği. |
| [createVbaProject()](#createVbaProject--) | Yeni VBA projesi oluşturur. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | OLE konteynerinden VBA projesini okur. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


VBA proje fabrikası statik örneği. Salt okunur [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**Döndürür:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


Yeni VBA projesi oluşturur.

**Döndürür:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Yeni VBA proje
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


OLE konteynerinden VBA projesini okur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | byte[] |  |

**Döndürür:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - VBA projesini okur