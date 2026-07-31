---
title: GetFontEmbeddingLevel()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan tingkat penyematan font dari array byte yang diberikan dan nama font.
type: docs
weight: 144
url: /id/aspose.slides/ifontsmanager/getfontembeddinglevel/
---
## IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) metode

Menentukan tingkat penyematan font dari array byte yang diberikan dan nama font.

```cpp
virtual EmbeddingLevel Aspose::Slides::IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte yang berisi data font. |
| fontName | [System::String](../../../system/string/) | Nama font. |

### Nilai Kembalian

Tingkat penyematan font yang ditentukan.

## Catatan

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Determine the embedding level of the font
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## Lihat Juga

* Enum [EmbeddingLevel](../../embeddinglevel/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [IFontsManager](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)