---
title: ECDsa
second_title: Aspose.Slides para C++ Referência da API
description: "Classe base para implementações do algoritmo ECDsa. Objetos desta classe devem ser alocados somente usando a função System::MakeObject(). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 183
url: /pt/system.security.cryptography/ecdsa/
---
## ECDsa classe

Classe base para implementações do algoritmo [ECDsa](./). Objetos desta classe devem ser alocados somente usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class ECDsa : public System::Security::Cryptography::AsymmetricAlgorithm
```

## Métodos

| Método | Descrição |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | Libera todos os recursos. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](./)\> [Create](./create/)() | Cria a implementação padrão do algoritmo ECDSA. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](./)\> [Create](./create/)(const [ECCurve](../eccurve/)\&) | Cria a implementação padrão do algoritmo ECDSA com uma chave recém-criada sobre a curva especificada. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](./)\> [Create](./create/)(const [ECParameters](../ecparameters/)\&) | Cria a implementação padrão do algoritmo ECDSA usando os parâmetros especificados. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Cria a implementação especificada do algoritmo ECDSA. |
| void [Dispose](../asymmetricalgorithm/dispose/)() override | Libera os recursos possuídos pelo objeto atual. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora segundo a IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora segundo a IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual [ECParameters](../ecparameters/) [ExportExplicitParameters](./exportexplicitparameters/)(**bool**) | Exporta parâmetros explícitos. |
| virtual [ECParameters](../ecparameters/) [ExportParameters](./exportparameters/)(**bool**) | Exporta parâmetros nomeados ou explícitos. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| virtual void [FromXmlString](../asymmetricalgorithm/fromxmlstring/)([String](../../system/string/)) | Lê os parâmetros do algoritmo de uma string XML. |
| virtual void [GenerateKey](./generatekey/)(const [ECCurve](../eccurve/)\&) | Gera um novo par de chaves pública/privada para a curva especificada. |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Obtém o algoritmo de troca de chaves a ser usado. |
| virtual **int32_t** [get_KeySize](../asymmetricalgorithm/get_keysize/)() | Obtém o tamanho da chave. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | Obtém o array de tamanhos de chave permitidos. |
| [String](../../system/string/) [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Obtém o algoritmo de assinatura a ser usado. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método [Object.GetHashCode()](../../system/object/gethashcode/) do C#. Habilita o hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada [System.Object.GetType()](../../system/object/gettype/) do C#. |
| virtual void [ImportParameters](./importparameters/)(const [ECParameters](../ecparameters/)\&) | Importa todos os parâmetros da estrutura de dados. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador 'is' do C#. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) do C#. Habilita a clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia em subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia em subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | Define o tamanho da chave. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Calcula o valor hash do array de dados especificado usando o algoritmo hash especificado e assina o resultado. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&) | Calcula o valor hash do array de dados especificado usando o algoritmo hash especificado e assina o resultado. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Calcula o valor hash do fluxo binário especificado usando o algoritmo hash especificado e assina o resultado. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Calcula a assinatura do valor de entrada especificado. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método [Object.ToString()](../../system/object/tostring/) do C#. Habilita a conversão de objetos personalizados para string. |
| virtual [String](../../system/string/) [ToXmlString](../asymmetricalgorithm/toxmlstring/)(**bool**) | Escreve os parâmetros do algoritmo em uma string XML. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Verifica se a assinatura dos dados especificados é válida. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Verifica se a assinatura dos dados especificados é válida. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Verifica se a assinatura do fluxo binário especificado é válida. |
| virtual **bool** [VerifyHash](./verifyhash/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/)) | Verifica a assinatura dos dados. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [AsymmetricAlgorithm](../asymmetricalgorithm/)
* Espaço de nomes [System::Security::Cryptography](../)
* Biblioteca [Aspose.Slides](../../)