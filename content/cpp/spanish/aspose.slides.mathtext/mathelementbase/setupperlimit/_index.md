---
title: SetUpperLimit()
second_title: Referencia de la API de Aspose.Slides para C++
description: Acepta límite superior
type: docs
weight: 131
url: /es/aspose.slides.mathtext/mathelementbase/setupperlimit/
---
## MathElementBase::SetUpperLimit(System::SharedPtr\<IMathElement\>) método


Acepta límite superior

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::SharedPtr<IMathElement> limit) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### Valor devuelto

New instance of type [IMathLimit](../../imathlimit/)
## Observaciones



Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## MathElementBase::SetUpperLimit(System::String) método


Acepta límite superior

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::String limit) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Valor devuelto

New instance of type [IMathLimit](../../imathlimit/)
## Observaciones



Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathLimit](../../imathlimit/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathElementBase](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)