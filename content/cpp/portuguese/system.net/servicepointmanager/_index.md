---
title: ServicePointManager
second_title: Referência da API Aspose.Slides para C++
description: "Gerencia as fases do ciclo de vida (criação, manutenção e exclusão) das instâncias da classe ServicePoint. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie uma instância desse tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 430
url: /pt/system.net/servicepointmanager/
---
## ServicePointManager classe

Gerencia as fases do ciclo de vida (criação, manutenção e exclusão) das instâncias da classe [ServicePoint](../servicepoint/). Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie uma instância desse tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class ServicePointManager : public System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| static [System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\> [get_CertificatePolicy](./get_certificatepolicy/)() | Obtém uma política de certificado. |
| static **bool** [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | Obtém um valor que indica se o certificado deve ser verificado contra a lista de revogação da autoridade certificadora. |
| static **int32_t** [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | Obtém o número máximo de conexões simultâneas que são permitidas pelas instâncias da classe ServicePoint-class. |
| static **int32_t** [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | Obtém um tempo limite em milissegundos durante o qual uma resolução DNS é considerada válida. |
| static **bool** [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | Obtém um valor que indica se uma resolução DNS gira entre os endereços IP aplicáveis. |
| static [System::Net::Security::EncryptionPolicy](../../system.net.security/encryptionpolicy/) [get_EncryptionPolicy](./get_encryptionpolicy/)() | Retorna a política de criptografia usada pela instância atual. |
| static **bool** [get_Expect100Continue](./get_expect100continue/)() | Obtém um valor que indica se as instâncias da classe ServicePoint-class usam o comportamento 100-Continue. |
| static **int32_t** [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | Obtém o tempo máximo ocioso das instâncias da classe ServicePoint-class. |
| static **int32_t** [get_MaxServicePoints](./get_maxservicepoints/)() | Obtém o número máximo de instâncias da classe ServicePoint-class que podem ser gerenciadas pela instância atual. |
| static **bool** [get_ReusePort](./get_reuseport/)() | Obtém um valor que indica se os sockets de conexões de saída usam a opção 'SO_REUSE_UNICASTPORT'. |
| static [SecurityProtocolType](../securityprotocoltype/) [get_SecurityProtocol](./get_securityprotocol/)() | Obtém o tipo de protocolo de segurança usado pelas instâncias da classe ServicePoint-class que são gerenciadas pela instância atual. |
| static [Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/) [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | Obtém a função de retorno de chamada usada para validar um certificado de servidor. |
| static **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Obtém um valor que indica se as instâncias da classe ServicePoint-class usam o algoritmo Nagle. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoga ao método [Object.GetHashCode()](../../system/object/gethashcode/) do C#. Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analoga à chamada [System.Object.GetType()](../../system/object/gettype/) do C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analoga ao operador 'is' do C#. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoga ao método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) do C#. Permite a clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhado pelo valor especificado. |
| static void [set_CertificatePolicy](./set_certificatepolicy/)([System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\>) | Define uma política de certificado. |
| static void [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(**bool**) | Define um valor que indica se o certificado deve ser verificado contra a lista de revogação da autoridade certificadora. |
| static void [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(**int32_t**) | Define o número máximo de conexões simultâneas permitidas pelas instâncias da classe ServicePoint-class. |
| static void [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(**int32_t**) | Define um tempo limite em milissegundos durante o qual uma resolução DNS é considerada válida. |
| static void [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(**bool**) | Define um valor que indica se uma resolução DNS gira entre os endereços IP aplicáveis. |
| static void [set_Expect100Continue](./set_expect100continue/)(**bool**) | Define um valor que indica se as instâncias da classe ServicePoint-class usam o comportamento 100-Continue. |
| static void [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(**int32_t**) | Define o tempo máximo ocioso das instâncias da classe ServicePoint-class. |
| static void [set_MaxServicePoints](./set_maxservicepoints/)(**int32_t**) | Define o número máximo de instâncias da classe ServicePoint-class que podem ser gerenciadas pela instância atual. |
| static void [set_ReusePort](./set_reuseport/)(**bool**) | Define um valor que indica se os sockets de conexões de saída usam a opção 'SO_REUSE_UNICASTPORT'. |
| static void [set_SecurityProtocol](./set_securityprotocol/)([SecurityProtocolType](../securityprotocoltype/)) | Define o tipo de protocolo de segurança usado pelas instâncias da classe ServicePoint-class que são gerenciadas pela instância atual. |
| static void [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)([Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/)) | Define a função de retorno de chamada usada para validar um certificado de servidor. |
| static void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | Define um valor que indica se as instâncias da classe ServicePoint-class usam o algoritmo Nagle. |
| static void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | Define o valor que indica se a opção 'Keep-Alive' está habilitada. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhado. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoga ao método [Object.ToString()](../../system/object/tostring/) do C#. Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | O número padrão de conexões não persistentes. |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | O número padrão de conexões persistentes. |

## Veja Também

* Classe [Object](../../system/object/)
* Namespace [System::Net](../)
* Biblioteca [Aspose.Slides](../../)