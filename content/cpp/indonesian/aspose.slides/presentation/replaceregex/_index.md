---
title: ReplaceRegex()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengganti semua kecocokan ekspresi reguler dengan string yang ditentukan.
type: docs
weight: 534
url: /id/aspose.slides/presentation/replaceregex/
---
## Presentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) metode

Mengganti semua kecocokan ekspresi reguler dengan string yang ditentukan.

```cpp
void Aspose::Slides::Presentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Ekspresi reguler [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) untuk mendapatkan string yang akan diganti. |
| newText | [System::String](../../../system/string/) | String untuk mengganti semua kemunculan string yang akan diganti. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objek callback untuk menerima hasil pencarian [IFindResultCallback](../../ifindresultcallback/). |
## Keterangan

Contoh kode berikut menunjukkan cara mengganti teks menggunakan ekspresi reguler dengan string yang ditentukan. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [String](../../../system/string/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)