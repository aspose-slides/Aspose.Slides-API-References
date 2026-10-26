---
title: TryGetValues()
second_title: Referencia de API de Aspose.Slides para C++
description: Intenta obtener los valores correspondientes por el nombre especificado.
type: docs
weight: 66
url: /es/system.net.http.headers/httpheaders/trygetvalues/
---
## HttpHeaders::TryGetValues(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&) método

Intenta obtener los valores correspondientes por el nombre especificado.

```cpp
bool System::Net::Http::Headers::HttpHeaders::TryGetValues(String name, System::SharedPtr<Collections::Generic::IEnumerable<String>> &values)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre del encabezado. |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Una instancia donde se asignarán los valores correspondientes. |

### Valor de retorno

True cuando los valores del encabezado se encuentran por el nombre especificado, de lo contrario false.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [IEnumerable](../../../system.collections.generic/ienumerable/)
* Clase [HttpHeaders](../)
* Espacio de nombres [System::Net::Http::Headers](../../)
* Biblioteca [Aspose.Slides](../../../)