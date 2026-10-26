---
title: FromStream()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un objeto Image a partir del flujo especificado.
type: docs
weight: 339
url: /es/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) método

Crea un objeto [Image](../) a partir del flujo especificado.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Un flujo que contiene datos de imagen |
| use_embedded_color_management | **bool** | IGNORADO |
| validate_image_data | **bool** | IGNORADO |

### Valor devuelto

Un puntero compartido al objeto [Image](../) creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Image](../)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)