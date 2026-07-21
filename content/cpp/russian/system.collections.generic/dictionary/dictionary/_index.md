---
title: Dictionary()
second_title: Справочник API Aspose.Slides for C++
description: Создает пустой словарь.
type: docs
weight: 1
url: /ru/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() конструктор

Создает пустой словарь.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) конструктор

Копирует данные из карты.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Карта, из которой копируются данные. |

## Dictionary::Dictionary(int) конструктор

Перегрузка, соответствующая созданию предвыделенного словаря; фактически не выполняет выделение памяти.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| capacity | int | Емкость для выделения; игнорируется. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) конструктор

Конструктор копирования.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../) для копирования данных из. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) конструктор

Конструктор копирования.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Исходный словарь. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) объект для использования. |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) конструктор

Создает пустой словарь.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) для использования. |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) конструктор

Создает пустой словарь.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| capacity | int | [Dictionary](../) емкость после создания; игнорируется. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) для использования. |

## См. также

* Typedef [map_t](../map_t/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Dictionary](../)
* Class [IDictionary](../../idictionary/)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)