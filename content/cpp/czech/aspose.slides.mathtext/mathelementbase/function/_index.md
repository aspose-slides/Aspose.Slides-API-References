---
title: Function()
second_title: Aspose.Slides pro C++ API Reference
description: Přijímá funkci argumentu s použitím této instance jako názvu funkce
type: docs
weight: 40
url: /cs/aspose.slides.mathtext/mathelementbase/function/
---
## MathElementBase::Function(System::SharedPtr\<IMathElement\>) metoda


Přijímá funkci argumentu s použitím této instance jako názvu funkce

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::SharedPtr<IMathElement> functionArgument) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument funkce |

### Návratová hodnota

Nový matematický prvek typu [IMathFunction](../../imathfunction/)
## Poznámky



Příklad: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## MathElementBase::Function(System::String) metoda


Přijímá funkci argumentu s použitím této instance jako názvu funkce

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::String functionArgument) override
```


### Argumenty

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
* Třída [IMathElement](../../imathelement/)
* Třída [MathElementBase](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)