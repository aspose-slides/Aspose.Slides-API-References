---
title: NameValueWithParametersHeaderValue
second_title: Referência da API Aspose.Slides para C++
description: "Representa um par chave/valor com parâmetros para usar em cabeçalhos. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 183
url: /pt/system.net.http.headers/namevaluewithparametersheadervalue/
---
## NameValueWithParametersHeaderValue class


Representa um par chave/valor com parâmetros para usar em cabeçalhos. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class NameValueWithParametersHeaderValue : public System::Net::Http::Headers::NameValueHeaderValue
```

## Métodos

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| static [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\> [Find](../namevalueheadervalue/find/)([System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\>, [String](../../system/string/)) | Encontra a instância da classe NameValueHeaderValue em uma coleção pelo nome especificado. |
| [String](../../system/string/) [get_Name](../namevalueheadervalue/get_name/)() | Retorna o nome da instância atual. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Parameters](./get_parameters/)() | Retorna parâmetros da instância atual. |
| [String](../../system/string/) [get_Value](../namevalueheadervalue/get_value/)() | Obtém um valor da instância atual. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analógico ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hash de objetos personalizados. |
| static **int32_t** [GetHashCode](../namevalueheadervalue/gethashcode/)([System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\>) | Retorna um código hash de todos os itens da coleção. |
| static **int32_t** [GetNameValueLength](../namevalueheadervalue/getnamevaluelength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\&) | Converte uma string passada a partir do índice especificado para uma instância da classe [NameValueHeaderValue](../namevalueheadervalue/). |
| static **int32_t** [GetNameValueLength](../namevalueheadervalue/getnamevaluelength/)([String](../../system/string/), **int32_t**, [HeaderFunc](../headerfunc/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>, [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\&) | Converte uma string passada a partir do índice especificado para uma instância da classe [NameValueHeaderValue](../namevalueheadervalue/). |
| static **int32_t** [GetNameValueListLength](../namevalueheadervalue/getnamevaluelistlength/)([String](../../system/string/), **int32_t**, char16_t, [System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\>) | Converte uma string passada a partir do índice especificado para a coleção de instâncias da classe NameValueHeaderValue e retorna o comprimento de uma subcadeia analisada. |
| static **int32_t** [GetNameValueWithParametersLength](./getnamevaluewithparameterslength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Converte uma string passada a partir do índice especificado para uma instância da classe [NameValueWithParametersHeaderValue](./). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| static **int32_t** [GetValueLength](../namevalueheadervalue/getvaluelength/)([String](../../system/string/), **int32_t**) | Retorna o comprimento de um valor a partir do índice especificado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita a clonagem de tipos personalizados. |
|  [NameValueHeaderValue](../namevalueheadervalue/namevalueheadervalue/)() | Constrói uma nova instância. |
|  [NameValueHeaderValue](../namevalueheadervalue/namevalueheadervalue/)([String](../../system/string/)) | Constrói uma nova instância. |
|  [NameValueHeaderValue](../namevalueheadervalue/namevalueheadervalue/)([String](../../system/string/), [String](../../system/string/)) | Constrói uma nova instância. |
|  [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)([String](../../system/string/)) | Constrói uma nova instância. |
|  [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)([String](../../system/string/), [String](../../system/string/)) | Constrói uma nova instância. |
|  [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)() | Constrói uma nova instância. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e habilita a construção de cópia em subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e habilita a construção de cópia em subclasses. |
| static [System::SharedPtr](../../system/sharedptr/)\<[NameValueWithParametersHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Converte uma string passada para uma instância da classe [NameValueWithParametersHeaderValue](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_Value](../namevalueheadervalue/set_value/)([String](../../system/string/)) | Define um valor da instância atual. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analógico ao método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados para string. |
| static void [ToString](../namevalueheadervalue/tostring/)([System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\>, char16_t, **bool**, [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>) | Retorna uma representação em string da coleção de instâncias da classe NameValueHeaderValue. |
| static [String](../../system/string/) [ToString](../namevalueheadervalue/tostring/)([System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\>, char16_t, **bool**) | Retorna uma representação em string da coleção de instâncias da classe NameValueHeaderValue. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[NameValueWithParametersHeaderValue](./)\>\&) | Tenta converter uma string passada para uma instância da classe [NameValueWithParametersHeaderValue](./). |
| static **bool** [TryParse](../namevalueheadervalue/tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\&) | Tenta converter uma string passada para uma instância da classe [NameValueHeaderValue](../namevalueheadervalue/). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa o construto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |
## Veja Também

* Classe [NameValueHeaderValue](../namevalueheadervalue/)
* Namespace [System::Net::Http::Headers](../)
* Biblioteca [Aspose.Slides](../../)