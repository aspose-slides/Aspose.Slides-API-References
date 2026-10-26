---
title: FoundResult()
second_title: Referensi API Aspose.Slides untuk C++
description: Metode callback yang menerima data tentang teks yang ditemukan.
type: docs
weight: 1
url: /id/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) metode

Metode callback yang menerima data tentang teks yang ditemukan.

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | [ITextFrame](../../itextframe/) di mana teks ditemukan. |
| sourceText | [System::String](../../../system/string/) | Teks sumber di mana teks ditemukan. |
| foundText | [System::String](../../../system/string/) | Teks yang ditemukan. |
| textPosition | **int32_t** | Posisi teks yang ditemukan. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ITextFrame](../../itextframe/)
* Kelas [String](../../../system/string/)
* Kelas [IFindResultCallback](../)
* RuangNama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)