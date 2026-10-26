---
title: Group()
second_title: Aspose.Slides for C++ API Referansı
description: Bu öğeyi alt süslü parantez kullanarak bir gruba yerleştirir
type: docs
weight: 235
url: /tr/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() metodu

Bu öğeyi, alt süslü parantez kullanarak bir gruba yerleştirir

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```


### Dönüş Değeri

Yeni [IMathGroupingCharacter](../../imathgroupingcharacter/) türünde örnek
## Açıklamalar



Örnek: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) metodu


Bu öğeyi, alt süslü parantez gibi bir gruplama karakteri veya başka bir karakter kullanarak bir gruba yerleştirir

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| character | char16_t | Gruplama Karakteri, BOTTOM CURLY BRACKET (U+23DF) gibi veya başka bir karakter |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Gruplama karakterinin konumu |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Grup karakterinin dikey hizalaması. Nesnenin temel çizgiye göre hizalanmasını belirtir. Örneğin, grup karakteri nesnenin üzerindeyse, VerticalJustification değerinin Top olması, nesnenin üstünün temel çizgiye denk geldiği anlamına gelir; VerticalJustification Bottom olarak ayarlandığında, nesnenin altı temel çizgide olur. |

### Dönüş Değeri

Yeni [IMathGroupingCharacter](../../imathgroupingcharacter/) türünde örnek
## Açıklamalar



Örnek: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Ayrıca Bakınız

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)