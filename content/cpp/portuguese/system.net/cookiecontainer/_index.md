---
title: CookieContainer
second_title: Referência da API Aspose.Slides para C++
description: "Fornece um contêiner para as instâncias da classe CookieCollection. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 40
url: /pt/system.net/cookiecontainer/
---
## CookieContainer classe

Fornece um container para as instâncias da classe CookieCollection. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class CookieContainer : public System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Cookie](../cookie/)\>) | Adiciona um cookie à coleção. |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Cookie](../cookie/)\>, **bool**) | Adiciona um cookie à coleção. |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\>) | Copia cookies da coleção especificada para a atual. |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Cookie](../cookie/)\>) | Adiciona um cookie para o URI especificado. |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\>) | Copia cookies da coleção especificada para o URI especificado para a coleção atual. |
|  [CookieContainer](./cookiecontainer/)() | Constrói uma nova instância. |
|  [CookieContainer](./cookiecontainer/)(**int32_t**) | Constrói uma nova instância. |
|  [CookieContainer](./cookiecontainer/)(**int32_t**, **int32_t**, **int32_t**) | Constrói uma nova instância. |
| [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\> [CookieCutter](./cookiecutter/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/), [String](../../system/string/), **bool**) | Copia cookies do cabeçalho HTTP especificado para o URI especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| **int32_t** [get_Capacity](./get_capacity/)() | Obtém a capacidade da coleção. |
| **int32_t** [get_Count](./get_count/)() | Retorna o número de itens da coleção. |
| **int32_t** [get_MaxCookieSize](./get_maxcookiesize/)() | Obtém o tamanho máximo do cookie. |
| **int32_t** [get_PerDomainCapacity](./get_perdomaincapacity/)() | Obtém a capacidade da coleção por domínio. |
| [String](../../system/string/) [GetCookieHeader](./getcookieheader/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Retorna um cabeçalho HTTP que contém cookies associados ao URI especificado. |
| [String](../../system/string/) [GetCookieHeader](./getcookieheader/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/)\&) | Retorna um cabeçalho HTTP que contém cookies associados ao URI especificado. |
| [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\> [GetCookies](./getcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Retorna uma coleção de cookies que estão associados ao URI especificado. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\> [InternalGetCookies](./internalgetcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Retorna uma coleção de cookies que estão associados ao URI especificado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| **bool** [IsLocalDomain](./islocaldomain/)([String](../../system/string/)) | Verifica se o domínio especificado é localhost. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referências compartilhadas pelo valor especificado. |
| void [set_Capacity](./set_capacity/)(**int32_t**) | Define a capacidade da coleção. |
| void [set_MaxCookieSize](./set_maxcookiesize/)(**int32_t**) | Define o tamanho máximo do cookie. |
| void [set_PerDomainCapacity](./set_perdomaincapacity/)(**int32_t**) | Define a capacidade da coleção por domínio. |
| void [SetCookies](./setcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/)) | Copia cookies do cabeçalho especificado para a coleção e os associa ao URI especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhadas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [DefaultCookieLengthLimit](./defaultcookielengthlimit/) | O tamanho máximo do cookie. |
| static [DefaultCookieLimit](./defaultcookielimit/) | O número máximo de itens da coleção. |
| static [DefaultPerDomainCookieLimit](./defaultperdomaincookielimit/) | O número máximo de itens da coleção por domínio. |

## Veja Também

* Classe [Object](../../system/object/)
* Espaço de nomes [System::Net](../)
* Biblioteca [Aspose.Slides](../../)