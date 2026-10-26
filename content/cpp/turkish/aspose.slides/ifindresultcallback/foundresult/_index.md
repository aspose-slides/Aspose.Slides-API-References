---
title: FoundResult()
second_title: Aspose.Slides for C++ API Referansı
description: Bulunan metinle ilgili verileri alan geri çağırma yöntemi.
type: docs
weight: 1
url: /tr/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) metot

Bulunan metinle ilgili verileri alan geri çağırma metodu.

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | Metnin bulunduğu [ITextFrame](../../itextframe/). |
| sourceText | [System::String](../../../system/string/) | Metnin bulunduğu kaynak metin. |
| foundText | [System::String](../../../system/string/) | Bulunan metin. |
| textPosition | **int32_t** | Bulunan metnin konumu. |

## Ayrıca Bakınız

* Tip tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [ITextFrame](../../itextframe/)
* Sınıf [String](../../../system/string/)
* Sınıf [IFindResultCallback](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)