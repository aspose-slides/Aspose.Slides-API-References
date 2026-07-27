---
title: CreatePortion()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una porción de texto vacía.
type: docs
weight: 1
url: /es/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() método


Crea una porción de texto vacía.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```


### Valor devuelto

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) método


Crea una porción de texto a partir de una cadena especificada.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | Cadena. |

### Valor devuelto

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) método


Crea una porción usando datos de una porción especificada.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Una porción a usar. |

### Valor devuelto

[Portion](../../portion/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPortion](../../iportion/)
* Clase [IPortionFactory](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)