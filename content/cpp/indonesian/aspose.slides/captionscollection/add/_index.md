---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan caption tertutup WebVTT ke akhir koleksi.
type: docs
weight: 27
url: /id/aspose.slides/captionscollection/add/
---
## CaptionsCollection::Add(System::String, System::String) metode

Menambahkan caption tertutup WebVTT ke akhir koleksi.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::String filePath) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Label caption tertutup. |
| filePath | [System::String](../../../system/string/) | Jalur ke file WebVTT. |

### Nilai Kembali

Instansi [ICaptions](../../icaptions/) yang ditambahkan.

## CaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) metode

Menambahkan caption tertutup WebVTT ke akhir koleksi dari aliran.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Label caption tertutup. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Aliran masukan yang berisi data dalam format WebVTT. |

### Nilai Kembali

Instansi [ICaptions](../../icaptions/) yang ditambahkan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ICaptions](../../icaptions/)
* Kelas [String](../../../system/string/)
* Kelas [CaptionsCollection](../)
* Kelas [Stream](../../../system.io/stream/)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)