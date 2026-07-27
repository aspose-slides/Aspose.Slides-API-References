---
title: Array
second_title: Referência da API Aspose.Slides para C++
description: "Classe que representa uma estrutura de dados de array. Os objetos desta classe devem ser alocados apenas usando as funções System::MakeArray() e System::MakeObject(). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-la a funções como argumento."
type: docs
weight: 14
url: /pt/system/array/
---
## Classe Array

Classe que representa uma estrutura de dados de array. Objetos desta classe devem ser alocados apenas usando as funções [System::MakeArray()](../makearray/) e [System::MakeObject()](../makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros em tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../smartptr/) e use esse ponteiro para passá-lo às funções como argumento.

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo dos elementos de um array |

## Métodos

| Método | Descrição |
| --- | --- |
| void [Add](./add/)(const T\&) override | Não suportado porque o array representado pelo objeto atual é somente leitura. |
| [Array](./array/)() | Constrói um array vazio. |
| [Array](./array/)(int, const T\&) | Construtor de preenchimento. |
| [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | Construtor de preenchimento. |
| [Array](./array/)(int, const T) | Construtor de preenchimento. |
| [Array](./array/)(**vector_t**\&&) | Construtor de movimento. |
| [Array](./array/)(const **vector_t**\&) | Construtor de cópia. |
| [Array](./array/)(const std::vector\<Q\>\&) | Constrói um objeto [Array](./) e preenche-lo com valores copiados de um objeto std::vector cujo tipo de valores é o mesmo que **T**, mas diferente de **UnderlyingType**. |
| [Array](./array/)(std::vector\<Q\>\&&) | Constrói um objeto [Array](./) e preenche-lo com valores movidos de um objeto std::vector cujo tipo de valores é o mesmo que **T**, mas diferente de **UnderlyingType**. |
| [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | Constrói um objeto [Array](./) e preenche-lo com valores da lista de inicialização especificada contendo elementos do tipo **UnderlyingType**. |
| [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>\&) | Constrói um objeto [Array](./) e preenche-lo com valores do array especificado contendo elementos do tipo **UnderlyingType**. |
| [Array](./array/)(std::initializer_list\<**bool**\>, int) | Constrói um objeto [Array](./) e preenche-lo com valores da lista de inicialização especificada contendo elementos do tipo bool. |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | Converte o array para uma coleção somente leitura. |
| [iterator](./iterator/) [begin](./begin/)() | Retorna um iterador para o primeiro elemento do contêiner. Se o contêiner estiver vazio, o iterador retornado será igual a [end()](./end/). |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Retorna um iterador para o primeiro elemento do contêiner qualificado como const. Se o contêiner estiver vazio, o iterador retornado será igual a [end()](./end/). |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T\&) | Executa busca binária no array ordenado. |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y\&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | NÃO IMPLEMENTADO. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | Retorna um iterador para o primeiro elemento qualificado como const do contêiner. Se o contêiner estiver vazio, o iterador retornado será igual a [cend()](./cend/). |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | Retorna um iterador para o elemento que segue o último elemento do contêiner. Este elemento atua como um placeholder; tentar acessá-lo resulta em comportamento indefinido. |
| void [Clear](./clear/)() override | Não suportado porque o array representado pelo objeto atual é somente leitura. |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Substitui **count** valores a partir do índice **startIndex** no array especificado por valores padrão. |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | Clona o array. |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Copia um intervalo de elementos de um [System.Array](./) a partir da origem especificada. |
| **bool** [Contains](./contains/)(const T\&) const override | Determina se o item especificado está no array. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | Constrói um novo objeto [Array](./) e preenche-lo com elementos do array especificado convertidos para o tipo **OutputType** usando o delegate conversor especificado. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)>) | Constrói um novo objeto [Array](./) e preenche-lo com elementos do array especificado convertidos para o tipo **OutputType** usando o objeto de função conversora especificado. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Copia o número especificado de elementos do array de origem para o array de destino. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Copia o número especificado de elementos da visualização de array de origem para o array de destino. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | Copia o número especificado de elementos do array de origem para a visualização de array de destino. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | Copia o número especificado de elementos da visualização de array de origem para a visualização de array de destino. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Copia o número especificado de elementos do array de origem na pilha para o array de destino. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | Copia o número especificado de elementos do array de origem para o array de destino na pilha. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | Copia o número especificado de elementos do array de origem na pilha para o array de destino na pilha. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Copia um número especificado de elementos do array de origem iniciando no índice especificado para a posição especificada no array de destino. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Copia um número especificado de elementos da visualização de array de origem iniciando no índice especificado para a posição especificada no array de destino. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Copia um número especificado de elementos do array de origem iniciando no índice especificado para a posição especificada na visualização de array de destino. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Copia um número especificado de elementos da visualização de array de origem iniciando no índice especificado para a posição especificada na visualização de array de destino. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Copia um número especificado de elementos do array de origem na pilha iniciando no índice especificado para a posição especificada no array de destino. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | Copia um número especificado de elementos do array de origem iniciando no índice especificado para a posição especificada no array de destino na pilha. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Copia um número especificado de elementos do array de origem na pilha iniciando no índice especificado para a posição especificada no array de destino na pilha. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Copia um número especificado de elementos da visualização de array de origem iniciando no índice especificado para a posição especificada no array de destino na pilha. |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | Copia todos os elementos do array atual para o array de destino especificado. Os elementos são inseridos no array de destino a partir do índice especificado pelo argumento arrayIndex. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | Copia todos os elementos do array atual para o array de destino especificado. Os elementos são inseridos no array de destino a partir do índice especificado pelo argumento dstIndex. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | Copia todos os elementos do array atual para a visualização de array de destino especificada. Os elementos são inseridos na visualização de array de destino a partir do índice especificado pelo argumento dstIndex. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Copia um número especificado de elementos do array atual iniciando na posição especificada para o array de destino especificado. Os elementos são inseridos no array de destino a partir do índice especificado pelo argumento dstIndex. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Copia um número especificado de elementos do array atual iniciando na posição especificada para a visualização de array de destino especificada. Os elementos são inseridos na visualização de array de destino a partir do índice especificado pelo argumento dstIndex. |
| int [Count](./count/)() const | Retorna um número que representa o total de todos os elementos em todas as dimensões do array. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Retorna um iterador reverso para o primeiro elemento do contêiner invertido. Ele corresponde ao último elemento do contêiner não invertido. Se o contêiner estiver vazio, o iterador retornado é igual a [crend()](./crend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Retorna um iterador reverso para o elemento que segue o último elemento do contêiner invertido. Ele corresponde ao elemento que precede o primeiro elemento do contêiner não invertido. Este elemento atua como um placeholder, tentar acessá-lo resulta em comportamento indefinido. |
| **vector_t**\& [data](./data/)() | Retorna uma referência à estrutura de dados interna usada para armazenar os elementos do array. |
| const **vector_t**\& [data](./data/)() const | Retorna uma referência constante à estrutura de dados interna usada para armazenar os elementos do array. |
| vector_t::pointer [data_ptr](./data_ptr/)() | Retorna um ponteiro bruto para o início do buffer de memória onde os elementos do array são armazenados. |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | Retorna um ponteiro bruto constante para o início do buffer de memória onde os elementos do array são armazenados. |
| [iterator](./iterator/) [end](./end/)() | Retorna um iterador para o elemento que segue o último elemento do contêiner. Este elemento atua como um placeholder; tentar acessá-lo resulta em comportamento indefinido. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Retorna um iterador para o elemento que segue o último elemento do contêiner qualificado como const. Este elemento atua como um placeholder; tentar acessá-lo resulta em comportamento indefinido. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | Determina se o objeto [Array](./) especificado contém um elemento que satisfaça os requisitos do predicado especificado. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Procura o primeiro elemento no array especificado que satisfaça as condições do predicado especificado. |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Recupera todos os elementos que correspondem às condições definidas pelo predicado especificado. |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Procura o primeiro elemento no array especificado que satisfaça as condições do predicado especificado. |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | Executa a ação especificada em cada elemento do array especificado. |
| int [get_Count](./get_count/)() const override | Retorna o tamanho do array. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Verifica se a coleção tem tamanho fixo. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | Indica se o array é somente leitura. |
| **int32_t** [get_Length](./get_length/)() const override | Retorna um inteiro de 32 bits que representa o número total de todos os elementos em todas as dimensões do array. |
| **int64_t** [get_LongLength](./get_longlength/)() const | Retorna um inteiro de 64 bits que representa o número total de todos os elementos em todas as dimensões do array. |
| **int32_t** [get_Rank](./get_rank/)() const | NÃO IMPLEMENTADO. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Obtém o objeto através do qual a coleção está sendo sincronizada. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | Retorna um ponteiro para o objeto **Enumerator** que fornece a interface IEnumerator aos elementos do array representado pelo objeto atual. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogia do método C# [Object.GetHashCode()](../object/gethashcode/). Permite hash de objetos personalizados. |
| int [GetLength](./getlength/)(int) | Retorna o número de elementos na dimensão especificada. |
| **int64_t** [GetLongLength](./getlonglength/)(int) | Retorna o número de elementos na dimensão especificada como inteiro de 64 bits. |
| int [GetLowerBound](./getlowerbound/)(int) const | Retorna o limite inferior da dimensão especificada. |
| size_t [GetSizeTLength](./getsizetlength/)() const | Retorna uma variável std::size_t que representa o número total de todos os elementos em todas as dimensões do array. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Obtém o tipo real do objeto. Analogia da chamada C# [System.Object.GetType()](../object/gettype/). |
| int [GetUpperBound](./getupperbound/)(int) | Retorna o limite superior da dimensão especificada. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | Construtor padrão. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Construtor de cópia. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Construtor de movimentação. |
| T [idx_get](./idx_get/)(int) const override | Retorna o item no índice especificado. |
| void [idx_set](./idx_set/)(int, T) override | Define o valor especificado como o item do array no índice especificado. |
| int [IndexOf](./indexof/)(const T\&) const override | Determina o índice da primeira ocorrência do item especificado no array. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Determina o índice da primeira ocorrência do item especificado no array. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Determina o índice da primeira ocorrência do item especificado no array, começando a partir do índice especificado. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Determina o índice da primeira ocorrência do item especificado em um intervalo de itens do array definido pelo índice inicial e pelo número de elementos no intervalo. |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | Preenche o array representado pelo objeto atual com os valores do array especificado. |
| void [Initialize](./initialize/)() | Preenche o array com os objetos de tipo **T** construídos por padrão. |
| void [Insert](./insert/)(int, const T\&) override | Não suportado porque o array representado pelo objeto atual é somente leitura. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogia do operador 'is' do C#. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Determina o índice da última ocorrência do item especificado em um intervalo de itens do array definido pelo índice inicial e pelo número de elementos no intervalo. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Determina o índice da última ocorrência do item especificado no array, começando a partir do índice especificado. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Determina o índice da última ocorrência do item especificado no array. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | Aplica uma função acumuladora sobre uma sequência. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Determina se todos os elementos de uma sequência satisfazem uma condição. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Determina se uma sequência contém algum elemento. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Determina se existe algum elemento em uma sequência ou se ele satisfaz uma condição. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Computa a média de uma sequência de valores numéricos. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<T, ResultType\>\&) | Computa a média de uma sequência de valores obtidos ao invocar uma função de transformação em cada elemento da sequência de entrada. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Converte os elementos para o tipo especificado. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Concatena duas sequências. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Determina se uma sequência contém um valor especificado. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Retorna o número de elementos na sequência (calculado por contagem direta). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | Retorna o número de elementos na sequência que satisfazem a condição especificada. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Retorna o elemento em um índice especificado em uma sequência. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Retorna o elemento em um índice especificado em uma sequência. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Retorna o primeiro elemento de uma sequência. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | Retorna o primeiro elemento de uma sequência que satisfaz a condição especificada. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Retorna o primeiro elemento de uma sequência, ou um valor padrão se a sequência estiver vazia. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Retorna o primeiro elemento da sequência que satisfaz uma condição ou um valor padrão se nenhum elemento for encontrado. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | Agrupa os elementos de uma sequência. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | Agrupa os elementos de uma sequência. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Retorna o último elemento de uma sequência. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Retorna o último elemento de uma sequência, ou um valor padrão se a sequência estiver vazia. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | Invoca uma função de transformação em cada elemento de uma sequência genérica e retorna o valor máximo resultante. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | Invoca uma função de transformação em cada elemento de uma sequência genérica e retorna o valor mínimo resultante. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtra os elementos da sequência com base no tipo especificado. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | Ordena os elementos de uma sequência em ordem ascendente de acordo com os valores de chave selecionados por keySelector. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | Ordena os elementos de uma sequência em ordem descendente de acordo com os valores de chave selecionados por keySelector. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Inverte a ordem dos elementos em uma sequência. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | Transforma os elementos de uma sequência. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | Transforma cada elemento de uma sequência em uma nova forma incorporando o índice do elemento. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projeta cada elemento de uma sequência e combina as sequências resultantes em uma única sequência. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Ignora um número especificado de elementos contíguos do início de uma sequência e retorna o restante. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Retorna um número especificado de elementos contíguos do início de uma sequência. |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Cria um array a partir de uma sequência. |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Cria um List<T> a partir de uma sequência. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtra uma sequência com base no predicado especificado. |
| void [Lock](../object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../lockcontext/). |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | Encontra o maior elemento no array usando [operator<()](../operator_less/) para comparar os elementos. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogia do método C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permite clonar tipos personalizados. |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | Encontra o menor elemento no array usando [operator<()](../operator_less/) para comparar os elementos. |
|  [Object](../object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../object/object/)([Object](../object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Operador de atribuição por movimentação. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Operador de atribuição por movimentação. |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | Retorna um item no índice especificado. |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | Retorna um item no índice especificado. |
| void * [raw_data_ptr](./raw_data_ptr/)() override | Retorna um ponteiro para o primeiro elemento de um array de dimensão única. Para arrays multidimensionais, o resultado é indefinido. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Retorna um iterador reverso para o primeiro elemento do contêiner invertido. Ele corresponde ao último elemento do contêiner não invertido. Se o contêiner estiver vazio, o iterador retornado é igual a [rend()](./rend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Retorna um iterador reverso para o primeiro elemento do contêiner invertido. Corresponde ao último elemento do contêiner não invertido. Se o contêiner estiver vazio, o iterador retornado é igual a [rend()](./rend/). |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo de valor com nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Especialização de [Object::ReferenceEquals](../object/referenceequals/) para o caso de strings. |
| **bool** [Remove](./remove/)(const T\&) override | Não suportado porque o array representado pelo objeto atual é somente leitura. |
| void [RemoveAt](./removeat/)(int) override | Não suportado porque o array representado pelo objeto atual é somente leitura. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Retorna um iterador reverso para o elemento que segue o último elemento do contêiner invertido. Corresponde ao elemento que precede o primeiro elemento do contêiner não invertido. Este elemento serve como placeholder; tentar acessá-lo resulta em comportamento indefinido. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Retorna um iterador reverso para o elemento que segue o último elemento do contêiner invertido. Corresponde ao elemento que precede o primeiro elemento do contêiner não invertido. Este elemento serve como placeholder; tentar acessá-lo resulta em comportamento indefinido. |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int) | Altera o tamanho do array especificado para o valor especificado ou cria um novo array com o tamanho especificado. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Inverte os elementos no array especificado. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Inverte um intervalo de elementos no array especificado. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Faz o array tratar os ponteiros armazenados como fracos (se aplicável). |
| void [SetValue](./setvalue/)(const T\&, int) | Define o valor do elemento no índice especificado. |
| int [SharedCount](../object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Ordena os elementos no array especificado usando o comparador padrão. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Ordena um intervalo de elementos no array especificado usando o comparador padrão. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | Ordena os elementos no array especificado usando o comparador especificado. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Y\>\>\&) | NÃO IMPLEMENTADO. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [System::Comparison](../comparison/)\<T\>\&) | Ordena os elementos no array especificado usando a comparação especificada. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&) | Ordena dois arrays, um contendo chaves e o outro — itens correspondentes, com base nos valores do array que contém as chaves, cujos elementos são comparados usando o operador <. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&, int, int) | Ordena dois arrays, um contendo chaves e o outro — itens correspondentes, com base nos valores do array que contém as chaves, cujos elementos são comparados usando o comparador padrão. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analógico do método C# [Object.ToString()](../object/tostring/). Permite converter objetos personalizados em string. |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Determina se todos os elementos no array especificado satisfazem as condições definidas pelo predicado especificado. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa a construção C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementa a liberação da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtém a implementação do iterador begin const para o contêiner atual. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtém a implementação do iterador begin para o contêiner atual. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtém a implementação do iterador end const para o contêiner atual. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtém a implementação do iterador end para o contêiner atual. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Destrutor. |
| virtual  [~Object](../object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Tipos Definidos

| Typedef | Descrição |
| --- | --- |
| [ValueType](./valuetype/) | Alias para o tipo dos elementos do array. |
| [UnderlyingType](./underlyingtype/) | Alias para o tipo usado para representar cada elemento do array. |
| [EnumerablePtr](./enumerableptr/) | Um alias para o tipo de ponteiro compartilhado que aponta para um objeto IEnumerable contendo elementos do tipo **T**. |
| [EnumeratorPtr](./enumeratorptr/) | Um alias para o tipo de ponteiro compartilhado que aponta para um objeto IEnumerator contendo elementos do tipo **T**. |
| [iterator](./iterator/) | Tipo de iterador. |
| [const_iterator](./const_iterator/) | Tipo de iterador const. |
| [reverse_iterator](./reverse_iterator/) | Tipo de iterador reverso. |
| [const_reverse_iterator](./const_reverse_iterator/) | Tipo de iterador reverso const. |

## Observações



```cpp
#include <system/array.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<Array<int32_t>> &arrayPtr)
{
  for (auto item: arrayPtr)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Criar e preencher o array.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // Imprimir os itens do array.
  Print(arrayPtr);

  // Ordenar os itens do array em ordem crescente.
  Array<int32_t>::Sort(arrayPtr);

  // Imprimir os itens do array.
  Print(arrayPtr);

  // Imprimir a contagem dos itens do array.
  std::cout << arrayPtr->get_Length() << std::endl;

  // Imprimir o índice do item que é igual a 4.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // Redimensionar o array.
  Array<int32_t>::Resize(arrayPtr, 3);

  // Imprimir os itens do array.
  Print(arrayPtr);

  return 0;
}
/*
Este exemplo de código produz a seguinte saída:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## Veja Também

* Classe [ArrayBase](../arraybase/)
* Classe [IList](../../system.collections.generic/ilist/)
* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)