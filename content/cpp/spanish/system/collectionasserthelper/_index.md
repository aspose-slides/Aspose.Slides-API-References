---
title: CollectionAssertHelper
second_title: Referencia de API de Aspose.Slides para C++
description: API Heler para operaciones relacionadas con colecciones.
type: docs
weight: 1548
url: /es/system/collectionasserthelper/
---
## CollectionAssertHelper struct

API Heler para operaciones relacionadas con colecciones.

```cpp
class CollectionAssertHelper
```

## Métodos

| Método | Descripción |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Comprueba que todos los elementos de la colección cumplen el predicado. |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Comprueba que algún elemento de la colección cumple el predicado. |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Serializa dos colecciones para su representación en un mensaje. |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | Convierte la colección a cadena uniendo las representaciones en cadena de los elementos. |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Calcula la 'diferencia' entre dos colecciones. Para cada elemento de cada colección como clave, el valor resultante será positivo si el elemento ocurre más veces en la colección "expected", negativo si ocurre más veces en la colección "actual", y cero si ocurre el mismo número de veces en ambas colecciones. |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | Formatea la cadena para ser usada como texto del mensaje. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)