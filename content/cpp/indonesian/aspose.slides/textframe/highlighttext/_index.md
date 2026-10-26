---
title: HighlightText()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyorot semua kecocokan teks contoh dengan warna yang ditentukan.
type: docs
weight: 131
url: /id/aspose.slides/textframe/highlighttext/
---
## TextFrame::HighlightText(System::String, System::Drawing::Color) metode


Menyorot semua kecocokan teks contoh dengan warna yang ditentukan.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Contoh teks yang akan disorot. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Warna untuk menyorot teks. |

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) metode


Menyorot semua kecocokan teks contoh dengan warna yang ditentukan.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Teks yang akan disorot. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Warna untuk menyorot teks. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Opsi penyorotan. |
## Catatan


Usang
:   Gunakan metode HighlightText(string text, Color highlightColor, ITextSearchOptions options) sebagai gantinya. Metode ini akan dihapus setelah rilis versi 24.10.


Kode contoh berikut menunjukkan cara menyorot teks dalam [TextFrame](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"title", System::Drawing::Color::get_LightBlue());

auto textHighlightOptions = System::MakeObject<TextHighlightingOptions>();
textHighlightOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"to", System::Drawing::Color::get_Violet(), textHighlightOptions);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metode


Menyorot semua kecocokan teks contoh dengan warna yang ditentukan.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Teks yang akan disorot. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Warna untuk menyorot teks. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opsi pencarian teks [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objek callback untuk menerima hasil pencarian [IFindResultCallback](../../ifindresultcallback/). |
## Catatan



Contoh kode berikut menunjukkan cara menyorot teks dalam [TextFrame](../). 
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
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [TextFrame](../)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)