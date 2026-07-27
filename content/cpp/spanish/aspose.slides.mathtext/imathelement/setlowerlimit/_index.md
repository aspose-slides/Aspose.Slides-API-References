---
title: SetLowerLimit()
second_title: Referencia de API de Aspose.Slides para C++
description: Toma el límite inferior
type: docs
weight: 157
url: /es/aspose.slides.mathtext/imathelement/setlowerlimit/
---
## IMathElement::SetLowerLimit(System::SharedPtr\<IMathElement\>) método

Toma el límite inferior

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::SharedPtr<IMathElement> limit)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | límite |

### Valor de retorno

Nueva instancia del tipo [IMathLimit](../../imathlimit/)
## Comentarios



Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## IMathElement::SetLowerLimit(System::String) método

Toma el límite inferior

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::String limit)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | límite |

### Valor de retorno

Nueva instancia del tipo [IMathLimit](../../imathlimit/)
## Comentarios



Ejemplo: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathLimit](../../imathlimit/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)