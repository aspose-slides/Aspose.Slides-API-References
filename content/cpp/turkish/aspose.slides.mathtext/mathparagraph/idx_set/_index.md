---
title: idx_set()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen indeksteki öğeyi alır. Salt okunur IMathBlock.
type: docs
weight: 53
url: /tr/aspose.slides.mathtext/mathparagraph/idx_set/
---
## MathParagraph::idx_set(int32_t, System::SharedPtr\<IMathBlock\>) metod

Belirtilen indeksteki öğeyi alır. Salt okunur [IMathBlock](../../imathblock/).

```cpp
void Aspose::Slides::MathText::MathParagraph::idx_set(int32_t index, System::SharedPtr<IMathBlock> value) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Alınacak öğenin sıfır tabanlı indeksi |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Matematiksel metnin bloğu. |

## Açıklamalar



Örnek: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = mathParagraph->idx_get(1);
```

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathBlock](../../imathblock/)
* Sınıf [MathParagraph](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)