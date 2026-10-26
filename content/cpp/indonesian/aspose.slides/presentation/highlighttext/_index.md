---
title: HighlightText()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyorot semua kecocokan teks contoh dengan warna yang ditentukan.
type: docs
weight: 495
url: /id/aspose.slides/presentation/highlighttext/
---
## Presentation::HighlightText(System::String, System::Drawing::Color) metode


Menyorot semua kecocokan teks contoh dengan warna yang ditentukan.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Teks yang akan disorot. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Warna untuk menyorot teks. |
## Catatan



Contoh kode berikut menunjukkan cara menyorot teks dalam presentasi PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// highlighting all separate 'the' occurrences
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Presentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metode


Menyorot semua kecocokan teks contoh dengan warna yang ditentukan.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Teks yang akan disorot. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Warna untuk menyorot teks. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opsi pencarian teks [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objek callback untuk menerima hasil pencarian [IFindResultCallback](../../ifindresultcallback/). |
## Catatan



Contoh kode berikut menunjukkan cara menyorot teks dalam presentasi PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// menyorot semua kemunculan 'the' yang terpisah
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [Color](../../../system.drawing/color/)
* Kelas [Presentation](../)
* Kelas [ITextSearchOptions](../../itextsearchoptions/)
* Kelas [IFindResultCallback](../../ifindresultcallback/)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)