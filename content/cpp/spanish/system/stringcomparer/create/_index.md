---
title: Create()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un comparador específico de cultura.
type: docs
weight: 79
url: /es/system/stringcomparer/create/
---
## StringComparer::Create(const System::SharedPtr\<System::Globalization::CultureInfo\>\&, bool) método


Crea un comparador específico de cultura.

```cpp
static StringComparerPtr System::StringComparer::Create(const System::SharedPtr<System::Globalization::CultureInfo> &culture, bool ignoreCase)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| culture | const [System::SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura para la cual crear el comparador. |
| ignoreCase | **bool** | Indica si el comparador debe ignorar mayúsculas y minúsculas. |

### Valor devuelto

Puntero al objeto comparador recién creado.

## Ver también

* Typedef [StringComparerPtr](../../stringcomparerptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [StringComparer](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)