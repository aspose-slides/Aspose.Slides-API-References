---
title: AreEqual()
second_title: Referencia de la API de Aspose.Slides para C++
description: Compara arreglos de no punteros.
type: docs
weight: 1
url: /es/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) method

Compara arreglos de no punteros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del primer elemento del arreglo. |
| U | Tipo del segundo elemento del arreglo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Arreglo LHS. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | Arreglo RHS. |

### Valor devuelto

true si los tamaños y los datos de los arreglos coinciden, false de lo contrario.

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) method

Compara arreglos de punteros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del elemento apuntado del primer arreglo. |
| U | Tipo del elemento apuntado del segundo arreglo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Arreglo LHS. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Arreglo RHS. |

### Valor devuelto

true si los tamaños y los objetos de los arreglos coinciden, false de lo contrario.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method

Compara listas de no punteros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del primer elemento de la lista. |
| U | Tipo del segundo elemento de la lista. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Lista LHS. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Lista RHS. |

### Valor devuelto

true si los tamaños y los datos de las listas coinciden, false de lo contrario.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method

Compara listas de punteros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del elemento apuntado del primer lista. |
| U | Tipo del elemento apuntado del segundo lista. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Lista LHS. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Lista RHS. |

### Valor devuelto

true si los tamaños y los objetos de las listas coinciden, false de lo contrario.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) method

Compara listas con arreglos en caso de elementos no punteros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del elemento de la lista. |
| U | Tipo del elemento [Array](../../array/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Lista. |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/). |

### Valor devuelto

true si los tamaños y los datos coinciden, false de lo contrario.

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method

Compara listas con arreglos en caso de elementos no punteros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del elemento [Array](../../array/). |
| U | Tipo del elemento de la lista. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/). |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Lista. |

### Valor devuelto

true si los tamaños y los datos coinciden, false de lo contrario.

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method

Compara listas con arreglos en caso de elementos punteros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del elemento apuntado [Array](../../array/). |
| U | Tipo del elemento apuntado de la lista. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/). |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Lista. |

### Valor devuelto

true si los tamaños y los objetos coinciden, false de lo contrario.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) method

Compara listas con arreglos en caso de elementos punteros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del elemento apuntado de la lista. |
| U | Tipo del elemento apuntado [Array](../../array/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Lista. |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/). |

### Valor devuelto

true si los tamaños y los objetos coinciden, false de lo contrario.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) method

Compara diccionarios de tipos mapeados sin puntero.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| K | Tipo de la clave. |
| U | Tipo mapeado. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Diccionario LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Diccionario RHS. |

### Valor devuelto

true si los tamaños y los datos de los diccionarios coinciden, false de lo contrario.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&) method

Compara diccionarios de tipos mapeados con puntero.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| K | Tipo de la clave. |
| U | Tipo apuntado del elemento mapeado. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Diccionario LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Diccionario RHS. |

### Valor devuelto

true si los tamaños y los datos de los diccionarios coinciden, false de lo contrario.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) method

Compara diccionarios de tipos diferentes.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| K1 | Tipo de la clave del diccionario LHS. |
| U1 | Tipo mapeado del diccionario LHS. |
| K2 | Tipo de la clave del diccionario RHS. |
| U2 | Tipo mapeado del diccionario RHS. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | Diccionario LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | Diccionario RHS. |

### Valor devuelto

Siempre devuelve false ya que la conversión de tipos está prohibida aquí.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) method

Compara conjuntos hash de no punteros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del primer elemento del conjunto hash. |
| U | Tipo del segundo elemento del conjunto hash. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | Conjunto hash LHS. |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | Conjunto hash RHS. |

### Valor devuelto

true si los tamaños y los datos de los conjuntos hash coinciden, false de lo contrario.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>\&) method

Compara conjuntos hash de punteros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo apuntado del primer conjunto hash. |
| U | Tipo apuntado del segundo conjunto hash. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Conjunto hash LHS. |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Conjunto hash RHS. |

### Valor devuelto

true si los tamaños y los datos de los conjuntos hash coinciden, false de lo contrario.

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) method

