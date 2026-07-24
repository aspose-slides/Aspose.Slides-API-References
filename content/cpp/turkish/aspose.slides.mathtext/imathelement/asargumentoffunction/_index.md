---
title: AsArgumentOfFunction()
second_title: C++ için Aspose.Slides API Referansı
description: Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır
type: docs
weight: 66
url: /tr/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) metodu

Belirtilen fonksiyonu, bu örneği argüman olarak alır

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Fonksiyon adı |

### Dönüş Değeri

Tipi [IMathFunction](../../imathfunction/) olan yeni matematik öğesi

## Açıklamalar



Örnek: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) metodu

Belirtilen fonksiyonu, bu örneği argüman olarak alır

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Fonksiyon adı |

### Dönüş Değeri

Tipi [IMathFunction](../../imathfunction/) olan yeni matematik öğesi

## Açıklamalar



Örnek: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) metodu

Belirtilen fonksiyonu, bu örneği argüman olarak alır

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | Tek argümanlı yaygın fonksiyon tiplerinden biri |

### Dönüş Değeri

Tipi [IMathFunction](../../imathfunction/) olan yeni matematik öğesi

## Açıklamalar



Örnek: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) metodu

Belirtilen fonksiyonu, bu örneği argüman olarak alır ve belirtilen ek argümanı kullanır

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | İki argümanlı yaygın fonksiyon tiplerinden biri: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Fonksiyon tipine bağlı ek argüman |

### Dönüş Değeri

Tipi [IMathFunction](../../imathfunction/) olan yeni matematik öğesi

## Açıklamalar



Örnek: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// 'x' değişkeninin '5' tabanındaki logaritmasını döndürür
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) metodu

Belirtilen fonksiyonu, bu örneği argüman olarak alır ve belirtilen ek argümanı kullanır

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | İki argümanlı yaygın fonksiyon tiplerinden biri: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Fonksiyon tipine bağlı ek argüman |

### Dönüş Değeri

Tipi [IMathFunction](../../imathfunction/) olan yeni matematik öğesi

## Açıklamalar



Örnek: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// 'x' değişkeninin '5' tabanındaki logaritmasını döndürür
```

## Bakınız

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)