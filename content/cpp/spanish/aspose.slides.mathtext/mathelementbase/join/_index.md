---
title: Join()
second_title: Referencia de API de Aspose.Slides para C++
description: Une un elemento matemático y forma un bloque matemático
type: docs
weight: 1
url: /es/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) método


Une un elemento matemático y forma un bloque matemático

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | El elemento que se va a unir |

### Valor de retorno

Una nueva [IMathBlock](../../imathblock/) que contiene esta instancia y el argumento especificado
## Observaciones



Ejemplo: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) método


Une un texto matemático y forma un bloque matemático

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Texto matemático que se va a unir |

### Valor de retorno

Una nueva [IMathBlock](../../imathblock/) que contiene esta instancia y el argumento especificado
## Observaciones



Ejemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathBlock](../../imathblock/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathElementBase](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)