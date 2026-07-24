---
title: Group()
second_title: Aspose.Slides için C++ API Referansı
description: Bu öğeyi alt kıvrımlı parantez kullanarak bir gruba yerleştirir
type: docs
weight: 248
url: /tr/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() metod


Bu öğeyi alt kıvrımlı parantez kullanarak bir gruba yerleştirir

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```


### Dönüş Değeri

Yeni [IMathGroupingCharacter](../../imathgroupingcharacter/) tipinde örnek
## Açıklamalar



Örnek: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) metod


Bu öğeyi alt kıvrımlı parantez gibi bir gruplama karakteri veya başka bir karakter kullanarak bir gruba yerleştirir

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| character | char16_t | Gruplama karakteri, BOTTOM CURLY BRACKET (U+23DF) veya başka bir karakter gibi |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Gruplama karakterinin konumu |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Grup karakterinin dikey hizalaması. Nesnenin temel çizgiye göre hizalamasını belirler. Örneğin, grup karakteri nesnenin üzerindeyse, VerticalJustification Top değeri, nesnenin üst kısmının temel çizgiye denk geldiğini gösterir; VerticalJustification Bottom ayarlandığında, nesnenin alt kısmı temel çizgide olur |

### Dönüş Değeri

Yeni [IMathGroupingCharacter](../../imathgroupingcharacter/) tipinde örnek
## Açıklamalar



Örnek: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## İlgili

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)