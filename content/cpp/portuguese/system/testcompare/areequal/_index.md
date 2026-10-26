---
title: AreEqual()
second_title: Aspose.Slides para C++ – Referência da API
description: Compara arrays de não ponteiros.
type: docs
weight: 1
url: /pt/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) método

Compara arrays de não ponteiros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do primeiro elemento do array. |
| U | Tipo do segundo elemento do array. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Array LHS. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | Array RHS. |

### Valor de retorno

true se os tamanhos e os dados dos arrays coincidirem, false caso contrário.

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) método

Compara arrays de ponteiros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do primeiro elemento apontado do array. |
| U | Tipo do segundo elemento apontado do array. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Array LHS. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Array RHS. |

### Valor de retorno

true se os tamanhos e os objetos dos arrays coincidirem, false caso contrário.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) método

Compara listas de não ponteiros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do primeiro elemento da lista. |
| U | Tipo do segundo elemento da lista. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Lista LHS. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Lista RHS. |

### Valor de retorno

true se os tamanhos e os dados coincidirem, false caso contrário.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) método

Compara listas de ponteiros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do primeiro elemento apontado da lista. |
| U | Tipo do segundo elemento apontado da lista. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Lista LHS. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Lista RHS. |

### Valor de retorno

true se os tamanhos e os objetos das listas coincidirem, false caso contrário.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) método

Compara listas com arrays no caso de elementos não ponteiros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do elemento da lista. |
| U | [Array](../../array/) tipo de elemento. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Lista. |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/). |

### Valor de retorno

true se os tamanhos e os dados coincidirem, false caso contrário.

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) método

Compara listas com arrays no caso de elementos não ponteiros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [Array](../../array/) tipo de elemento. |
| U | Tipo do elemento da lista. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/). |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Lista. |

### Valor de retorno

true se os tamanhos e os dados coincidirem, false caso contrário.

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) método

Compara listas com arrays no caso de elementos ponteiros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [Array](../../array/) tipo apontado. |
| U | Tipo apontado da lista. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/). |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Lista. |

### Valor de retorno

true se os tamanhos e os objetos coincidirem, false caso contrário.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) método

Compara listas com arrays no caso de elementos ponteiros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo apontado da lista. |
| U | [Array](../../array/) tipo apontado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Lista. |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/). |

### Valor de retorno

true se os tamanhos e os objetos coincidirem, false caso contrário.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) método

Compara dicionários de tipos mapeados sem ponteiro.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| K | Tipo da chave. |
| U | Tipo mapeado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Dicionário LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Dicionário RHS. |

### Valor de retorno

true se os tamanhos e os dados dos dicionários coincidirem, false caso contrário.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&) método

Compara dicionários de tipos mapeados por ponteiro.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| K | Tipo da chave. |
| U | Tipo apontado mapeado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Dicionário LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Dicionário RHS. |

### Valor de retorno

true se os tamanhos e os dados dos dicionários coincidirem, false caso contrário.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) método

Compara dicionários de tipos diferentes.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| K1 | Tipo da chave do dicionário LHS. |
| U1 | Tipo mapeado do dicionário LHS. |
| K2 | Tipo da chave do dicionário RHS. |
| U2 | Tipo mapeado do dicionário RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | Dicionário LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | Dicionário RHS. |

### Valor de retorno

Sempre retorna false pois a conversão de tipo é proibida aqui.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) método

Compara conjuntos de hash de não ponteiros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do primeiro elemento do hashset. |
| U | Tipo do segundo elemento do hashset. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | Conjunto de hash LHS. |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | Conjunto de hash RHS. |

### Valor de retorno

true se os tamanhos e os dados dos conjuntos coincidirem, false caso contrário.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>\&) método

Compara conjuntos de hash de ponteiros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo apontado do primeiro hashset. |
| U | Tipo apontado do segundo hashset. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Conjunto de hash LHS. |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Conjunto de hash RHS. |

### Valor de retorno

true se os tamanhos e os dados dos conjuntos coincidirem, false caso contrário.

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) método

