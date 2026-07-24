---
title: Function()
second_title: Aspose.Slides için C++ API Referansı
description: Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır
type: docs
weight: 40
url: /tr/aspose.slides.mathtext/mathelementbase/function/
---
## MathElementBase::Function(System::SharedPtr\<IMathElement\>) metot

Bu örnek, bu nesneyi fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::SharedPtr<IMathElement> functionArgument) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Fonksiyonun bir argümanı |

### Dönüş Değeri

Tipi [IMathFunction](../../imathfunction/) olan yeni matematik öğesi

## Açıklamalar

Örnek: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## MathElementBase::Function(System::String) metot

Bu örnek, bu nesneyi fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::String functionArgument) override
```

### Parametreler

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

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathFunction](../../imathfunction/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathElementBase](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)