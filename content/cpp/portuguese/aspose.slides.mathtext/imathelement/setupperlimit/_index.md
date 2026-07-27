---
title: SetUpperLimit()
second_title: Referência da API Aspose.Slides for C++
description: Define limite superior
type: docs
weight: 144
url: /pt/aspose.slides.mathtext/imathelement/setupperlimit/
---
## IMathElement::SetUpperLimit(System::SharedPtr\<IMathElement\>) método

Define limite superior

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::SharedPtr<IMathElement> limit)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### Valor de retorno

Nova instância do tipo [IMathLimit](../../imathlimit/)

## Observações



Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## IMathElement::SetUpperLimit(System::String) método

Define limite superior

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::String limit)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Valor de retorno

Nova instância do tipo [IMathLimit](../../imathlimit/)

## Observações



Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathLimit](../../imathlimit/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)