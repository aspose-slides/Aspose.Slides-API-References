---
title: Join()
second_title: Aspose.Slides için C++ API Referansı
description: Bir matematiksel öğeyi birleştirir ve bir matematik bloğu oluşturur
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) metot

Bir matematiksel öğeyi birleştirir ve bir matematik bloğu oluşturur

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Birleştirilecek öğe |

### Dönüş Değeri

Bu örneği ve belirtilen argümanı içeren yeni bir [IMathBlock](../../imathblock/)

## Açıklamalar

Örnek: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) metot

Bir matematiksel metni birleştirir ve bir matematik bloğu oluşturur

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Birleştirilecek matematiksel metin |

### Dönüş Değeri

Bu örneği ve belirtilen argümanı içeren yeni bir [IMathBlock](../../imathblock/)

## Açıklamalar

Örnek: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathBlock](../../imathblock/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathElementBase](../)
* Sınıf [String](../../../system/string/)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)