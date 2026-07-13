---
title: VbaProjectFactory
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mengizinkan pembuatan proyek VBA melalui antarmuka COM
type: docs
url: /id/com.aspose.slides/vbaprojectfactory/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

Mengizinkan pembuatan proyek VBA melalui antarmuka COM
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getInstance()](#getInstance--) | Instansi statis pabrik proyek VBA. |
| [createVbaProject()](#createVbaProject--) | Membuat proyek VBA baru. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Membaca proyek VBA dari kontainer OLE. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


Instansi statis pabrik proyek VBA. Baca-saja [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**Mengembalikan:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


Membuat proyek VBA baru.

**Mengembalikan:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Proyek VBA baru
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


Membaca proyek VBA dari kontainer OLE.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] |  |

**Mengembalikan:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Proyek VBA yang dibaca