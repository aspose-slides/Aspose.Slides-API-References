---
title: get_PortionFormat()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve un objeto de formato que contiene las propiedades de formato establecidas explícitamente de la porción de texto sin aplicar herencia. Solo lectura IPortionFormat.
type: docs
weight: 1
url: /es/aspose.slides/portion/get_portionformat/
---
## Portion::get_PortionFormat() método

Devuelve un objeto de formato que contiene las propiedades de formato establecidas explícitamente de la porción de texto sin aplicar herencia. Solo lectura [IPortionFormat](../../iportionformat/).

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::Portion::get_PortionFormat() override
```

## Observaciones

El objeto de formato contiene los parámetros de formato definidos solo para la porción actual; los datos heredados no se aplican.

Para obtener los valores efectivos, incluidos los heredados, use el método [PortionFormat::GetEffective](../../portionformat/geteffective/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPortionFormat](../../iportionformat/)
* Clase [Portion](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)