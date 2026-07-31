---
title: ReplaceRegex()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengganti semua kecocokan ekspresi reguler dengan string yang ditentukan.
type: docs
weight: 183
url: /id/aspose.slides/textframe/replaceregex/
---
## TextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) metode

Mengganti semua kecocokan ekspresi reguler dengan string yang ditentukan.

```cpp
void Aspose::Slides::TextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Ekspresi reguler [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) untuk mendapatkan string yang akan diganti. |
| newText | [System::String](../../../system/string/) | String untuk mengganti semua kejadian string yang akan diganti. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objek callback untuk menyimpan hasil operasi penggantian [IFindResultCallback](../../ifindresultcallback/). |
## Keterangan

Contoh kode berikut menunjukkan cara mengganti teks menggunakan ekspresi reguler dengan string yang ditentukan. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Regex](../../../system.text.regularexpressions/regex/)
* Kelas [String](../../../system/string/)
* Kelas [IFindResultCallback](../../ifindresultcallback/)
* Kelas [TextFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)