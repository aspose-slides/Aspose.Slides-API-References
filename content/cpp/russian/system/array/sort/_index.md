---
title: Sort()
second_title: Справочник API Aspose.Slides для C++
description: Сортирует элементы в указанном массиве, используя сравниватель по умолчанию.
type: docs
weight: 742
url: /ru/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) метод


Сортирует элементы в указанном массиве, используя сравниватель по умолчанию.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Целевой массив |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) метод


Сортирует диапазон элементов в указанном массиве, используя сравниватель по умолчанию.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Целевой массив |
| startIndex | int | Индекс, обозначающий начало диапазона элементов для сортировки |
| count | int | Размер диапазона элементов для сортировки |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) метод


Сортирует элементы в указанном массиве, используя указанный сравниватель.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Целевой массив |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | Объект IComparer<T>, используемый для сравнения элементов массива |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) метод


НЕ РЕАЛИЗОВАНО.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```


## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) метод


Сортирует элементы в указанном массиве, используя заданное сравнение.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) метод


Сортирует два массива — один, содержащий ключи, и другой — соответствующие элементы, основываясь на значениях массива ключей, элементы которого сравниваются с помощью оператора <.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TKey | Тип элементов в массиве **keys** |
| TValue | тип элементов в массиве **items** |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) которая содержит значения ключей |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) которая содержит элементы, сопоставленные со значениями ключей в массиве **keys** |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) метод


Сортирует два массива — один, содержащий ключи, и другой — соответствующие элементы, основываясь на значениях массива ключей, элементы которого сравниваются с помощью сравнивателя по умолчанию.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TKey | Тип элементов в массиве **keys** |
| TValue | тип элементов в массиве **items** |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) которая содержит значения ключей |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) которая содержит элементы, сопоставленные со значениями ключей в массиве **keys** |
| index | int | Индекс, обозначающий начало диапазона для сортировки |
| length | int | Количество элементов в диапазоне для сортировки |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Comparison](../../comparison/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)