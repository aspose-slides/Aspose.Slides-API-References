---
title: AsArgumentOfFunction()
second_title: Aspose.Slides for C++ API Referansı
description: Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır
type: docs
weight: 53
url: /tr/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) metot

Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Fonksiyon adı |

### Dönüş Değeri

Yeni [IMathFunction](../../imathfunction/) tipinde matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) metot

Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Fonksiyon adı |

### Dönüş Değeri

Yeni [IMathFunction](../../imathfunction/) tipinde matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) metot

Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | Tek argümanlı ortak fonksiyon tiplerinden biri |

### Dönüş Değeri

Yeni [IMathFunction](../../imathfunction/) tipinde matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) metot

Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek argümanı alır

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | İki argümanlı ortak fonksiyon tiplerinden biri: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Fonksiyon tipine bağlı ek argüman |

### Dönüş Değeri

Yeni [IMathFunction](../../imathfunction/) tipinde matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// 'x' öğesinin '5' tabanındaki logaritmasını döndürür
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) metot

Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek argümanı alır

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | İki argümanlı ortak fonksiyon tiplerinden biri: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Fonksiyon tipine bağlı ek argüman |

### Dönüş Değeri

Yeni [IMathFunction](../../imathfunction/) tipinde matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// 'x' öğesinin '5' tabanındaki logaritmasını döndürür
```

## İlgili

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)