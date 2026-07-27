---
title: AddPath()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega la ruta especificada a la ruta representada por el objeto actual.
type: docs
weight: 222
url: /es/system.drawing.drawing2d/graphicspath/addpath/
---
## GraphicsPath::AddPath(const SharedPtr\<GraphicsPath\>\&, bool) método

Agrega la ruta especificada a la ruta representada por el objeto actual.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPath(const SharedPtr<GraphicsPath> &path, bool connect)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../)\>\& | La ruta a agregar |
| connect | **bool** | True especifica que la última figura del **path** forma parte de la última figura de la ruta representada por el objeto actual; false especifica que la primera figura del **path** y la última figura de la ruta representada por el objeto actual son figuras separadas |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [GraphicsPath](../)
* Espacio de nombres [System::Drawing::Drawing2D](../../)
* Biblioteca [Aspose.Slides](../../../)