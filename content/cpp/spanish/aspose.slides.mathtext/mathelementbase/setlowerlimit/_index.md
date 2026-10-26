---
title: SetLowerLimit()
second_title: Referencia de API de Aspose.Slides para C++
description: Toma el límite inferior
type: docs
weight: 144
url: /es/aspose.slides.mathtext/mathelementbase/setlowerlimit/
---
## MathElementBase::SetLowerLimit(System::SharedPtr\<IMathElement\>) método


Toma el límite inferior

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::SharedPtr<IMathElement> limit) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### Valor devuelto

Nueva instancia del tipo [IMathLimit](../../imathlimit/)
## Observaciones



Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## MathElementBase::SetLowerLimit(System::String) método


Toma el límite inferior

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::String limit) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Valor devuelto

Nueva instancia del tipo [IMathLimit](../../imathlimit/)
## Observaciones



Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## Ver también

* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [IMathLimit](../../imathlimit/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathElementBase](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)