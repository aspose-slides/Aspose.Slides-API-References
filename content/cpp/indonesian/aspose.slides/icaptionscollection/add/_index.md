--- 
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan caption tertutup WebVTT ke akhir koleksi.
type: docs
weight: 27
url: /id/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) method


Menambahkan caption tertutup WebVTT ke akhir koleksi.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Label untuk caption tertutup. |
| filePath | [System::String](../../../system/string/) | Jalur ke file WebVTT. |

### Nilai Kembalian

Instance [ICaptions](../../icaptions/) yang ditambahkan.

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) method


Menambahkan caption tertutup WebVTT ke akhir koleksi dari aliran.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Label untuk caption tertutup. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Aliran masukan yang berisi data dalam format WebVTT. |

### Nilai Kembalian

Instance [ICaptions](../../icaptions/) yang ditambahkan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ICaptions](../../icaptions/)
* Kelas [String](../../../system/string/)
* Kelas [ICaptionsCollection](../)
* Kelas [Stream](../../../system.io/stream/)
* Ruang nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)