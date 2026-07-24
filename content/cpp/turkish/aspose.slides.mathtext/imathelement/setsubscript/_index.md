---
title: SetSubscript()
second_title: Aspose.Slides için C++ API Referansı
description: Alt simge oluşturur
type: docs
weight: 79
url: /tr/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) metod


Alt simge oluşturur

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Alt simge (sağ tarafta alt indeks) |

### Dönüş Değeri

Yeni [IMathSubscriptElement](../../imathsubscriptelement/) türünde matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) metod


Alt simge oluşturur

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Alt simge (sağ tarafta alt indeks) |

### Dönüş Değeri

Yeni [IMathSubscriptElement](../../imathsubscriptelement/) türünde matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## Ayrıca Bakınız

* typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathSubscriptElement](../../imathsubscriptelement/)
* Sınıf [IMathElement](../)
* Sınıf [String](../../../system/string/)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)