---
title: DSACryptoServiceProvider
second_title: Referência da API Aspose.Slides para C++
description: "Algoritmo DSA em forma CSP. Objetos desta classe devem ser alocados somente usando a função System::MakeObject(). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo às funções como argumento."
type: docs
weight: 144
url: /pt/system.security.cryptography/dsacryptoserviceprovider/
---
## DSACryptoServiceProvider classe


[DSA](../dsa/) algoritmo em forma CSP. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo às funções como argumento.

```cpp
class DSACryptoServiceProvider : public System::Security::Cryptography::DSA,
                                 public System::Security::Cryptography::ICspAsymmetricAlgorithm
```

## Métodos

| Método | Descrição |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | Libera todos os recursos. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [Create](../dsa/create/)() | Cria a implementação padrão do algoritmo [DSA](../dsa/). |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [Create](../dsa/create/)(const [String](../../system/string/)\&) | Cria a implementação padrão do algoritmo [DSA](../dsa/). |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [Create](../dsa/create/)(**int32_t**) | Cria a implementação padrão do algoritmo [DSA](../dsa/) com o tamanho de chave especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [Create](../dsa/create/)(const [DSAParameters](../dsaparameters/)\&) | Cria a implementação padrão do algoritmo [DSA](../dsa/) com os parâmetros especificados. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [CreateFromXmlString](../dsa/createfromxmlstring/)(const [String](../../system/string/)\&) | Cria a implementação padrão do algoritmo [DSA](../dsa/) com os parâmetros codificados em XML. |
| [ByteArrayPtr](../../system/bytearrayptr/) [CreateSignature](./createsignature/)([ByteArrayPtr](../../system/bytearrayptr/)) override | Cria a assinatura [DSA](../dsa/) para os dados especificados. |
| void [Dispose](./dispose/)() override | Libera os dados associados ao objeto. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)() | Construtor. Usa parâmetros padrão. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(const [DSAParameters](../dsaparameters/)\&) | Construtor. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | Construtor. Não implementado. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(**int32_t**) | Construtor. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(**int32_t**, const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | Construtor. Não implementado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| [ByteArrayPtr](../../system/bytearrayptr/) [ExportCspBlob](./exportcspblob/)(**bool**) override | Exporta um blob com informações sobre a chave. Não implementado. |
| [DSAParameters](../dsaparameters/) [ExportParameters](./exportparameters/)(**bool**) override | Exporta parâmetros CSP. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| void [FromXmlString](../dsa/fromxmlstring/)([String](../../system/string/)) override | Inicializa o objeto usando parâmetros codificados em XML. |
| [SharedPtr](../../system/sharedptr/)\<[CspKeyContainerInfo](../cspkeycontainerinfo/)\> [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() override | Obtém um objeto [CspKeyContainerInfo](../cspkeycontainerinfo/). |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Verifica o algoritmo de troca de chave associado ao objeto. |
| **int32_t** [get_KeySize](./get_keysize/)() override | Obtém o tamanho da chave. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | Obtém um array dos tamanhos de chave permitidos. |
| **bool** [get_PersistKeyInCsp](./get_persistkeyincsp/)() const | Verifica se a chave está persistida no objeto CSP. |
| **bool** [get_PublicOnly](./get_publiconly/)() const | Verifica se apenas a chave pública está presente no objeto CSP. |
| [String](../../system/string/) [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Obtém o algoritmo de assinatura a ser usado. |
| static **bool** [get_UseMachineKeyStore](./get_usemachinekeystore/)() | Verifica se a chave persiste no armazenamento da máquina em vez do armazenamento do usuário. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| void [ImportCspBlob](./importcspblob/)([ByteArrayPtr](../../system/bytearrayptr/)) override | Importa um blob com informações sobre a chave. Não implementado. |
| void [ImportParameters](./importparameters/)([DSAParameters](../dsaparameters/)) override | Importa todos os parâmetros da estrutura de dados. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
| [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e habilita a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e habilita a cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | Define o tamanho da chave. |
| void [set_PersistKeyInCsp](./set_persistkeyincsp/)(**bool**) | Define se a chave está persistida no objeto CSP. |
| static void [set_UseMachineKeyStore](./set_usemachinekeystore/)(**bool**) | Define se a chave persiste no armazenamento da máquina em vez do armazenamento do usuário. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Calcula a assinatura do valor de entrada especificado. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Calcula a assinatura do valor de entrada especificado. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**) | Calcula a assinatura do valor de entrada especificado. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Calcula o valor hash do array de dados especificado usando o algoritmo de hash especificado e assina o resultado. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&) | Calcula o valor hash do array de dados especificado usando o algoritmo de hash especificado e assina o resultado. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Calcula o valor hash do fluxo binário especificado usando o algoritmo de hash especificado e assina o resultado. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | Calcula a assinatura do valor de entrada especificado. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| [String](../../system/string/) [ToXmlString](../dsa/toxmlstring/)(**bool**) override | Exporta todos os parâmetros em formato XML. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa a liberação da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Verifica a assinatura dos dados. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Verifica se a assinatura dos dados especificados é válida. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Verifica se a assinatura dos dados especificados é válida. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Verifica se a assinatura do fluxo binário especificado é válida. |
| **bool** [VerifyHash](./verifyhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Verifica a assinatura dos dados. |
| **bool** [VerifySignature](./verifysignature/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/)) override | Verifica a assinatura [DSA](../dsa/) para os dados especificados. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [DSA](../dsa/)
* Classe [ICspAsymmetricAlgorithm](../icspasymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Biblioteca [Aspose.Slides](../../)