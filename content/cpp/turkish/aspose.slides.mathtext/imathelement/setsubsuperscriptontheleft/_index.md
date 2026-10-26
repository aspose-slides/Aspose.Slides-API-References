---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides for C++ API Referansı
description: Sol tarafta alt simge ve üst simge oluşturur
type: docs
weight: 118
url: /tr/aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft/
---
## IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metot

Sol tarafta alt simge ve üst simge oluşturur

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Alt simge (sol tarafta alt indeks) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Üst simge (sol tarafta üst indeks) |

### Dönüş Değeri

Yeni [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/) tipinde matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheLeft(System::String, System::String) metot

Sol tarafta alt simge ve üst simge oluşturur

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Alt simge (sol tarafta alt indeks) |
| superscript | [System::String](../../../system/string/) | Üst simge (sol tarafta üst indeks) |

### Dönüş Değeri

Yeni [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/) tipinde matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Sınıf [IMathElement](../)
* Sınıf [String](../../../system/string/)
* İsim Alanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)