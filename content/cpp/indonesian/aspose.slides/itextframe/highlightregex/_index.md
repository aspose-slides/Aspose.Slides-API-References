---
title: HighlightRegex()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyorot semua kecocokan ekspresi reguler dengan warna yang ditentukan.
type: docs
weight: 131
url: /id/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) metode


Menyorot semua kecocokan ekspresi reguler dengan warna yang ditentukan.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Ekspresi reguler [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) untuk mendapatkan string yang akan disorot. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Warna untuk menyorot teks. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objek callback untuk menerima hasil pencarian [IFindResultCallback](../../ifindresultcallback/). |
## Catatan



Contoh kode berikut menunjukkan cara menyorot teks dalam [TextFrame](../../textframe/) menggunakan ekspresi reguler. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) metode


Menyorot semua kecocokan ekspresi reguler dengan warna yang ditentukan.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Teks ekspresi reguler untuk mendapatkan teks yang akan disorot. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Warna untuk menyorot teks. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Opsi penyorotan. |

Tidak Direkomendasikan
:   Gunakan metode HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) sebagai gantinya. Metode ini akan dihapus setelah rilis versi 24.10.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [Color](../../../system.drawing/color/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [ITextFrame](../)
* Class [String](../../../system/string/)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)