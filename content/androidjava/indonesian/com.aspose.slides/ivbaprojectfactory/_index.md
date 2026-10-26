---
title: IVbaProjectFactory
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Memungkinkan membuat proyek VBA melalui antarmuka COM
type: docs
url: /id/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

Memungkinkan membuat proyek VBA melalui antarmuka COM
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Membuat proyek VBA baru. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Membaca proyek VBA dari kontainer OLE. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```


Membuat proyek VBA baru.

**Mengembalikan:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Proyek VBA baru
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```


Membaca proyek VBA dari kontainer OLE.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] | Data Ole byte[] |

**Mengembalikan:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Proyek VBA yang dibaca