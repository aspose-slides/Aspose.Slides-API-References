---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides for C++ API Referansı
description: Alt ve üst simgeyi solda oluşturur
type: docs
weight: 105
url: /tr/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metodu


Alt ve üst simgeyi solda oluşturur

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Alt Simge (sol tarafta alt indeks) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Üst Simge (sol tarafta üst indeks) |

### Dönüş Değeri

[IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/) tipinde yeni matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) metodu


Alt ve üst simgeyi solda oluşturur

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Alt Simge (sol tarafta alt indeks) |
| superscript | [System::String](../../../system/string/) | Üst Simge (sol tarafta üst indeks) |

### Dönüş Değeri

[IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/) tipinde yeni matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathElementBase](../)
* Sınıf [String](../../../system/string/)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)