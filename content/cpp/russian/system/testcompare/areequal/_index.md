---
title: AreEqual()
second_title: Справочник API Aspose.Slides для C++
description: Сравнивает массивы без указателей.
type: docs
weight: 1
url: /ru/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) method

Сравнивает массивы без указателей.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип первого элемента массива. |
| U | Тип второго элемента массива. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Левый массив. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | Правый массив. |

### Возвращаемое значение

true, если размеры массивов и данные совпадают, иначе false.

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) method

Сравнивает массивы указателей.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип первого элемента-указателя массива. |
| U | Тип второго элемента-указателя массива. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Левый массив. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Правый массив. |

### Возвращаемое значение

true, если размеры массивов и объекты совпадают, иначе false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method

Сравнивает списки без указателей.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип первого элемента списка. |
| U | Тип второго элемента списка. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Левый список. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Правый список. |

### Возвращаемое значение

true, если размеры и данные совпадают, иначе false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method

Сравнивает списки указателей.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип первого элемента-указателя списка. |
| U | Тип второго элемента-указателя списка. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Левый список. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Правый список. |

### Возвращаемое значение

true, если размеры списков и объекты совпадают, иначе false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) method

Сравнивает списки с массивами в случае элементов без указателей.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элемента списка. |
| U | [Array](../../array/) тип элемента. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Список. |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/). |

### Возвращаемое значение

true, если размеры и данные совпадают, иначе false.

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method

Сравнивает списки с массивами в случае элементов без указателей.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Array](../../array/) тип элемента. |
| U | Тип элемента списка. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/). |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Список. |

### Возвращаемое значение

true, если размеры и данные совпадают, иначе false.

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method

Сравнивает списки с массивами в случае элементов-указателей.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Array](../../array/) тип указываемого значения. |
| U | Тип элемента списка-указателя. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/). |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Список. |

### Возвращаемое значение

true, если размеры и объекты совпадают, иначе false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) method

Сравнивает списки с массивами в случае элементов-указателей.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип указываемого значения списка. |
| U | [Array](../../array/) тип указываемого значения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Список. |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/). |

### Возвращаемое значение

true, если размеры и объекты совпадают, иначе false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) method

Сравнивает словари с типами значений без указателей.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| K | Тип ключа. |
| U | Тип значения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Левый словарь. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Правый словарь. |

### Возвращаемое значение

true, если размеры словарей и данные совпадают, иначе false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&) method

Сравнивает словари с типами значений-указателей.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| K | Тип ключа. |
| U | Тип указываемого значения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Левый словарь. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Правый словарь. |

### Возвращаемое значение

true, если размеры словарей и данные совпадают, иначе false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) method

Сравнивает словари разных типов.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| K1 | Тип ключа левого словаря. |
| U1 | Тип значения левого словаря. |
| K2 | Тип ключа правого словаря. |
| U2 | Тип значения правого словаря. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | Левый словарь. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | Правый словарь. |

### Возвращаемое значение

Всегда возвращает false, так как преобразование типов запрещено.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) method

Сравнивает хеш-множества без указателей.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип первого элемента хеш-множества. |
| U | Тип второго элемента хеш-множества. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | Левый хеш-множество. |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | Правый хеш-множество. |

### Возвращаемое значение

true, если размеры хеш-множест и данные совпадают, иначе false.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>\&) method

Сравнивает хеш-множества указателей.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип первого указываемого значения хеш-множества. |
| U | Тип второго указываемого значения хеш-множества. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Левый хеш-множество. |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Правый хеш-множество. |

### Возвращаемое значение

true, если размеры хеш-множест и объекты совпадают, иначе false.

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) method

Сравнивает очереди без указателей.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип первого элемента очереди. |
| U | Тип второго элемента очереди. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | Левая очередь. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | Правая очередь. |

### Возвращаемое значение

true, если размеры очередей и данные совпадают, иначе false.

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) method

Сравнивает очереди указателей.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип первого указываемого значения очереди. |
| U | Тип второго указываемого значения очереди. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | Левая очередь. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | Правая очередь. |

### Возвращаемое значение

true, если размеры очередей и данные совпадают, иначе false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) method

Сравнивает стеки без указателей.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип первого элемента стека. |
| U | Тип второго элемента стека. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | Левый стек. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | Правый стек. |

### Возвращаемое значение

true, если размеры стеков и данные совпадают, иначе false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>\&) method

Сравнивает стеки указателей.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип первого указываемого значения стека. |
| U | Тип второго указываемого значения стека. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Левый стек. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Правый стек. |

### Возвращаемое значение

true, если размеры стеков и данные совпадают, иначе false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) method

Сравнивает сортированные словари с типами значений без указателей.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| K | Тип ключа. |
| U | Тип значения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Левый словарь. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Правый словарь. |

### Возвращаемое значение

true, если размеры словарей и данные совпадают, иначе false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&) method

Сравнивает сортированные словари с типами значений-указателей.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| K | Тип ключа. |
| U | Тип указываемого значения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Левый словарь. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Правый словарь. |

### Возвращаемое значение

true, если размеры словарей и данные совпадают, иначе false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) method

Сравнивает сортированные словари разных типов.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| K1 | Тип ключа левого словаря. |
| U1 | Тип значения левого словаря. |
| K2 | Тип ключа правого словаря. |
| U2 | Тип значения правого словаря. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | Левый словарь. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | Правый словарь. |

### Возвращаемое значение

Всегда возвращает false, так как преобразование типов запрещено.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) method

Сравнивает сортированные списки с типами значений без указателей.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| K | Тип ключа. |
| U | Тип значения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Левый список. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Правый список. |

### Возвращаемое значение

true, если размеры списков и данные совпадают, иначе false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&) method

Сравнивает сортированные списки с типами значений-указателей.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| K | Тип ключа. |
| U | Тип указываемого значения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Левый список. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Правый список. |

### Возвращаемое значение

true, если размеры списков и данные совпадают, иначе false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) method

Сравнивает сортированные списки разных типов.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| K1 | Тип ключа левого списка. |
| U1 | Тип значения левого списка. |
| K2 | Тип ключа правого списка. |
| U2 | Тип значения правого списка. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | Левый список. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | Правый список. |

### Возвращаемое значение

Всегда возвращает false, так как преобразование типов запрещено.

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) method

Сравнивает коллекции строк.

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Левая коллекция. |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Правая коллекция. |

### Возвращаемое значение

True, если размеры и данные совпадают, иначе false.

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) method

Сравнивает экземпляры IEnumerable.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | Левый перечислимый объект. |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | Правый перечислимый объект. |

### Возвращаемое значение

True, если размеры и данные совпадают, иначе false.

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../../array/)
* Class [List](../../../system.collections.generic/list/)
* Class [Dictionary](../../../system.collections.generic/dictionary/)
* Class [HashSet](../../../system.collections.generic/hashset/)
* Class [QueuePtr](../../../system.collections.generic/queueptr/)
* Class [Stack](../../../system.collections.generic/stack/)
* Class [SortedDictionary](../../../system.collections.generic/sorteddictionary/)
* Class [SortedList](../../../system.collections.generic/sortedlist/)
* Class [StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [TestCompare](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)