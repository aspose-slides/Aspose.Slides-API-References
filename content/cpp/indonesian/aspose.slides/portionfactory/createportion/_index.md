---
title: CreatePortion()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat bagian teks kosong.
type: docs
weight: 1
url: /id/aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() metode

Membuat bagian teks kosong.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```

### Nilai Kembalian

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) metode

Membuat bagian teks dari string yang ditentukan.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### Nilai Kembalian

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) metode

Membuat bagian dengan menggunakan data bagian yang ditentukan.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Bagian yang akan digunakan. |

### Nilai Kembalian

[Portion](../../portion/).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IPortion](../../iportion/)
* Kelas [PortionFactory](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)