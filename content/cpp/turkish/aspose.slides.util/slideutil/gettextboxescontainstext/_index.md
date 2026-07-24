---
title: GetTextBoxesContainsText()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen slaytta verilen metni içeren tüm metin çerçevelerini döndürür.
type: docs
weight: 66
url: /tr/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) method

Belirtilen slaytta verilen metni içeren tüm metin çerçevelerini döndürür.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Aranacak slayt. |
| text | [System::String](../../../system/string/) | Metin çerçevelerinde aranacak metin. |
| checkPlaceholderText | **bool** | Yer tutucu metni arama metnini içeriyorsa, boş olan metin çerçevelerinin de dahil edilip edilmeyeceğini belirtir. |

### Dönüş Değeri

Belirtilen metni içeren [ITextFrame](../../../aspose.slides/itextframe/) nesnelerinden oluşan bir dizi.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ITextFrame](../../../aspose.slides/itextframe/)
* Sınıf [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Sınıf [String](../../../system/string/)
* Sınıf [SlideUtil](../)
* Ad alanı [Aspose::Slides::Util](../../)
* Kütüphane [Aspose.Slides](../../../)