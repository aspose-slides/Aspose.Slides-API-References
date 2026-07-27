---
title: get_PortionFormat()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el objeto de formato que contiene las propiedades de formato establecidas explícitamente de la porción de texto sin aplicar herencia. Solo lectura IPortionFormat.
type: docs
weight: 1
url: /es/aspose.slides/iportion/get_portionformat/
---
## IPortion::get_PortionFormat() método


Devuelve el objeto de formato que contiene las propiedades de formato establecidas explícitamente de la porción de texto sin aplicar herencia. Solo lectura [IPortionFormat](../../iportionformat/).

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::IPortion::get_PortionFormat()=0
```

## Observaciones


El objeto de formato contiene los parámetros de formato definidos solo para la porción actual, no se aplican los datos heredados.

Para obtener los valores efectivos, incluidos los heredados, use [IPortionFormat::GetEffective](../../iportionformat/geteffective/) método.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPortionFormat](../../iportionformat/)
* Clase [IPortion](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)