---
title: ToBorderBox()
second_title: Aspose.Slides için C++ API Referansı
description: Bu öğeyi bir border-box içine yerleştirir
type: docs
weight: 248
url: /tr/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() metod


Bu öğeyi bir border-box içine yerleştirir

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```


### Dönüş Değeri

Bu öğeyi içinde bulunduran border-box

## Açıklamalar



Örnek: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) metod


Bu öğeyi bir border-box içine yerleştirir

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hideTop | **bool** | Üst Kenarı Gizle |
| hideBottom | **bool** | Alt Kenarı Gizle |
| hideLeft | **bool** | Sol Kenarı Gizle |
| hideRight | **bool** | Sağ Kenarı Gizle |
| strikethroughHorizontal | **bool** | Border Box Yatay Çizgi |
| strikethroughVertical | **bool** | Border Box Dikey Çizgi |
| strikethroughBottomLeftToTopRight | **bool** | Border Box Alt Sol - Üst Sağ Çizgi |
| strikethroughTopLeftToBottomRight | **bool** | Border Box Üst Sol - Alt Sağ Çizgi |

### Dönüş Değeri

Bu öğeyi içinde bulunduran border-box

## Açıklamalar



Örnek: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathBorderBox](../../imathborderbox/)
* Sınıf [MathElementBase](../)
* İsim Uzayı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)