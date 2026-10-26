---
title: CreatePortion()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una porción de texto vacía.
type: docs
weight: 1
url: /es/aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() método

Crea una porción de texto vacía.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```

### Valor devuelto

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) método

Crea una porción de texto a partir de la cadena especificada.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | Cadena. |

### Valor devuelto

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) método

Crea una porción usando los datos de una porción especificada.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
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
* Clase [PortionFactory](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)