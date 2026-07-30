---
title: SetUpperLimit()
second_title: Riferimento API di Aspose.Slides per C++
description: Accetta limite superiore
type: docs
weight: 131
url: /it/aspose.slides.mathtext/mathelementbase/setupperlimit/
---
## MathElementBase::SetUpperLimit(System::SharedPtr\<IMathElement\>) metodo


Accetta limite superiore

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::SharedPtr<IMathElement> limit) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| limite | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limite |

### Valore restituito

Nuova istanza del tipo [IMathLimit](../../imathlimit/)
## Osservazioni



Esempio: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## MathElementBase::SetUpperLimit(System::String) metodo


Accetta limite superiore

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::String limit) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| limite | [System::String](../../../system/string/) | limite |

### Valore restituito

Nuova istanza del tipo [IMathLimit](../../imathlimit/)
## Osservazioni



Esempio: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathLimit](../../imathlimit/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)