---
title: SetSuperscript()
second_title: Aspose.Slides for C++ API Referansı
description: Üst simge oluşturur
type: docs
weight: 79
url: /tr/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) metod


Üst simge oluşturur

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Üst simge (sağ tarafta üst indis) |

### Dönüş Değeri

Türü [IMathSuperscriptElement](../../imathsuperscriptelement/) olan yeni matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) metod


Üst simge oluşturur

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Üst simge (sağ tarafta üst indis) |

### Dönüş Değeri

Türü [IMathSuperscriptElement](../../imathsuperscriptelement/) olan yeni matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Ayrıca Bakın

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathElementBase](../)
* Sınıf [String](../../../system/string/)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)