---
title: CreateMathBorderBox()
second_title: Aspose.Slides için C++ API Referansı
description: Elemanı uygulayarak bir matematik kenarlık kutusu oluşturun
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathborderboxfactory/createmathborderbox/
---
## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) metodu


Elemanı uygulayarak bir matematik kenarlık kutusu oluşturun

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | kenarlık kutusu uygulanacak matematik elemanı |

### Dönüş Değeri

yeni kenarlık kutusu elemanı

## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) metodu


Elemanı uygulayarak bir matematik kenarlık kutusu oluşturun

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | kenarlık kutusu uygulanacak matematik elemanı |
| hideTop | **bool** | Üst Kenarı Gizle |
| hideBottom | **bool** | Alt Kenarı Gizle |
| hideLeft | **bool** | Sol Kenarı Gizle |
| hideRight | **bool** | Sağ Kenarı Gizle |
| strikethroughHorizontal | **bool** | Kenarlık Kutusu Yatay Çizgiyle Üst Üstüne Çiz |
| strikethroughVertical | **bool** | Kenarlık Kutusu Dikey Çizgiyle Üst Üstüne Çiz |
| strikethroughBottomLeftToTopRight | **bool** | Kenarlık Kutusu Sol-Aşağıdan Sağ-Yukarıya Çiz |
| strikethroughTopLeftToBottomRight | **bool** | Kenarlık Kutusu Sol-Yukarıdan Sağ-Aşağıya Çiz |

### Dönüş Değeri

yeni kenarlık kutusu elemanı

## ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBorderBox](../../imathborderbox/)
* Class [IMathElement](../../imathelement/)
* Class [IMathBorderBoxFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)