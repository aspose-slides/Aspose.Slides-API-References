---
title: ReplaceText()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengganti semua kemunculan teks yang ditentukan dengan teks lain yang ditentukan.
type: docs
weight: 482
url: /id/aspose.slides/ipresentation/replacetext/
---
## IPresentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metode

Mengganti semua kemunculan teks yang ditentukan dengan teks lain yang ditentukan.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | String yang akan diganti. |
| newText | [System::String](../../../system/string/) | String untuk mengganti semua kemunculan oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opsi pencarian teks [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objek callback untuk menerima hasil pencarian [IFindResultCallback](../../ifindresultcallback/). |
## Catatan

Kode contoh berikut menunjukkan cara mengganti satu string yang ditentukan dengan string lain yang ditentukan.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Ganti semua kemunculan 'the' yang terpisah dengan '<em><strong>'
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [ITextSearchOptions](../../itextsearchoptions/)
* Kelas [IFindResultCallback](../../ifindresultcallback/)
* Kelas [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)