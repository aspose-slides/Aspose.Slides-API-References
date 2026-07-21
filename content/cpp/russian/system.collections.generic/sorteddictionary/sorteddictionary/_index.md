---
title: SortedDictionary()
second_title: Справочник API Aspose.Slides для C++
description: Создает пустой словарь.
type: docs
weight: 14
url: /ru/system.collections.generic/sorteddictionary/sorteddictionary/
---
## SortedDictionary::SortedDictionary() конструктор

Создает пустой словарь.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary()
```

## SortedDictionary::SortedDictionary(const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) конструктор

Создает пустой словарь.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IComparer<typename BasePointerType<TKey>::type>> &comparer)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\& | [Comparer](../../comparer/) to use. |

## SortedDictionary::SortedDictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) конструктор

Конструктор копирования.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Source dictionary to copy data from. |

## SortedDictionary::SortedDictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) конструктор

Конструктор копирования.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IComparer<typename BasePointerType<TKey>::type>> &comparer)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Source dictionary to copy data from. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\& | [Comparer](../../comparer/) to use. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [SortedDictionary](../)
* Класс [IComparer](../../icomparer/)
* Класс [IDictionary](../../idictionary/)
* Пространство имён [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)