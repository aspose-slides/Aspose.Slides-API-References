---
title: ReplaceRegex()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengganti semua kecocokan ekspresi reguler dengan string yang ditentukan.
type: docs
weight: 157
url: /id/aspose.slides/itextframe/replaceregex/
---
## ITextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) method

Mengganti semua kecocokan ekspresi reguler dengan string yang ditentukan.

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Ekspresi reguler [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) untuk mendapatkan string yang akan diganti. |
| newText | [System::String](../../../system/string/) | String yang akan mengganti semua kejadian string yang akan diganti. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objek callback untuk menerima hasil pencarian [IFindResultCallback](../../ifindresultcallback/). |
## Catatan

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
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [String](../../../system/string/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [ITextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)