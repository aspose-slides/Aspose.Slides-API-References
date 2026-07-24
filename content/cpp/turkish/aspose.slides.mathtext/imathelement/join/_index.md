---
title: Join()
second_title: Aspose.Slides for C++ API Referansı
description: Matematiksel bir öğeyi birleştirir ve bir matematiksel blok oluşturur
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) metodu


Bir matematiksel öğeyi birleştirir ve bir matematiksel blok oluşturur

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Birleştirilecek öğe |

### Dönüş Değeri

Bu örnek ve belirtilen bağımsız değişkeni içeren yeni [IMathBlock](../../imathblock/)

## Açıklamalar



Örnek: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) metodu


Bir matematiksel metni birleştirir ve bir matematiksel blok oluşturur

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Birleştirilecek matematiksel metin |

### Dönüş Değeri

Bu örnek ve belirtilen bağımsız değişkeni içeren yeni [IMathBlock](../../imathblock/)

## Açıklamalar



Örnek: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Ayrıca Bakınız

* Tip tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathBlock](../../imathblock/)
* Sınıf [IMathElement](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)