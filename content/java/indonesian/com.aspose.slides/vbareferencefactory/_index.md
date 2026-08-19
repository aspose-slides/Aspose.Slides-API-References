---
title: VbaReferenceFactory
second_title: Aspose.Slides untuk Referensi API Java
description: Memungkinkan membuat referensi proyek VBA melalui antarmuka COM
type: docs
url: /id/com.aspose.slides/vbareferencefactory/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

Memungkinkan membuat referensi proyek VBA melalui antarmuka COM
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getInstance()](#getInstance--) | Fabrik referensi proyek VBA statis. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Membuat referensi perpustakaan tipe OLE Automation baru. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


Fabrik referensi proyek VBA statis. Hanya-baca [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Mengembalikan:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Membuat referensi perpustakaan tipe OLE Automation baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Mengembalikan:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Referensi perpustakaan tipe OLE Automation baru