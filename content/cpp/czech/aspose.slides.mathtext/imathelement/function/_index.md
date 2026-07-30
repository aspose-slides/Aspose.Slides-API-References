---
title: Function()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Přijímá funkci argumentu pomocí této instance jako názvu funkce
type: docs
weight: 53
url: /cs/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) metoda


Přijímá funkci argumentu pomocí této instance jako názvu funkce

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```


### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Argument funkce |

### Návratová hodnota

Nový matematický prvek typu [IMathFunction](../../imathfunction/)
## Poznámky



Příklad: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) metoda


Přijímá funkci argumentu pomocí této instance jako názvu funkce

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```


### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | Argument funkce |

### Návratová hodnota

Nový matematický prvek typu [IMathFunction](../../imathfunction/)
## Poznámky



Příklad: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathFunction](../../imathfunction/)
* Třída [IMathElement](../)
* Třída [String](../../../system/string/)
* Obor názvů [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)