---
title: Function()
second_title: Aspose.Slides for C++ API Referansı
description: Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır
type: docs
weight: 53
url: /tr/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) metot


Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Fonksiyonun bir argümanı |

### Dönüş Değeri

Tipi [IMathFunction](../../imathfunction/) olan yeni matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) metot


Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | Fonksiyonun bir argümanı |

### Dönüş Değeri

Tipi [IMathFunction](../../imathfunction/) olan yeni matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## Ayrıca Bakınız

* Tip tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathFunction](../../imathfunction/)
* Sınıf [IMathElement](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)