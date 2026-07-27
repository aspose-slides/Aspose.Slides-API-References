---
title: Nary()
second_title: Referência da API Aspose.Slides para C++
description: Cria um operador N-ário
type: docs
weight: 170
url: /pt/aspose.slides.mathtext/imathelement/nary/
---
## IMathElement::Nary(MathNaryOperatorTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

Cria um operador N-ário

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | O tipo do operador N-ário |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | O limite inferior |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | O limite superior |

### Valor de Retorno

Nova instância do tipo [IMathNaryOperator](../../imathnaryoperator/)
## Observações

Example: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"i-1");
System::SharedPtr<IMathElement> lowerLimit = System::MakeObject<MathematicalText>(u"i=0");
System::SharedPtr<IMathElement> upperLimit = System::MakeObject<MathematicalText>(u"\U0001d45b");
auto naryOperator = baseElement->Nary(MathNaryOperatorTypes::Summation, lowerLimit, upperLimit);
```

## IMathElement::Nary(MathNaryOperatorTypes, System::String, System::String) method

Cria um operador N-ário

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::String lowerLimit, System::String upperLimit)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | O tipo do operador N-ário |
| lowerLimit | [System::String](../../../system/string/) | O limite inferior |
| upperLimit | [System::String](../../../system/string/) | O limite superior |

### Valor de Retorno

Nova instância do tipo [IMathNaryOperator](../../imathnaryoperator/)
## Observações

Example: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"i")->Nary(MathNaryOperatorTypes::Summation, u"i=0", u"\U0001d45b");
```

## Veja Também

* Enum [MathNaryOperatorTypes](../../mathnaryoperatortypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathNaryOperator](../../imathnaryoperator/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)