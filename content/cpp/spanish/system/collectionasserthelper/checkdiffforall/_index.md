---
title: CheckDiffForAll()
second_title: Aspose.Slides para la Referencia de la API de C++
description: Comprueba que todos los elementos de la colección cumplen el predicado.
type: docs
weight: 14
url: /es/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) método

Comprueba que todos los elementos de la colección cumplen el predicado.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Predicado a comprobar. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Valores a comprobar. |

### Valor de retorno

Falso si la verificación falla para algún elemento, verdadero si todos pasan.

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [ICollection](../../../system.collections.generic/icollection/)
* Estructura [CollectionAssertHelper](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)