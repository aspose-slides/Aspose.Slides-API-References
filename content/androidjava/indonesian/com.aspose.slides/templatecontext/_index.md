---
title: TemplateContext
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili antarmuka objek model untuk mesin templat.
type: docs
url: /id/com.aspose.slides/templatecontext/
---
**Pewarisan:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Mewakili antarmuka objek model untuk mesin templat.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Membuat konteks templat anak. |
| [getObject()](#getObject--) | Mengembalikan objek model. |
| [getOutput()](#getOutput--) | Mengembalikan koleksi elemen output dari dokumen host. |
| [getLocal()](#getLocal--) | Mengembalikan penyimpanan lokal dari konteks templat saat ini. |
| [getGlobal()](#getGlobal--) | Mengembalikan penyimpanan global dari dokumen host. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```


Membuat konteks templat anak.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| subModel | TSubModel | Objek model anak. |

**Mengembalikan:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Konteks templat baru dengan model yang diberikan serta koleksi output orang tua dan penyimpanan global.
### getObject() {#getObject--}
```
public final TObject getObject()
```


Mengembalikan objek model. Hanya-baca Object.

**Mengembalikan:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Mengembalikan koleksi elemen output dari dokumen host. Hanya-baca [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Mengembalikan:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```


Mengembalikan penyimpanan lokal dari konteks templat saat ini. Hanya-baca [Storage](../../com.aspose.slides/storage).

**Mengembalikan:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Mengembalikan penyimpanan global dari dokumen host. Hanya-baca [Storage](../../com.aspose.slides/storage).

**Mengembalikan:**
[Storage](../../com.aspose.slides/storage)