---
title: GetTextBoxesContainsText()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan semua bingkai teks pada slide yang ditentukan yang berisi teks yang diberikan.
type: docs
weight: 66
url: /id/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) method

Mengembalikan semua bingkai teks pada slide yang ditentukan yang berisi teks yang diberikan.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Slide yang akan dicari. |
| text | [System::String](../../../system/string/) | Teks yang akan dicari dalam bingkai teks. |
| checkPlaceholderText | **bool** | Menunjukkan apakah akan menyertakan bingkai teks yang kosong, tetapi teks placeholder-nya mengandung teks pencarian. |

### Nilai Kembali

Sebuah array dari objek [ITextFrame](../../../aspose.slides/itextframe/) yang berisi teks yang ditentukan.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ITextFrame](../../../aspose.slides/itextframe/)
* Kelas [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Kelas [String](../../../system/string/)
* Kelas [SlideUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)