---
title: Dictionary()
second_title: Referência da API Aspose.Slides para C++
description: Cria dicionário vazio.
type: docs
weight: 1
url: /pt/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() construtor

Cria dicionário vazio.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) construtor

Copia os dados do map.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Map a ser copiado. |

## Dictionary::Dictionary(int) construtor

Sobrecarga que corresponde à criação de um dicionário pré-alocado; na verdade não faz alocação.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| capacity | int | Capacidade a alocar; ignorado. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) construtor

Construtor de cópia.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../) a ser copiado. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) construtor

Construtor de cópia.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Dicionário de origem. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) objeto a ser usado. |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) construtor

Cria dicionário vazio.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) a ser usado. |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) construtor

Cria dicionário vazio.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| capacity | int | [Dictionary](../) capacidade após a criação; ignorado. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) a ser usado. |

## Veja Também

* Typedef [map_t](../map_t/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Dictionary](../)
* Classe [IDictionary](../../idictionary/)
* Classe [IEqualityComparer](../../iequalitycomparer/)
* Espaço de nomes [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)