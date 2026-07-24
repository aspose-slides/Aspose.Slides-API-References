---
title: SetSubscript()
second_title: Aspose.Slides for C++ API Referansı
description: Alt simge oluşturur
type: docs
weight: 66
url: /tr/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) metot


Alt simge oluşturur

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Alt simge (sağ tarafta alt indeks) |

### Dönüş Değeri

Yeni [IMathSubscriptElement](../../imathsubscriptelement/) tipinde matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) metot


Alt simge oluşturur

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Alt simge (sağ tarafta alt indeks) |

### Dönüş Değeri

Yeni [IMathSubscriptElement](../../imathsubscriptelement/) tipinde matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathSubscriptElement](../../imathsubscriptelement/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathElementBase](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)