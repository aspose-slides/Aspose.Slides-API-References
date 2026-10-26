---
title: Get()
second_title: Referencia de API de Aspose.Slides para C++
description: Función para obtener el N-ésimo elemento de la tupla dada. Sobrecarga para objeto base.
type: docs
weight: 2406
url: /es/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) function

Función para obtener el N-ésimo elemento de la tupla dada. Sobrecarga para objeto base.

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| N | índice del elemento. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | objeto a inspeccionar. |

### Valor de retorno

valor del elemento N-ésimo de la tupla convertido a objeto.

## System::Get(const T\&) function

Función para obtener el N-ésimo elemento de la tupla dada. Sobrecarga para objetos con método Deconstruct.

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| N | índice del elemento. |
| T | tipo del objeto inspeccionado. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| object | const T\& | objeto a inspeccionar. |

### Valor de retorno

valor del elemento N-ésimo de la tupla.

## System::Get(const SharedPtr\<T\>\&) function

Función para obtener el N-ésimo elemento de la tupla dada. Sobrecarga para punteros compartidos.

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| N | índice del elemento. |
| T | tipo del objeto inspeccionado. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | objeto a inspeccionar. |

### Valor de retorno

valor del elemento N-ésimo de la tupla.

## System::Get(T\&, const Index\&) function

Implementación para expresiones collection[index].

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | tipo de la colección. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| collection | T\& | objeto de la colección. |
| index | const [Index](../index/)\& | índice del elemento de tipo [System.Index](../index/). |

### Valor de retorno

Elemento de la colección en el desplazamiento calculado.

## System::Get(T\&, const Range\&) function

Devuelve una porción de la colección especificada definida por el rango proporcionado.

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| collection | T\& | La colección a segmentar. |
| range | const [Range](../range/)\& | El rango que especifica los límites de la porción. |

### Valor de retorno

Una vista o porción de la colección a partir del desplazamiento inicial y la longitud calculados.

## System::Get(const ValueTuple\<Args...\>\&) function

Obtiene el N-ésimo elemento de una tupla de valores.

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| N | índice del elemento. |
| Args | elementos de la tupla. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tuple | const [ValueTuple](../valuetuple/)\<Args...\>\& | tupla de la cual obtener el elemento. |

### Valor de retorno

valor del elemento N-ésimo de la tupla.

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Class [Index](../index/)
* Class [Range](../range/)
* Class [ValueTuple](../valuetuple/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)