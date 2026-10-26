---
title: ToBorderBox()
second_title: Aspose.Slides for C++ API Referansı
description: Bu öğeyi bir kenarlık kutusuna yerleştirir
type: docs
weight: 261
url: /tr/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() metot


Bu öğeyi bir kenarlık kutusuna yerleştirir

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```


### Dönüş Değeri

Bu öğe yerleştirilmiş kenarlık kutusu
## Açıklamalar



Örnek: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) metot


Bu öğeyi bir kenarlık kutusuna yerleştirir

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hideTop | **bool** | Üst Kenarı Gizle |
| hideBottom | **bool** | Alt Kenarı Gizle |
| hideLeft | **bool** | Sol Kenarı Gizle |
| hideRight | **bool** | Sağ Kenarı Gizle |
| strikethroughHorizontal | **bool** | Yatay Üst Üste Çizgi Kenarlık Kutusu |
| strikethroughVertical | **bool** | Dikey Üst Üste Çizgi Kenarlık Kutusu |
| strikethroughBottomLeftToTopRight | **bool** | Alt Sol'dan Üst Sağ'a Kenarlık Kutusu Üst Üste Çizgi |
| strikethroughTopLeftToBottomRight | **bool** | Üst Sol'dan Alt Sağ'a Kenarlık Kutusu Üst Üste Çizgi |

### Dönüş Değeri

Bu öğe yerleştirilmiş kenarlık kutusu
## Açıklamalar



Örnek: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathBorderBox](../../imathborderbox/)
* Sınıf [IMathElement](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)