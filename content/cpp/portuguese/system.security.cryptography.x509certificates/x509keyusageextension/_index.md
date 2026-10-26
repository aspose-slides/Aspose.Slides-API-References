---
title: X509KeyUsageExtension
second_title: Referência da API Aspose.Slides para C++
description: "Objeto de extensão para manter informações extras sobre o uso de uma chave. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 196
url: /pt/system.security.cryptography.x509certificates/x509keyusageextension/
---
## X509KeyUsageExtension classe

Objeto de extensão para armazenar informações extras sobre o uso de uma chave. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class X509KeyUsageExtension : public System::Security::Cryptography::X509Certificates::X509Extension
```

## Métodos

| Método | Descrição |
| --- | --- |
|  [AsnEncodedData](../../system.security.cryptography/asnencodeddata/asnencodeddata/)(const [SharedPtr](../../system/sharedptr/)\<[AsnEncodedData](../../system.security.cryptography/asnencodeddata/)\>\&) | Construtor de cópia. |
|  [AsnEncodedData](../../system.security.cryptography/asnencodeddata/asnencodeddata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Construtor. |
|  [AsnEncodedData](../../system.security.cryptography/asnencodeddata/asnencodeddata/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\>\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Construtor. |
|  [AsnEncodedData](../../system.security.cryptography/asnencodeddata/asnencodeddata/)(const [String](../../system/string/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Construtor. |
| void [CopyFrom](./copyfrom/)(const [SharedPtr](../../system/sharedptr/)\<[AsnEncodedData](../../system.security.cryptography/asnencodeddata/)\>\&) override | Copia os dados de extensão de outro objeto. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual [String](../../system/string/) [Format](../../system.security.cryptography/asnencodeddata/format/)(**bool**) const | Formata os dados em forma legível por humanos. |
| **bool** [get_Critical](../x509extension/get_critical/)() const | Verifica se a extensão é crítica. |
| [X509KeyUsageFlags](../x509keyusageflags/) [get_KeyUsages](./get_keyusages/)() | Obtém os usos da chave. |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\> [get_Oid](../../system.security.cryptography/asnencodeddata/get_oid/)() const | Obtém o identificador de objeto dos dados codificados. |
| [ByteArrayPtr](../../system/bytearrayptr/) [get_RawData](../../system.security.cryptography/asnencodeddata/get_rawdata/)() const | Obtém os dados codificados brutos. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico do método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita o hash de objetos customizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico do operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita a clonagem de tipos customizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_Critical](../x509extension/set_critical/)(**bool**) | Define se a extensão é crítica. |
| void [set_Oid](../../system.security.cryptography/asnencodeddata/set_oid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\>\&) | Define o identificador de objeto dos dados codificados. |
| void [set_RawData](../../system.security.cryptography/asnencodeddata/set_rawdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Define os dados codificados brutos. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como um ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico do método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos customizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
|  [X509Extension](../x509extension/x509extension/)(const [SharedPtr](../../system/sharedptr/)\<[AsnEncodedData](../../system.security.cryptography/asnencodeddata/)\>\&, **bool**) | Construtor. |
|  [X509Extension](../x509extension/x509extension/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\>\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, **bool**) | Construtor. |
|  [X509Extension](../x509extension/x509extension/)(const [String](../../system/string/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, **bool**) | Construtor. |
|  [X509KeyUsageExtension](./x509keyusageextension/)() | Construtor padrão. |
|  [X509KeyUsageExtension](./x509keyusageextension/)(const [SharedPtr](../../system/sharedptr/)\<[AsnEncodedData](../../system.security.cryptography/asnencodeddata/)\>\&, **bool**) | Construtor. |
|  [X509KeyUsageExtension](./x509keyusageextension/)([X509KeyUsageFlags](../x509keyusageflags/), **bool**) | Construtor. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [X509Extension](../x509extension/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Biblioteca [Aspose.Slides](../../)