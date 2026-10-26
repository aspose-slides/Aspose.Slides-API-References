---
title: RemoveAt()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyonun belirtilen dizinindeki öğeyi kaldırır.
type: docs
weight: 170
url: /tr/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock::RemoveAt(int32_t) metot


Koleksiyonun belirtilen indeksindeki öğeyi kaldırır.

```cpp
void Aspose::Slides::MathText::MathBlock::RemoveAt(int32_t index) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Kaldırılacak öğenin sıfır tabanlı indeksi. |
## Açıklamalar



Örnek: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->RemoveAt(2);
```

## Ayrıca Bakınız

* Sınıf [MathBlock](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)