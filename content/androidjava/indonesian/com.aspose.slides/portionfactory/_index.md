---
title: PortionFactory
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Memungkinkan membuat bagian uji
type: docs
url: /id/com.aspose.slides/portionfactory/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

Memungkinkan membuat bagian uji

--------------------

Untuk kompatibilitas COM
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createPortion()](#createPortion--) | Membuat bagian teks kosong. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Membuat bagian teks dari string yang ditentukan. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Membuat bagian dengan menggunakan data bagian yang ditentukan. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


Membuat bagian teks kosong.

**Mengembalikan:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


Membuat bagian teks dari string yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | java.lang.String | String. |

**Mengembalikan:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```


Membuat bagian dengan menggunakan data bagian yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Sebuah bagian untuk digunakan. |

**Mengembalikan:**
[IPortion](../../com.aspose.slides/iportion) - Portion.