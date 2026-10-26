---
title: CreateMathFunction()
second_title: Aspose.Slides için C++ API Referansı
description: Matematik fonksiyonu oluşturur
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathfunctionfactory/createmathfunction/
---
## IMathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) yöntemi


Matematik fonksiyonu oluşturur

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Fonksiyon adı olarak kullanılan öğe |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Fonksiyon argümanı olarak kullanılan öğe |

### Dönüş Değeri

yeni matematik fonksiyonu

## IMathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) yöntemi


Matematik fonksiyonu oluşturur

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | Fonksiyon adı |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Fonksiyon argümanı olarak kullanılan öğe |

### Dönüş Değeri

yeni matematik fonksiyonu

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../../imathelement/)
* Class [IMathFunctionFactory](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)