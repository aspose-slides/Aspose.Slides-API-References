---
title: Clear()
second_title: Aspose.Slides para la referencia de API de C++
description: No compatible porque el arreglo representado por el objeto actual es de solo lectura.
type: docs
weight: 53
url: /es/system/array/clear/
---
## Array::Clear() método


No compatible porque el arreglo representado por el objeto actual es de solo lectura.

```cpp
virtual void System::Array<T>::Clear() override
```


## Array::Clear(const ArrayPtr\<Type\>\&, int, int) método


Reemplaza los valores **count** a partir del índice **startIndex** en el arreglo especificado con valores predeterminados.

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Type | Tipo de elementos en el arreglo objetivo |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Arreglo objetivo |
| startIndex | int | [Index](../../index/) en el que se comienza a reemplazar los elementos |
| count | int | El número de elementos a reemplazar |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Método [Type](../../object/type/)
* Clase [Array](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)