Compara colas de no punteros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del primer elemento de la cola. |
| U | Tipo del segundo elemento de la cola. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | Cola LHS. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | Cola RHS. |

### Valor devuelto

true si los tamaños y los datos de las colas coinciden, false de lo contrario.

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) method

Compara colas de punteros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo apuntado del primer cola. |
| U | Tipo apuntado del segundo cola. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | Cola LHS. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | Cola RHS. |

### Valor devuelto

true si los tamaños y los datos de las colas coinciden, false de lo contrario.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) method

Compara pilas de no punteros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del primer elemento de la pila. |
| U | Tipo del segundo elemento de la pila. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | Pila LHS. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | Pila RHS. |

### Valor devuelto

true si los tamaños y los datos de las pilas coinciden, false de lo contrario.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>\&) method

Compara pilas de punteros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo apuntado del primer pila. |
| U | Tipo apuntado del segundo pila. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Pila LHS. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Pila RHS. |

### Valor devuelto

true si los tamaños y los datos de las pilas coinciden, false de lo contrario.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) method

Compara diccionarios ordenados de tipos mapeados sin puntero.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| K | Tipo de la clave. |
| U | Tipo mapeado. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Diccionario LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Diccionario RHS. |

### Valor devuelto

true si los tamaños y los datos de los diccionarios coinciden, false de lo contrario.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&) method

Compara diccionarios ordenados de tipos mapeados con puntero.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| K | Tipo de la clave. |
| U | Tipo apuntado del elemento mapeado. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Diccionario LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Diccionario RHS. |

### Valor devuelto

true si los tamaños y los datos de los diccionarios coinciden, false de lo contrario.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) method

Compara diccionarios ordenados de tipos diferentes.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| K1 | Tipo de la clave del diccionario LHS. |
| U1 | Tipo mapeado del diccionario LHS. |
| K2 | Tipo de la clave del diccionario RHS. |
| U2 | Tipo mapeado del diccionario RHS. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | Diccionario LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | Diccionario RHS. |

### Valor devuelto

Siempre devuelve false ya que la conversión de tipos está prohibida aquí.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) method

Compara listas ordenadas de tipos mapeados sin puntero.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| K | Tipo de la clave. |
| U | Tipo mapeado. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Lista LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Lista RHS. |

### Valor devuelto

true si los tamaños y los datos de las listas coinciden, false de lo contrario.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&) method

Compara listas ordenadas de tipos mapeados con puntero.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| K | Tipo de la clave. |
| U | Tipo apuntado del elemento mapeado. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Lista LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Lista RHS. |

### Valor devuelto

true si los tamaños y los datos de las listas coinciden, false de lo contrario.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) method

Compara listas ordenadas de tipos diferentes.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| K1 | Tipo de la clave de la lista LHS. |
| U1 | Tipo mapeado de la lista LHS. |
| K2 | Tipo de la clave de la lista RHS. |
| U2 | Tipo mapeado de la lista RHS. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | Lista LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | Lista RHS. |

### Valor devuelto

Siempre devuelve false ya que la conversión de tipos está prohibida aquí.

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) method

Compara colecciones de cadenas.

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Colección LHS. |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Colección RHS. |

### Valor devuelto

True si los tamaños y los datos coinciden, false de lo contrario.

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) method

Compara instancias de IEnumerable.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | Objeto enumerable LHS. |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | Objeto enumerable RHS. |

### Valor devuelto

True si los tamaños y los datos coinciden, false de lo contrario.

## Véase también

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Clase [Array](../../array/)
* Clase [List](../../../system.collections.generic/list/)
* Clase [Dictionary](../../../system.collections.generic/dictionary/)
* Clase [HashSet](../../../system.collections.generic/hashset/)
* Clase [QueuePtr](../../../system.collections.generic/queueptr/)
* Clase [Stack](../../../system.collections.generic/stack/)
* Clase [SortedDictionary](../../../system.collections.generic/sorteddictionary/)
* Clase [SortedList](../../../system.collections.generic/sortedlist/)
* Clase [StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)
* Clase [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [TestCompare](../)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)