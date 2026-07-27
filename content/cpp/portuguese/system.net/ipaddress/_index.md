---
title: IPAddress
second_title: Aspose.Slides para C++ Referência da API
description: "Representa o endereço IP. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject() function. Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 326
url: /pt/system.net/ipaddress/
---
## IPAddress classe

Representa o endereço IP. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class IPAddress : public System::Object
```

## Métodos

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() | Retorna a família de endereços. |
| **bool** [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | Retorna um valor que indica se o endereço é um endereço IPv4 e está mapeado para um endereço IPv6. |
| **bool** [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | Retorna um valor que indica se o endereço é um endereço IPv6 link-local. |
| **bool** [get_IsIPv6Multicast](./get_isipv6multicast/)() | Retorna um valor que indica se o endereço é um endereço multicast IPv6 global. |
| **bool** [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | Retorna um valor que indica se o endereço é um endereço IPv6 site-local. |
| **bool** [get_IsIPv6Teredo](./get_isipv6teredo/)() | Retorna um valor que indica se o endereço é um endereço IPv6 Teredo. |
| **int64_t** [get_ScopeId](./get_scopeid/)() | Obtém o identificador de escopo do endereço IPv6. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetAddressBytes](./getaddressbytes/)() | Retorna um array de bytes do endereço IP. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analoga ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita o hash de objetos personalizados. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | Retorna um ponteiro para a implementação. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analoga à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| static **int64_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int64_t**) | Converte a ordem de bytes do host especificada para a ordem de bytes de rede correspondente. |
| static **int32_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int32_t**) | Converte a ordem de bytes do host especificada para a ordem de bytes de rede correspondente. |
| static **int16_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int16_t**) | Converte a ordem de bytes do host especificada para a ordem de bytes de rede correspondente. |
|  [IPAddress](./ipaddress/)(**int64_t**) | Constrói uma nova instância. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int64_t**) | Constrói uma nova instância. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Constrói uma nova instância. |
|  [IPAddress](./ipaddress/)() | Constrói uma nova instância. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analoga ao operador C# 'is'. |
| static **bool** [IsLoopback](./isloopback/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>) | Retorna um valor que indica se o endereço especificado é um endereço de loopback. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv4](./maptoipv4/)() | Mapeia o endereço para o endereço IPv4. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv6](./maptoipv6/)() | Mapeia o endereço para o endereço IPv6. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoga ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita a clonagem de tipos personalizados. |
| static **int64_t** [NetworkToHostOrder](./networktohostorder/)(**int64_t**) | Converte a ordem de bytes de rede especificada para a ordem de bytes do host correspondente. |
| static **int32_t** [NetworkToHostOrder](./networktohostorder/)(**int32_t**) | Converte a ordem de bytes de rede especificada para a ordem de bytes do host correspondente. |
| static **int16_t** [NetworkToHostOrder](./networktohostorder/)(**int16_t**) | Converte a ordem de bytes de rede especificada para a ordem de bytes do host correspondente. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [Parse](./parse/)([String](../../system/string/)) | Converte uma string fornecida para uma instância da classe [IPAddress](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referências compartilhadas pelo valor especificado. |
| void [set_ScopeId](./set_scopeid/)(**int64_t**) | Define o identificador de escopo do endereço IPv6. |
| void [SetImpl](./setimpl/)([ImplPtr](./implptr/)) | Define um ponteiro para a implementação. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhadas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analoga ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>\&) | Tenta converter uma string fornecida para uma instância da classe [IPAddress](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referências fracas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referências fracas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Campos

| Field | Description |
| --- | --- |
| static [Any](./any/) | O endereço IPv4 que indica se o servidor deve escutar todas as interfaces de rede. |
| static [Broadcast](./broadcast/) | O endereço broadcast IPv4. |
| static [IPv6Any](./ipv6any/) | O endereço IPv6 que indica se o servidor deve escutar todas as interfaces de rede. |
| static [IPv6Loopback](./ipv6loopback/) | O endereço de loopback IPv6. |
| static [IPv6None](./ipv6none/) | O endereço IPv6 que indica se o servidor não deve escutar nenhuma interface de rede. |
| static [Loopback](./loopback/) | O endereço de loopback IPv4. |
| static [None](./none/) | O endereço IPv4 que indica se o servidor não deve escutar nenhuma interface de rede. |

## Definições de tipo

| Typedef | Description |
| --- | --- |
| [ImplPtr](./implptr/) | Um ponteiro para o tipo de implementação. |

## Veja Também

* Classe [Object](../../system/object/)
* Espaço de nomes [System::Net](../)
* Biblioteca [Aspose.Slides](../../)