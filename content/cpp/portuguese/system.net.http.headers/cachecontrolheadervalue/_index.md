---
title: CacheControlHeaderValue
second_title: Referência da API Aspose.Slides para C++
description: "Representa um valor do cabeçalho 'Cache-Control'. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 14
url: /pt/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue classe

Representa um valor do cabeçalho 'Cache-Control'. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo para funções como argumento.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## Métodos

| Método | Descrição |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | Constrói uma nova instância. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para fins internos. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | Retorna a coleção de tokens de extensão de cache. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | Obtém o valor máximo de idade em segundos que determina o período durante o qual o cliente aceitará uma resposta. |
| **bool** [get_MaxStale](./get_maxstale/)() | Obtém o valor que determina se o cliente aceitará respostas expiradas. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | Obtém o valor em segundos que determina o período durante o qual o cliente aceitará respostas expiradas. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | Obtém o valor que determina a vida útil de frescor. |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | Obtém o valor que determina se o servidor requer revalidação de uma entrada de cache quando esta se torna obsoleta. |
| **bool** [get_NoCache](./get_nocache/)() | Obtém o valor que determina se o cliente aceitará uma resposta em cache. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | Obtém a coleção de nomes de campos na diretiva 'no-cache' do cabeçalho 'Cache-Control'. |
| **bool** [get_NoStore](./get_nostore/)() | Obtém o valor que determina se um cache não deve armazenar qualquer parte de uma requisição ou resposta HTTP. |
| **bool** [get_NoTransform](./get_notransform/)() | Obtém o valor que determina se um cache ou proxy não deve alterar qualquer parte do corpo da entidade. |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | Obtém o valor que determina se o cliente deve usar apenas entradas em cache. |
| **bool** [get_Private](./get_private/)() | Obtém o valor que determina se a mensagem de resposta HTTP ou sua parte destina-se a um único usuário e não deve ser armazenada em cache compartilhado. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | Obtém a coleção de nomes de campos na diretiva 'private' do cabeçalho 'Cache-Control'. |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | Obtém o valor que determina se o servidor requer revalidação de uma entrada de cache quando esta se torna obsoleta para caches de agentes de usuário compartilhados. |
| **bool** [get_Public](./get_public/)() | Obtém o valor que determina se uma resposta HTTP pode ser armazenada em qualquer cache. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | Obtém o valor máximo de idade compartilhado em segundos que sobrescreve a diretiva 'max-age' no cabeçalho 'Cache-Control' ou o cabeçalho 'Expires' para um cache compartilhado. |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Converte uma string fornecida a partir do índice especificado para uma instância da classe [CacheControlHeaderValue](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analogo do método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite a hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogo da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogo do operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Converte uma string fornecida para uma instância da classe [CacheControlHeaderValue](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Define o valor máximo de idade em segundos que determina o período durante o qual o cliente aceitará uma resposta. |
| void [set_MaxStale](./set_maxstale/)(**bool**) | Define o valor que determina se o cliente aceitará respostas expiradas. |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Define o valor em segundos que determina o período durante o qual o cliente aceitará respostas expiradas. |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Define o valor que determina a vida útil de frescor. |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | Define o valor que determina se o servidor requer revalidação de uma entrada de cache quando esta se torna obsoleta. |
| void [set_NoCache](./set_nocache/)(**bool**) | Define o valor que determina se o cliente aceitará uma resposta em cache. |
| void [set_NoStore](./set_nostore/)(**bool**) | Define o valor que determina se um cache não deve armazenar qualquer parte de uma requisição ou resposta HTTP. |
| void [set_NoTransform](./set_notransform/)(**bool**) | Define o valor que determina se um cache ou proxy não deve alterar qualquer parte do corpo da entidade. |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | Define o valor que determina se o cliente deve usar apenas entradas em cache. |
| void [set_Private](./set_private/)(**bool**) | Define o valor que determina se a mensagem de resposta HTTP ou sua parte destina-se a um único usuário e não deve ser armazenada em cache compartilhado. |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | Define o valor que determina se o servidor requer revalidação de uma entrada de cache quando se torna obsoleta para caches de agentes de usuário compartilhados. |
| void [set_Public](./set_public/)(**bool**) | Define o valor que determina se uma resposta HTTP pode ser armazenada em qualquer cache. |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Define o valor máximo de idade compartilhado em segundos que sobrescreve a diretiva 'max-age' no cabeçalho 'Cache-Control' ou o cabeçalho 'Expires' para um cache compartilhado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analogo do método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Tenta converter uma string fornecida para uma instância da classe [CacheControlHeaderValue](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Biblioteca [Aspose.Slides](../../)