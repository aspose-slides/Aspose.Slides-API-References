---
title: IVbaProjectFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create VBA project via COM interface
type: docs
url: /tr/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

COM arabirimi üzerinden VBA projesi oluşturmayı sağlar
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Yeni VBA projesi oluşturur. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | OLE konteynerinden VBA projesini okur. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```


Yeni VBA projesi oluşturur.

**Döndürür:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Yeni VBA proje
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```


OLE konteynerinden VBA projesini okur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | byte[] | Ole veri byte[] |

**Döndürür:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Okunan VBA proje