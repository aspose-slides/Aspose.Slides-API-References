---
title: IndexOf()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyondaki belirli bir IMathBlock'un indeksini belirler.
type: docs
weight: 131
url: /tr/aspose.slides.mathtext/mathparagraph/indexof/
---
## MathParagraph::IndexOf(System::SharedPtr\<IMathBlock\>) yöntemi

Belirli bir [IMathBlock](../../imathblock/) koleksiyondaki indeksi belirler.

```cpp
int32_t Aspose::Slides::MathText::MathParagraph::IndexOf(System::SharedPtr<IMathBlock> mathBlock) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Koleksiyonda bulunacak öğe. |

### Dönüş Değeri

Koleksiyonda bulunursa *mathBlock*'ın indeksi; aksi takdirde -1.

## Açıklamalar

Örnek: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
int32_t index = mathParagraph->IndexOf(block);
```

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)