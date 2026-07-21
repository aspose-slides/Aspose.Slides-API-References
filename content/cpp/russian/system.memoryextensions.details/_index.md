---
title: "System::MemoryExtensions::Details"
second_title: Справочник API Aspose.Slides для C++
description: 
type: docs
weight: 638
url: /ru/system.memoryextensions.details/
---
## Функции

| Функция | Описание |
| --- | --- |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<U\>\&) | Сравнивает два умных указателя. |
| **int32_t** [Compare](./compare/)(const T\&, const T\&) | Сравнивает два арифметических значения. |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const U\&) | Сравнивает умный указатель со значением. |
| **int32_t** [LastIndexOfImpl](./lastindexofimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**, const T\&) | Находит последний индекс значения в диапазоне. |
| **bool** [SequenceEqualImpl](./sequenceequalimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const **int32_t**, **int32_t**, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Проверяет, равны ли два диапазона, начиная с указанных позиций. |
| void [IntroSort](./introsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Внутренняя реализация алгоритма introsort для пар ключ-значение. |
| void [SwapIfGreaterWithValues](./swapifgreaterwithvalues/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>, **int32_t**, **int32_t**) | Обменивает пары ключ-значение, если выполнено условие сравнения. |
| void [InsertionSort](./insertionsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Выполняет сортировку вставками пар ключ-значение. |
| void [HeapSort](./heapsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Выполняет пирамидальную сортировку пар ключ-значение. |
| void [Heapify](./heapify/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Поддерживает свойство кучи для пар ключ-значение. |
| **int32_t** [PickPivotAndPartition](./pickpivotandpartition/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Выбирает опорный элемент и разбивает пары ключ-значение для быстрой сортировки. |
| **int32_t** [BinarySearchImpl](./binarysearchimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const TValue\&, TCompareFunc) | Общая реализация бинарного поиска. |