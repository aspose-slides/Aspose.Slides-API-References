---
title: ECDsaBotan
second_title: Referência da API Aspose.Slides for C++
description: "Algoritmo ECDsa na forma Botan. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 196
url: /pt/system.security.cryptography/ecdsabotan/
---
## ECDsaBotan classe


[ECDsa](../ecdsa/) algoritmo em forma Botan. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class ECDsaBotan : public System::Security::Cryptography::ECDsa
```

## Métodos

| Method | Description |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | Libera todos os recursos. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](../ecdsa/)\> [Create](../ecdsa/create/)() | Cria a implementação padrão do algoritmo ECDSA. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](../ecdsa/)\> [Create](../ecdsa/create/)(const [ECCurve](../eccurve/)\&) | Cria a implementação padrão do algoritmo ECDSA com chave recém-criada sobre a curva especificada. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](../ecdsa/)\> [Create](../ecdsa/create/)(const [ECParameters](../ecparameters/)\&) | Cria a implementação padrão do algoritmo ECDSA usando os parâmetros especificados. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](../ecdsa/)\> [Create](../ecdsa/create/)(const [String](../../system/string/)\&) | Cria a implementação especificada do algoritmo ECDSA. |
| void [Dispose](../asymmetricalgorithm/dispose/)() override | Libera recursos pertencentes ao objeto atual. |
| [ECDsaBotan](./ecdsabotan/)() | Construtor. Usa parâmetros padrão. |
| [ECDsaBotan](./ecdsabotan/)(const [ECParameters](../ecparameters/)\&) | Construtor. |
| [ECDsaBotan](./ecdsabotan/)(const [ECCurve](../eccurve/)\&) | Construtor. |
| [ECDsaBotan](./ecdsabotan/)(**int32_t**) | Construtor. |
| [ECDsaBotan](./ecdsabotan/)(const Botan::ECDSA_PublicKey\&) | Construtor. |
| [ECDsaBotan](./ecdsabotan/)(const Botan::ECDSA_PrivateKey\&) | Construtor. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| [ECParameters](../ecparameters/) [ExportExplicitParameters](./exportexplicitparameters/)(**bool**) override | Exporta parâmetros explícitos. |
| [ECParameters](../ecparameters/) [ExportParameters](./exportparameters/)(**bool**) override | Exporta parâmetros nomeados ou explícitos. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| void [FromXmlString](./fromxmlstring/)([String](../../system/string/)) override | Inicializa o objeto usando parâmetros codificados em XML. Não implementado. |
| void [FromXmlString](./fromxmlstring/)(const [String](../../system/string/)\&, [ECKeyXmlFormat](../eckeyxmlformat/)) | Inicializa o objeto usando parâmetros codificados em XML. Não implementado. |
| void [GenerateKey](./generatekey/)(const [ECCurve](../eccurve/)\&) override | Gera um novo par de chaves pública/privada para a curva especificada. |
| [HashAlgorithmName](../hashalgorithmname/) [get_HashAlgorithm](./get_hashalgorithm/)() const | Obtém o algoritmo de hash. |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](../ecdsa/get_keyexchangealgorithm/)() override | Obtém o algoritmo de troca de chaves a ser usado. |
| virtual **int32_t** [get_KeySize](../asymmetricalgorithm/get_keysize/)() | Obtém o tamanho da chave. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | Obtém um array de tamanhos de chave permitidos. |
| [String](../../system/string/) [get_SignatureAlgorithm](../ecdsa/get_signaturealgorithm/)() override | Obtém o algoritmo de assinatura a ser usado. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [ByteArrayPtr](../../system/bytearrayptr/) [HashData](./hashdata/)([ByteArrayPtr](../../system/bytearrayptr/), **int32_t**, **int32_t**, [HashAlgorithmName](../hashalgorithmname/)) override | Calcula o valor de hash do array de dados especificado usando o algoritmo de hash especificado. |
| [ByteArrayPtr](../../system/bytearrayptr/) [HashData](./hashdata/)([StreamPtr](../../system/streamptr/), [HashAlgorithmName](../hashalgorithmname/)) override | Calcula o valor de hash do fluxo binário especificado usando o algoritmo de hash especificado. |
| void [ImportParameters](./importparameters/)(const [ECParameters](../ecparameters/)\&) override | Importa todos os parâmetros da estrutura de dados. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_HashAlgorithm](./set_hashalgorithm/)(const [HashAlgorithmName](../hashalgorithmname/)\&) | Define o algoritmo de hash. |
| void [set_KeySize](./set_keysize/)(**int32_t**) override | Define o tamanho da chave. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Calcula o valor de hash do array de dados especificado e assina o resultado. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**) | Calcula o valor de hash do array de dados especificado e assina o resultado. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&) | Calcula o valor de hash do fluxo binário especificado e assina o resultado. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Calcula o valor de hash do array de dados especificado usando o algoritmo de hash especificado e assina o resultado. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&) | Calcula o valor de hash do array de dados especificado usando o algoritmo de hash especificado e assina o resultado. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Calcula o valor de hash do fluxo binário especificado usando o algoritmo de hash especificado e assina o resultado. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) override | Calcula a assinatura do valor de entrada especificado. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| [String](../../system/string/) [ToXmlString](./toxmlstring/)(**bool**) override | Exporta todos os parâmetros em formato XML. Não implementado. |
| [String](../../system/string/) [ToXmlString](./toxmlstring/)([ECKeyXmlFormat](../eckeyxmlformat/)) | Exporta todos os parâmetros em formato XML. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Verifica se a assinatura dos dados especificados é válida. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Verifica se a assinatura dos dados especificados é válida. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Verifica se a assinatura do fluxo binário especificado é válida. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Verifica se a assinatura dos dados especificados é válida. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Verifica se a assinatura dos dados especificados é válida. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Verifica se a assinatura do fluxo binário especificado é válida. |
| **bool** [VerifyHash](./verifyhash/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/)) override | Verifica a assinatura dos dados. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [ECDsa](../ecdsa/)
* Namespace [System::Security::Cryptography](../)
* Biblioteca [Aspose.Slides](../../)