---
title: Hyperlink()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance dari hyperlink.
type: docs
weight: 339
url: /id/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) konstruktor

Membuat sebuah instance dari hyperlink.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) konstruktor

Membuat sebuah instance dari hyperlink yang mengarah ke slide tertentu. Catatan: hyperlink yang dibuat harus ditetapkan ke objek dari presentasi yang sama, jika tidak tautan akan disimpan sebagai NoAction.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Slide target. |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) konstruktor

Membuat sebuah instance hyperlink dengan menggunakan hyperlink lain sebagai sumber, mengganti properti sekunder.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | Hyperlink sumber |
| targetFrame | [System::String](../../../system/string/) | Bingkai target |
| tooltip | [System::String](../../../system/string/) | Teks tooltip |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Hyperlink](../)
* Class [ISlide](../../islide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)