---
title: "System::Collections::Generic"
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 326
url: /pt/system.collections.generic/
---
## Classes

| Classe | Descrição |
| --- | --- |
| [_KeyCollection](./_keycollection/) | Coleção das chaves de [Dictionary](./dictionary/). Referência à coleção, não copia nada. Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [_KeyList](./_keylist/) | Implementa lista de chaves de dicionário. Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [_ValueCollection](./_valuecollection/) | Coleção dos valores de [Dictionary](./dictionary/). Referência à coleção, não copia nada. Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [_ValueList](./_valuelist/) | Implementa lista de valores de dicionário. Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [BaseDictionary](./basedictionary/) | Implementa código comum para várias estruturas semelhantes a dicionário (ex.: [Dictionary](./dictionary/), [SortedDictionary](./sorteddictionary/)). Não deve ser usado diretamente, exceto para herança ao definir contêineres. Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [BaseEnumerator](./baseenumerator/) | Definição de enumerador para envolver tipos estilo STL para uso estilo C#. Não faz asserções sobre a estrutura do contêiner exceto a existência de iterador sequencial. Usa as funções begin() e end(). Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [BaseKVCollection](./basekvcollection/) | Mantém código comum para coleções de chaves ou valores. Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [BaseSet](./baseset/) |  |
| [Comparer](./comparer/) | Fornece uma classe base para implementações da interface genérica [System.Collections.Generic.IComparer](./icomparer/). |
| [DefaultComparer](./defaultcomparer/) | Classe comparadora padrão. Usa os operadores < e == para comparar valores. Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [Details_KeyNotFoundException](./details_keynotfoundexception/) |  |
| [Dictionary](./dictionary/) | Declaração antecipada da classe [Dictionary](./dictionary/). |
| [DictionaryIterator](./dictionaryiterator/) | Iterador [Dictionary](./dictionary/) que fornece notação [KeyValuePair](./keyvaluepair/). |
| [DictionaryPtr](./dictionaryptr/) | Classe ponteiro [Dictionary](./dictionary/) com sobrecarga de operadores. Este tipo é um ponteiro para gerenciar a deleção de outro objeto. Deve ser alocado na pilha e passado para funções por valor ou por referência constante. |
| [EnumerableExt](./enumerableext/) |  |
| [EnumeratorWrapperIterator](./enumeratorwrapperiterator/) | Iterador que envolve o enumerador pré-criado e redireciona todas as chamadas para ele. |
| [HashDictionary](./hashdictionary/) | Stub para a classe [HashDictionary](./hashdictionary/) (não implementado atualmente). Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [HashSet](./hashset/) | Declaração antecipada da classe [HashSet](./hashset/). |
| [HashSetPtr](./hashsetptr/) | Ponteiro para manter referências [HashSet](./hashset/). Este tipo é um ponteiro para gerenciar a deleção de outro objeto. Deve ser alocado na pilha e passado para funções por valor ou por referência constante. |
| [ICollection](./icollection/) | Interface de coleção de elementos. Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [IComparer](./icomparer/) | Interface que compara dois objetos em sentido maior-igual-menor. Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [IDictionary](./idictionary/) | Interface para contêineres semelhantes a dicionário. Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [IEnumerable](./ienumerable/) | Interface de objeto que fornece enumerador sobre os elementos contidos. |
| [IEnumerator](./ienumerator/) | Interface de enumerador que pode ser usado para iterar através de alguns elementos. Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [IEqualityComparer](./iequalitycomparer/) | Interface que fornece meios para comparar dois objetos quanto à igualdade. Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [IKVCollection](./ikvcollection/) | Interface de contêiner que contém chaves ou valores do contêiner semelhante a dicionário. Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [IList](./ilist/) | Interface de contêiner indexado de elementos. Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [ISet](./iset/) | Interface de coleção que contém um conjunto de elementos únicos. Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [KeyIterator](./keyiterator/) | Iterador [Dictionary](./dictionary/) que fornece acesso à chave. |
| [KeyValuePair](./keyvaluepair/) | Par de chave e valor. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../system/smartptr/) para gerenciar objetos deste tipo. |
| [KVPairIterator](./kvpairiterator/) | Iterador adaptador, envolve std::pair em KVPair esperado por [Dictionary](./dictionary/). |
| [LinkedList](./linkedlist/) | Declaração antecipada [LinkedList](./linkedlist/). |
| [LinkedListNode](./linkedlistnode/) | Nó de lista ligada. Implementa um wrapper sobre um iterador de std::list que está encapsulado na lista ligada. Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [List](./list/) | Declaração antecipada [List](./list/). |
| [ListExt](./listext/) | classe genérica [List](./list/) que implementa a interface [IListWrapper](../system.collections/ilistwrapper/). |
| [ListPtr](./listptr/) | Ponteiro [List](./list/) com operadores de acesso. Este tipo é um ponteiro para gerenciar a deleção de outro objeto. Deve ser alocado na pilha e passado para funções por valor ou por referência constante. |
| [Queue](./queue/) | Declaração antecipada da classe [Queue](./queue/). |
| [QueuePtr](./queueptr/) | Ponteiro [Queue](./queue/). Este tipo é um ponteiro para gerenciar a deleção de outro objeto. Deve ser alocado na pilha e passado para funções por valor ou por referência constante. |
| [ReverseEnumerator](./reverseenumerator/) | Enumerador que itera em ordem reversa pelo contêiner. Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [SimpleEnumerator](./simpleenumerator/) | Classe iteradora para contêineres simples que armazenam elementos diretamente usando as funções rbegin() e rend(). Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [SortedDictionary](./sorteddictionary/) | Declaração antecipada do tipo dicionário ordenado. |
| [SortedDictionaryPtr](./sorteddictionaryptr/) | Ponteiro de dicionário ordenado com operadores de acesso. Este tipo é um ponteiro para gerenciar a deleção de outro objeto. Deve ser alocado na pilha e passado para funções por valor ou por referência constante. |
| [SortedList](./sortedlist/) | Lista ordenada que encapsula a estrutura FlatMap. Objetos desta classe só devem ser alocados usando a função [System::MakeObject()](../system/makeobject/). Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro ao passá-la para funções como argumento. |
| [SortedListHelper](./sortedlisthelper/) | Esta classe auxiliar é usada para mascarar as funções virtuais get_Keys e get_Values que vêm da interface [IDictionary](./idictionary/) e substituí-las por funções com tipo de retorno diferente. |
| [SortedSet](./sortedset/) | Declaração antecipada da classe [SortedSet](./sortedset/). |
| [SortedSetPtr](./sortedsetptr/) | Ponteiro para manter referências [SortedSet](./sortedset/). Este tipo é um ponteiro para gerenciar a deleção de outro objeto. Deve ser alocado na pilha e passado para funções por valor ou por referência constante. |
| [Stack](./stack/) | Declaração antecipada da classe [Stack](./stack/). |
| [StackPtr](./stackptr/) | Ponteiro [Stack](./stack/). Este tipo é um ponteiro para gerenciar a deleção de outro objeto. Deve ser alocado na pilha e passado para funções por valor ou por referência constante. |
| [ValueIterator](./valueiterator/) | Iterador [Dictionary](./dictionary/) que fornece acesso ao valor. |

