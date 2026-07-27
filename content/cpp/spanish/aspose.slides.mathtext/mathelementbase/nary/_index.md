---
title: Nary()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un operador N-ario
type: docs
weight: 157
url: /es/aspose.slides.mathtext/mathelementbase/nary/
---
## MathElementBase::Nary(MathNaryOperatorTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) método

Crea un operador N-ario

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Nary(MathNaryOperatorTypes type, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | El tipo de operador N-ario |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | El límite inferior |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | El límite superior |

### Valor devuelto

Nueva instancia del tipo [IMathNaryOperator](../../imathnaryoperator/)
## Observaciones



Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"i-1");
auto lowerLimit = System::MakeObject<MathematicalText>(u"i=0");
auto upperLimit = System::MakeObject<MathematicalText>(u"\U0001d465");
auto naryOperator = baseElement->Nary(MathNaryOperatorTypes::Summation, lowerLimit, upperLimit);
```

## MathElementBase::Nary(MathNaryOperatorTypes, System::String, System::String) método

Crea un operador N-ario

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Nary(MathNaryOperatorTypes type, System::String lowerLimit, System::String upperLimit) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | El tipo de operador N-ario |
| lowerLimit | [System::String](../../../system/string/) | El límite inferior |
| upperLimit | [System::String](../../../system/string/) | El límite superior |

### Valor devuelto

Nueva instancia del tipo [IMathNaryOperator](../../imathnaryoperator/)
## Observaciones



Ejemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"i")->Nary(MathNaryOperatorTypes::Summation, u"i=0", u"\U0001d465");
```

## Ver también

* Enum [MathNaryOperatorTypes](../../mathnaryoperatortypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathNaryOperator](../../imathnaryoperator/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathElementBase](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)