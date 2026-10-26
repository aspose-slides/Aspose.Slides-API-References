---
title: CreateMathBorderBox()
second_title: Aspose.Slides for C++ API Referansı
description: Elemanına uygulayarak bir matematik sınır kutusu oluşturur
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) yöntem


Elemanına uygulayarak bir matematik sınır kutusu oluşturur

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | sınır kutusunu uygulamak için matematik öğesi |

### Dönüş Değeri

yeni sınır kutusu öğesi

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) yöntem


Elemanına uygulayarak bir matematik sınır kutusu oluşturur

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | sınır kutusunu uygulamak için matematik öğesi |
| hideTop | **bool** | Üst Kenarı Gizle |
| hideBottom | **bool** | Alt Kenarı Gizle |
| hideLeft | **bool** | Sol Kenarı Gizle |
| hideRight | **bool** | Sağ Kenarı Gizle |
| strikethroughHorizontal | **bool** | Sınır Kutusu Üzerinde Yatay Çizgi |
| strikethroughVertical | **bool** | Sınır Kutusu Üzerinde Dikey Çizgi |
| strikethroughBottomLeftToTopRight | **bool** | Sınır Kutusu Alt Sol'dan Üst Sağa Çizgi |
| strikethroughTopLeftToBottomRight | **bool** | Sınır Kutusu Üst Sol'dan Alt Sağa Çizgi |

### Dönüş Değeri

yeni sınır kutusu öğesi

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBorderBox](../../imathborderbox/)
* Class [IMathElement](../../imathelement/)
* Class [MathBorderBoxFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)