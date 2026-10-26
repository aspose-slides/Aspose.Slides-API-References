---
title: MakeDiff()
second_title: Referencia de API de Aspose.Slides para C++
description: Calcula el 'diff' entre dos colecciones. Para cada elemento de cada colección como clave, el valor resultante será positivo si el elemento ocurre más veces en la colección \"expected\", negativo si ocurre más veces en la colección \"actual\", y cero si ocurre el mismo número de veces en cada colección.
type: docs
weight: 1
url: /es/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) method


Calcula el “diff” entre dos colecciones. Para cada elemento de cada colección como clave, el valor resultante será positivo si el elemento ocurre más veces en la colección “expected”, negativo si ocurre más veces en la colección “actual”, y cero si ocurre el mismo número de veces en ambas colecciones.

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| T1 | Tipo de elemento de la colección esperada. |
| T2 | Tipo de elemento de la colección real. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Colección esperada. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Colección real. |

### Valor de retorno

Mapa de resultados de comparación por valor según las reglas anteriores.

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Class [Dictionary](../../../system.collections.generic/dictionary/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)