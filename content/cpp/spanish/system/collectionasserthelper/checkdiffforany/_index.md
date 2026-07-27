---
title: CheckDiffForAny()
second_title: Referencia de API de Aspose.Slides para C++
description: Comprueba que cualquier elemento de la colección cumpla el predicado.
type: docs
weight: 27
url: /es/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) método

Comprueba que cualquier elemento de la colección cumpla el predicado.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Predicado a comprobar. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Valores a comprobar. |

### Valor devuelto

Verdadero si la verificación tiene éxito para cualquier elemento, falso si todos pasan.

## Ver también

* Definición de tipo [SharedPtr](../../sharedptr/)
* Clase [ICollection](../../../system.collections.generic/icollection/)
* Estructura [CollectionAssertHelper](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)