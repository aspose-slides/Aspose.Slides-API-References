---
title: Join()
second_title: Aspose.Slides için C++ API Referansı
description: Bu matematiksel blok ile bir matematiksel öğeyi birleştirir
type: docs
weight: 183
url: /tr/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) metodu


Bu matematiksel blok ile bir matematiksel öğeyi birleştirir

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Birleştirilecek öğe |

### Dönüş Değeri

Mevcut [IMathBlock](../../imathblock/) örneği
## Açıklamalar



Örnek: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) metodu


Bu matematiksel blok ile bir matematiksel metni birleştirir

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Birleştirilecek matematiksel metin |

### Dönüş Değeri

Bu örnek ve belirtilen argümanı içeren yeni bir [IMathBlock](../../imathblock/)

## Açıklamalar



Örnek: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathBlock](../../imathblock/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathBlock](../)
* Sınıf [String](../../../system/string/)
* İsim Uzayı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)