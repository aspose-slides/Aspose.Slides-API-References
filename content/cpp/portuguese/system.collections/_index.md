---
title: "System::Collections"
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 300
url: /pt/system.collections/
---
## Classes

| Class | Description |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) de bits que podem ser endereçados por índice. Objetos desta classe devem ser alocados somente usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo às funções como argumento. |
| [BitArrayPtr](./bitarrayptr/) | Ponteiro para [BitArray](./bitarray/). Este tipo é um ponteiro para gerenciar a exclusão de outros objetos. Ele deve ser alocado na pilha e passado para funções por valor ou por referência constante. |
| [CollectionBase](./collectionbase/) | Fornece uma classe base abstrata para uma coleção fortemente tipada. |
| [ICollection](./icollection/) | Define a interface de coleção não genérica. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) é a interface base para todas as coleções não genéricas que podem ser enumeradas. |
| [IEnumerator](./ienumerator/) | Interface de enumerador que pode ser usada para iterar através de alguns elementos. Objetos desta classe devem ser alocados somente usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo às funções como argumento. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | Wrapper que cria implementação não genérica [IEnumerator](./ienumerator/) sobre o Iterator genérico [IEnumeratorImplRefType](./ienumeratorimplreftype/) - wrapper para os tipos de referência. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | Wrapper que cria implementação não genérica [IEnumerator](./ienumerator/) sobre o Iterator genérico [IEnumeratorImplRefType](./ienumeratorimplreftype/) - wrapper para os tipos de valor. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) Representa uma coleção não genérica de objetos que podem ser acessados individualmente por índice. |
| [IListImplRefType](./ilistimplreftype/) | Stub que implementa a interface [System::Collections::IList](./ilist/) em objeto [System::Collections::Generic::List](../system.collections.generic/list/). Implementação para tipos de referência. |
| [IListImplValueType](./ilistimplvaluetype/) | Stub que implementa a interface [System::Collections::IList](./ilist/) em objeto [System::Collections::Generic::List](../system.collections.generic/list/). Implementação para tipos de valor. |
| [IListWrapper](./ilistwrapper/) | Interface para suportar casting de coleção genérica para não genérica. |
| [Invalidatable](./invalidatable/) | Classe que possibilita rastrear o estado de seus descendentes através de objetos [InvalidatableTracker](./invalidatabletracker/). |
| [InvalidatableTracker](./invalidatabletracker/) | Classe que implementa rastreadores de objetos [Invalidatable](./invalidatable/). |