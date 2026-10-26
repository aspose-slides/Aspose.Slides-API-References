---
title: HighlightRegex()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyorot semua kecocokan dari ekspresi reguler dengan warna yang ditentukan.
type: docs
weight: 157
url: /id/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) method


Menyorot semua kecocokan dari ekspresi reguler dengan warna yang ditentukan.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Teks dari ekspresi reguler untuk mendapatkan teks yang akan disorot. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Warna untuk menyorot teks. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Opsi penyorotan. |
## Catatan


Tidak lagi digunakan
:   Gunakan metode HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) sebagai gantinya. Metode ini akan dihapus setelah rilis versi 24.10.


Berikut contoh kode menunjukkan cara menyorot teks dalam [TextFrame](../) menggunakan ekspresi reguler. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// menyorot semua kata dengan 10 atau lebih karakter
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method


Menyorot semua kecocokan dari ekspresi reguler dengan warna yang ditentukan.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Ekspresi reguler [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) untuk mendapatkan string yang akan disorot. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Warna untuk menyorot teks. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objek panggilan balik untuk menerima hasil pencarian [IFindResultCallback](../../ifindresultcallback/). |
## Catatan



Berikut contoh kode menunjukkan cara menyorot teks dalam [TextFrame](../) menggunakan ekspresi reguler. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// menyorot semua kata dengan 10 atau lebih karakter
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [Color](../../../system.drawing/color/)
* Kelas [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Kelas [TextFrame](../)
* Kelas [Regex](../../../system.text.regularexpressions/regex/)
* Kelas [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)