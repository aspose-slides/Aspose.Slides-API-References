---
title: "System::MemoryExtensions::Details"
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 638
url: /de/system.memoryextensions.details/
---
## Funktionen

| Funktion | Beschreibung |
| --- | --- |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<U\>\&) | Vergleicht zwei Smart-Pointer. |
| **int32_t** [Compare](./compare/)(const T\&, const T\&) | Vergleicht zwei arithmetische Werte. |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const U\&) | Vergleicht einen Smart-Pointer mit einem Wert. |
| **int32_t** [LastIndexOfImpl](./lastindexofimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**, const T\&) | Findet den letzten Index eines Wertes in einem Span. |
| **bool** [SequenceEqualImpl](./sequenceequalimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const **int32_t**, **int32_t**, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Prüft, ob zwei Spans ab den angegebenen Positionen gleich sind. |
| void [IntroSort](./introsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Interne Implementierung des Introsort-Algorithmus für Schlüssel-Wert-Paare. |
| void [SwapIfGreaterWithValues](./swapifgreaterwithvalues/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>, **int32_t**, **int32_t**) | Vertauscht Schlüssel-Wert-Paare, wenn die Vergleichsbedingung erfüllt ist. |
| void [InsertionSort](./insertionsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Führt Insertion Sort für Schlüssel-Wert-Paare aus. |
| void [HeapSort](./heapsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Führt Heap Sort für Schlüssel-Wert-Paare aus. |
| void [Heapify](./heapify/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Erhält die Heap-Eigenschaft für Schlüssel-Wert-Paare bei. |
| **int32_t** [PickPivotAndPartition](./pickpivotandpartition/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Wählt das Pivot aus und partitioniert Schlüssel-Wert-Paare für Quicksort. |
| **int32_t** [BinarySearchImpl](./binarysearchimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const TValue\&, TCompareFunc) | Allgemeine Implementierung der Binärsuche. |