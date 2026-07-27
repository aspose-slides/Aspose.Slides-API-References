---
title: CompareInfo
second_title: Referência da API Aspose.Slides para C++
description: "Realiza comparação de strings sensível à cultura. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 40
url: /pt/system.globalization/compareinfo/
---
## CompareInfo classe

Realiza comparação de strings sensível à cultura. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class CompareInfo : public virtual System::Object
```

## Métodos

| Method | Description |
| --- | --- |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Compara strings. Não implementado. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Compara strings. Somente os modos Ordinal e OrdinalIgnoreCase são suportados. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int) const | Compara uma seção de uma string com uma seção de outra string. Não implementado. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Compara a seção final de uma string com a seção final de outra string usando métodos de comparação de strings. Não implementado. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int) const | Compara a seção final de uma string com a seção final de outra string. Não implementado. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Compara uma seção de uma string com uma seção de outra string usando métodos de comparação de strings. Não implementado. |
| [CompareInfo](./compareinfo/)(const [CompareInfo](./)\&) | informação RTTI. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| int [get_LCID](./get_lcid/)() const | Obtém o LCID da cultura associada ao comparador. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | Obtém o nome da cultura associada ao comparador. |
| [SortVersionPtr](../sortversionptr/) [get_Version](./get_version/)() const | Obtém informações sobre a versão de ordenação. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | Obtém [CompareInfo](./) associado à cultura especificada e usando métodos de comparação de strings no assembly especificado. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | Obtém [CompareInfo](./) associado à cultura especificada e usando métodos de comparação de strings no assembly especificado. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int) | Obtém [CompareInfo](./) associado à cultura especificada. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&) | Obtém [CompareInfo](./) associado à cultura especificada. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual int [GetHashCode](./gethashcode/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Obtém o código hash da string baseado nas opções de comparação especificadas. |
| int [GetHashCode](./gethashcode/)() const override | Análogo do método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hashing de objetos personalizados. |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Obtém o objeto [SortKey](../sortkey/) para a string especificada usando as opções de comparação especificadas. |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&) const | Obtém o objeto [SortKey](../sortkey/) para a string especificada. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | Procura por substring. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Procura por substring. Somente o modo Ordinal é suportado. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Procura por substring. Somente o modo Ordinal é suportado. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | Procura pelo caractere especificado. Somente o modo Ordinal é suportado. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | Procura por substring. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t) const | Procura pelo caractere especificado. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Procura por substring. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | Procura pelo caractere especificado. Somente o modo Ordinal é suportado. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | Procura pelo caractere especificado. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int) const | Procura pelo caractere especificado. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Procura por substring. Somente o modo Ordinal é suportado. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | Procura pelo caractere especificado. Somente o modo Ordinal é suportado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Verifica se a string especificada começa com o prefixo especificado usando as opções de comparação especificadas. |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Verifica se a string especificada começa com o prefixo especificado. |
| static **bool** [IsSortable](./issortable/)(char16_t) | Verifica se um caractere especificado é ordenável. |
| static **bool** [IsSortable](./issortable/)(const [String](../../system/string/)\&) | Verifica se uma string especificada é ordenável. |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Verifica se a string especificada termina com o sufixo especificado usando as opções de comparação especificadas. |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Verifica se a string especificada termina com o sufixo especificado. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Busca a última ocorrência da substring especificada. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Busca a última ocorrência da substring especificada usando as opções de comparação especificadas. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | Busca a última ocorrência do caractere especificado usando as opções de comparação especificadas. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | Busca a última ocorrência da string especificada. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Busca a última ocorrência da string especificada usando as opções de comparação especificadas. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | Busca a última ocorrência do caractere especificado usando as opções de comparação especificadas. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | Busca a última ocorrência da string especificada. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int) const | Busca a última ocorrência do caractere especificado. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Busca a última ocorrência da string especificada usando as opções de comparação especificadas. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | Busca a última ocorrência do caractere especificado usando as opções de comparação especificadas. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t) const | Busca a última ocorrência do caractere especificado. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | Busca a última ocorrência do caractere especificado. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
| [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| [CompareInfo](./)\& [operator=](./operator_equal/)(const [CompareInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Análogo do método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja também

* Classe [Object](../../system/object/)
* Espaço de nomes [System::Globalization](../)
* Biblioteca [Aspose.Slides](../../)