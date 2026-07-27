---
title: ConvertAll()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una lista de elementos convertidos a un tipo diferente.
type: docs
weight: 352
url: /es/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) método

Crea una lista de elementos convertidos a un tipo diferente.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| OutputType | Tipo de elemento de lista de salida. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | Convertidor a usar para la conversión de elementos. |

### Valor de retorno

Una lista recién creada de elementos convertidos.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Converter](../../../system/converter/)
* Clase [List](../)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)