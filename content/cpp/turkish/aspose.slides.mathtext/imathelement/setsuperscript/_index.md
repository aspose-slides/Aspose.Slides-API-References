---
title: SetSuperscript()
second_title: Aspose.Slides for C++ API Referansı
description: Üst simge oluşturur
type: docs
weight: 92
url: /tr/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) metodu

Üst simge oluşturur

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Üst simge (sağ tarafta üst indis) |

### Dönüş Değeri

Yeni matematik öğesi, tip [IMathSuperscriptElement](../../imathsuperscriptelement/)

## Açıklamalar

Örnek: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) metodu

Üst simge oluşturur

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Üst simge (sağ tarafta üst indis) |

### Dönüş Değeri

Yeni matematik öğesi, tip [IMathSuperscriptElement](../../imathsuperscriptelement/)

## Açıklamalar

Örnek: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Sınıf [IMathElement](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)