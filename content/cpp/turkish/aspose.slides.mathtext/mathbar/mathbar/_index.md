---
title: MathBar()
second_title: Aspose.Slides için C++ API Referansı
description: MathBar'ı üst çizgi (Üst konum) ile başlatır
type: docs
weight: 40
url: /tr/aspose.slides.mathtext/mathbar/mathbar/
---
## MathBar::MathBar(System::SharedPtr\<IMathElement\>) yapıcı

[MathBar](../) öğesini üst çizgi (Üst konum) ile başlatır

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Barın uygulandığı temel öğe |

## Açıklamalar

Örnek: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBar::MathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) yapıcı

[MathBar](../) öğesini belirtilen konumla başlatır

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Barın uygulandığı temel öğe |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Bar çizgisinin konumu. |

## Açıklamalar

Örnek: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"), MathTopBotPositions::Bottom);
```

## İlgili

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathBar](../)
* İsim uzayı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)