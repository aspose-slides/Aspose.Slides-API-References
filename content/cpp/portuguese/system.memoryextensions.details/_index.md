---
title: "System::MemoryExtensions::Details"
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 638
url: /pt/system.memoryextensions.details/
---
## Funções

| Função | Descrição |
| --- | --- |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<U\>\&) | Compara dois ponteiros inteligentes. |
| **int32_t** [Compare](./compare/)(const T\&, const T\&) | Compara dois valores aritméticos. |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const U\&) | Compara um ponteiro inteligente com um valor. |
| **int32_t** [LastIndexOfImpl](./lastindexofimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**, const T\&) | Encontra o último índice de um valor em um intervalo. |
| **bool** [SequenceEqualImpl](./sequenceequalimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const **int32_t**, **int32_t**, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Verifica se dois intervalos são iguais a partir das posições especificadas. |
| void [IntroSort](./introsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Implementação interna do algoritmo introsort para pares chave-valor. |
| void [SwapIfGreaterWithValues](./swapifgreaterwithvalues/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>, **int32_t**, **int32_t**) | Troca pares chave-valor se a condição de comparação for atendida. |
| void [InsertionSort](./insertionsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Realiza ordenação por inserção em pares chave-valor. |
| void [HeapSort](./heapsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Realiza ordenação heap em pares chave-valor. |
| void [Heapify](./heapify/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Mantém a propriedade de heap para pares chave-valor. |
| **int32_t** [PickPivotAndPartition](./pickpivotandpartition/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | Seleciona o pivô e particiona pares chave-valor para quicksort. |
| **int32_t** [BinarySearchImpl](./binarysearchimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const TValue\&, TCompareFunc) | Implementação comum de busca binária. |