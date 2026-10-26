---
title: SetLowerLimit()
second_title: Referência da API Aspose.Slides para C++
description: Define o limite inferior
type: docs
weight: 157
url: /pt/aspose.slides.mathtext/imathelement/setlowerlimit/
---
## IMathElement::SetLowerLimit(System::SharedPtr\<IMathElement\>) método

Define o limite inferior

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::SharedPtr<IMathElement> limit)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limite |

### Valor de Retorno

Nova instância do tipo [IMathLimit](../../imathlimit/)
## Observações



Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## IMathElement::SetLowerLimit(System::String) método


Define o limite inferior

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::String limit)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limite |

### Valor de Retorno

Nova instância do tipo [IMathLimit](../../imathlimit/)
## Observações



Exemplo: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathLimit](../../imathlimit/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)