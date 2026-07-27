---
title: GetChildRows()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene filas que se consideran hijas a través de la relación especificada.
type: docs
weight: 27
url: /es/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) método

Obtiene filas que se consideran hijas a través de la relación especificada.

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | Objeto de relación para especificar la relación fila padre - fila hijo. |

### Valor devuelto

[Array](../../../system/array/) de filas hijas recuperadas.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [DataRow](../)
* Clase [DataRelation](../../datarelation/)
* Espacio de nombres [System::Data](../../)
* Biblioteca [Aspose.Slides](../../../)