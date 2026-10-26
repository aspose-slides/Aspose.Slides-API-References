---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan sebuah Tab ke koleksi.
type: docs
weight: 14
url: /id/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) metode

Menambahkan sebuah [Tab](../../tab/) ke koleksi.

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) posisi. |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) perataan. |

### Nilai Kembali

Tab yang ditambahkan.

## ITabCollection::Add(System::SharedPtr\<ITab\>) metode

Menambahkan sebuah [Tab](../../tab/) ke koleksi.

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | Objek [Tab](../../tab/) yang akan ditambahkan di akhir koleksi. |

### Nilai Kembali

Indeks di mana tab ditambahkan.

## Lihat Juga

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ITab](../../itab/)
* Kelas [ITabCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)