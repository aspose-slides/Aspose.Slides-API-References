---
title: Dictionary()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea un diccionario vacío.
type: docs
weight: 1
url: /es/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() constructor

Crea un diccionario vacío.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) constructor

Copia datos del mapa.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Mapa del que copiar datos. |

## Dictionary::Dictionary(int) constructor

Sobrecarga que corresponde a crear un diccionario preasignado; en realidad no realiza asignación.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| capacity | int | Capacidad a asignar; ignorada. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) constructor

Constructor de copia.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../) para copiar datos de. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) constructor

Constructor de copia.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Diccionario fuente. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) objeto a usar. |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) constructor

Crea un diccionario vacío.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) a usar. |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) constructor

Crea un diccionario vacío.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| capacity | int | [Dictionary](../) capacidad después de la creación; ignorada. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) a usar. |

## See Also

* Typedef [map_t](../map_t/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Dictionary](../)
* Clase [IDictionary](../../idictionary/)
* Clase [IEqualityComparer](../../iequalitycomparer/)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)