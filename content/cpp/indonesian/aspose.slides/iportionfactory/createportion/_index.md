---
title: CreatePortion()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat bagian teks kosong.
type: docs
weight: 1
url: /id/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() metode

Creates an empty text portion.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```

### Nilai Kembalian

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) metode

Creates a text portion from specified string.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### Nilai Kembalian

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) metode

Creates a portion with the using of a specified portion data.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Portion yang akan digunakan. |

### Nilai Kembalian

[Portion](../../portion/).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IPortion](../../iportion/)
* Kelas [IPortionFactory](../)
* Kelas [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)