---
title: Join()
second_title: Referencia de API de Aspose.Slides para C++
description: Une un elemento matemático y forma un bloque matemático
type: docs
weight: 14
url: /es/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) método


Une un elemento matemático y forma un bloque matemático

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | El elemento que se va a unir |

### Valor devuelto

Un nuevo [IMathBlock](../../imathblock/) que contiene esta instancia y el argumento especificado
## Observaciones



Ejemplo: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) método


Une un texto matemático y forma un bloque matemático

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Texto matemático que se va a unir |

### Valor devuelto

Un nuevo [IMathBlock](../../imathblock/) que contiene esta instancia y el argumento especificado
## Observaciones



Ejemplo: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathBlock](../../imathblock/)
* Clase [IMathElement](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)