## Estruturas

| Estrutura | Descrição |
| --- | --- |
| [ComparerAdapter](./compareradapter/) | Adaptador para usar [IComparer](./icomparer/) em ambiente STL. Usa [IComparer](./icomparer/) se definido; caso contrário, usa o operador < (se disponível) ou retorna false (se não). |
| [DictionaryHashSelector](./dictionaryhashselector/) | Seletor de função hash para a classe [Dictionary](./dictionary/). Esta implementação usa hash STL caso nenhuma alternativa seja fornecida. |
| [EqualityComparerAdapter](./equalitycompareradapter/) | Adaptador que possibilita usar [IEqualityComparer](./iequalitycomparer/) com coleções e algoritmos estilo STL. Usa [IEqualityComparer](./iequalitycomparer/) se definido. Caso não esteja definido, usa o operador ==, [Object::Equals](../system/object/equals/) ou T::Equals, o que estiver disponível. |
| [EqualityComparerHashAdapter](./equalitycomparerhashadapter/) | Adaptador para usar [IEqualityComparer](./iequalitycomparer/) para hashing. Usa objeto comparador, se definido; caso contrário, usa o método de hash disponível selecionado usando a struct [DictionaryHashSelector](./dictionaryhashselector/). |

## Funções

| Função | Descrição |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)(const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | Compara dois pares chave-valor usando a semântica 'equals'. Usa o operador == ou o método EqualsTo para ambas as chaves e valores, conforme definido. |
| **bool** [operator!=](./operator_not_equal/)(const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | Compara dois pares chave-valor usando a semântica inversa de 'equals'. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | Insere dados no fluxo usando codificação UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | Insere dados no fluxo. |

## Tipos

| Typedef | Descrição |
| --- | --- |
| [KeyNotFoundException](./keynotfoundexception/) |  |