---
title: HighlightText()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyorot semua kecocokan teks contoh dengan warna yang ditentukan.
type: docs
weight: 105
url: /id/aspose.slides/itextframe/highlighttext/
---
## ITextFrame::HighlightText(System::String, System::Drawing::Color) metode

Menyorot semua kecocokan teks contoh dengan warna yang ditentukan.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Teks yang akan disorot. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Warna untuk menyorot teks. |

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) metode

Menyorot semua kecocokan teks contoh dengan warna yang ditentukan.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Teks yang akan disorot. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Warna untuk menyorot teks. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Opsi penyorotan. |

Tidak direkomendasikan
:   Gunakan HighlightText(string text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) metode sebagai gantinya. Metode akan dihapus setelah rilis versi 24.10.

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metode

Menyorot semua kecocokan teks contoh dengan warna yang ditentukan.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Teks yang akan disorot. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Warna untuk menyorot teks. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opsi pencarian teks [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objek callback untuk menerima hasil pencarian [IFindResultCallback](../../ifindresultcallback/). |
## Catatan



Contoh kode berikut menunjukkan cara menyorot teks dalam sebuah [TextFrame](../../textframe/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// menyorot semua kata 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// menyorot semua kemunculan terpisah 'the'
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [Color](../../../system.drawing/color/)
* Kelas [ITextFrame](../)
* Kelas [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Kelas [ITextSearchOptions](../../itextsearchoptions/)
* Kelas [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)