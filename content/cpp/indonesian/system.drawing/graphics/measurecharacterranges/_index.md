---
title: MeasureCharacterRanges()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan sebuah array wilayah yang masing-masing membatasi posisi karakter dalam string yang ditentukan.
type: docs
weight: 508
url: /id/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String\&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) metode

Mengembalikan sebuah array wilayah yang masing-masing membatasi posisi karakter dalam string yang ditentukan.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | String yang akan diukur |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Font yang digunakan selama pengukuran string |
| layoutRect | [RectangleF](../../rectanglef/) | Kotak tata letak yang digunakan selama pengukuran string |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\& | Format string, berisi rentang karakter yang akan diukur |

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Region](../../region/)
* Kelas [String](../../../system/string/)
* Kelas [Font](../../font/)
* Kelas [RectangleF](../../rectanglef/)
* Kelas [StringFormat](../../stringformat/)
* Kelas [Graphics](../)
* Ruang Nama [System::Drawing](../../)
* Library [Aspose.Slides](../../../)