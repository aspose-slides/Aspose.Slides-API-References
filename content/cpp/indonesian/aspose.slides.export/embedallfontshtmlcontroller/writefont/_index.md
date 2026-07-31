---
title: WriteFont()
second_title: Referensi API Aspose.Slides untuk C++
description: Menulis data sebagai base64 ke dalam dokumen HTML itu sendiri
type: docs
weight: 105
url: /id/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) metode

Menulis data sebagai base64 ke dalam dokumen HTML itu sendiri

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Generator HTML |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Font yang akan diserialkan |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Font yang disubstitusi (jika substitusi font terjadi), null sebaliknya |
| fontStyle | [System::String](../../../system/string/) | Gaya font |
| fontWeight | [System::String](../../../system/string/) | Berat font |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data font |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [IHtmlGenerator](../../ihtmlgenerator/)
* Kelas [IFontData](../../../aspose.slides/ifontdata/)
* Kelas [String](../../../system/string/)
* Kelas [EmbedAllFontsHtmlController](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)