Compara filas de não ponteiros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do primeiro elemento da fila. |
| U | Tipo do segundo elemento da fila. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | Fila LHS. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | Fila RHS. |

### Valor de retorno

true se os tamanhos e os dados das filas coincidirem, false caso contrário.

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) método

Compara filas de ponteiros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo apontado do primeiro elemento da fila. |
| U | Tipo apontado do segundo elemento da fila. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | Fila LHS. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | Fila RHS. |

### Valor de retorno

true se os tamanhos e os dados das filas coincidirem, false caso contrário.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) método

Compara pilhas de não ponteiros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do primeiro elemento da pilha. |
| U | Tipo do segundo elemento da pilha. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | Pilha LHS. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | Pilha RHS. |

### Valor de retorno

true se os tamanhos e os dados das pilhas coincidirem, false caso contrário.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>\&) método

Compara pilhas de ponteiros.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo apontado do primeiro elemento da pilha. |
| U | Tipo apontado do segundo elemento da pilha. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Pilha LHS. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Pilha RHS. |

### Valor de retorno

true se os tamanhos e os dados das pilhas coincidirem, false caso contrário.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) método

Compara dicionários ordenados de tipos mapeados sem ponteiro.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| K | Tipo da chave. |
| U | Tipo mapeado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Dicionário LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Dicionário RHS. |

### Valor de retorno

true se os tamanhos e os dados dos dicionários coincidirem, false caso contrário.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>) método

Compara dicionários ordenados de tipos mapeados por ponteiro.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| K | Tipo da chave. |
| U | Tipo apontado mapeado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Dicionário LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Dicionário RHS. |

### Valor de retorno

true se os tamanhos e os dados dos dicionários coincidirem, false caso contrário.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) método

Compara dicionários ordenados de tipos diferentes.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| K1 | Tipo da chave do dicionário LHS. |
| U1 | Tipo mapeado do dicionário LHS. |
| K2 | Tipo da chave do dicionário RHS. |
| U2 | Tipo mapeado do dicionário RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | Dicionário LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | Dicionário RHS. |

### Valor de retorno

Sempre retorna false pois a conversão de tipo é proibida aqui.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) método

Compara listas ordenadas de tipos mapeados sem ponteiro.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| K | Tipo da chave. |
| U | Tipo mapeado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Lista LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Lista RHS. |

### Valor de retorno

true se os tamanhos e os dados das listas coincidirem, false caso contrário.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&) método

Compara listas ordenadas de tipos mapeados por ponteiro.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| K | Tipo da chave. |
| U | Tipo apontado mapeado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Lista LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Lista RHS. |

### Valor de retorno

true se os tamanhos e os dados das listas coincidirem, false caso contrário.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) método

Compara listas ordenadas de tipos diferentes.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| K1 | Tipo da chave da lista LHS. |
| U1 | Tipo mapeado da lista LHS. |
| K2 | Tipo da chave da lista RHS. |
| U2 | Tipo mapeado da lista RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | Lista LHS. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | Lista RHS. |

### Valor de retorno

Sempre retorna false pois a conversão de tipo é proibida aqui.

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) método

Compara coleções de strings.

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Coleção LHS. |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Coleção RHS. |

### Valor de retorno

True se os tamanhos e os dados coincidirem, false caso contrário.

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) método

Compara instâncias de IEnumerable.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | Objeto enumerável LHS. |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | Objeto enumerável RHS. |

### Valor de retorno

True se os tamanhos e os dados coincidirem, false caso contrário.

## Veja Também

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Classe [Array](../../array/)
* Classe [List](../../../system.collections.generic/list/)
* Classe [Dictionary](../../../system.collections.generic/dictionary/)
* Classe [HashSet](../../../system.collections.generic/hashset/)
* Classe [QueuePtr](../../../system.collections.generic/queueptr/)
* Classe [Stack](../../../system.collections.generic/stack/)
* Classe [SortedDictionary](../../../system.collections.generic/sorteddictionary/)
* Classe [SortedList](../../../system.collections.generic/sortedlist/)
* Classe [StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Estrutura [TestCompare](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)