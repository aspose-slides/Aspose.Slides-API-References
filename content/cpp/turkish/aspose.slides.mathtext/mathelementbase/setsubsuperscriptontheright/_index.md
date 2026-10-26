---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides için C++ API Referansı
description: Sağ tarafta alt simge ve üst simge oluşturur
type: docs
weight: 92
url: /tr/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
---
## MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metodu


Sağ tarafta alt simge ve üst simge oluşturur

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Alt simge (sağ tarafta alt indeks) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Üst simge (sağ tarafta üst indeks) |

### Dönüş Değeri

Yeni [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/) tipinde matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheRight(System::String, System::String) metodu


Sağ tarafta alt simge ve üst simge oluşturur

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Alt simge (sağ tarafta alt indeks) |
| superscript | [System::String](../../../system/string/) | Üst simge (sağ tarafta üst indeks) |

### Dönüş Değeri

Yeni [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/) tipinde matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathElementBase](../)
* Sınıf [String](../../../system/string/)
* İsim Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)