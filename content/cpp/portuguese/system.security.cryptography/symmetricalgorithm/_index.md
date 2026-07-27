---
title: SymmetricAlgorithm
second_title: Referência da API Aspose.Slides para C++
description: "Algoritmo simétrico que usa a mesma chave para criptografia e descriptografia, classe base. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instância desse tipo na pilha ou usando o operador new, pois resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro ao passá-lo para funções como argumento."
type: docs
weight: 651
url: /pt/system.security.cryptography/symmetricalgorithm/
---
## SymmetricAlgorithm classe

Algoritmo simétrico que usa a mesma chave para criptografia e descriptografia, classe base. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro ao passá-lo para funções como argumento.

```cpp
class SymmetricAlgorithm : public virtual System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[SymmetricAlgorithm](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Cria uma instância do algoritmo. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)() | Cria um descriptografador com parâmetros associados ao objeto do algoritmo. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Cria um descriptografador com parâmetros explícitos. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)() | Cria um criptografador com parâmetros associados ao objeto do algoritmo. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Cria um criptografador com parâmetros explícitos. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, mesmo que de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, mesmo que de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para fins internos. |
| virtual void [GenerateIV](./generateiv/)() | Gera um valor inicial aleatório para o algoritmo. Substitui o existente (se houver). |
| virtual void [GenerateKey](./generatekey/)() | Gera uma chave aleatória para o algoritmo. Substitui a existente (se houver). |
| virtual int [get_BlockSize](./get_blocksize/)() | Obtém o tamanho do bloco da operação criptográfica. |
| virtual int [get_FeedbackSize](./get_feedbacksize/)() | Obtém o tamanho da retroalimentação da operação criptográfica. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_IV](./get_iv/)() | Obtém o valor inicial da operação criptográfica. Cria um novo se ainda não foi criado. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_Key](./get_key/)() | Obtém a chave da operação criptográfica. Cria uma nova se ainda não foi criada. |
| virtual int [get_KeySize](./get_keysize/)() | Obtém o tamanho da chave da operação criptográfica. |
| virtual [CipherMode](../ciphermode/) [get_Mode](./get_mode/)() | Obtém o modo da operação criptográfica. |
| virtual [PaddingMode](../paddingmode/) [get_Padding](./get_padding/)() | Obtém o preenchimento da operação criptográfica. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoga ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analoga à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analoga ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoga ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_BlockSize](./set_blocksize/)(int) | Define o tamanho do bloco da operação criptográfica. |
| virtual void [set_FeedbackSize](./set_feedbacksize/)(int) | Define o tamanho da retroalimentação da operação criptográfica. |
| virtual void [set_IV](./set_iv/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Define o valor inicial da operação criptográfica. |
| virtual void [set_Key](./set_key/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Define a chave da operação criptográfica. |
| virtual void [set_KeySize](./set_keysize/)(int) | Define o tamanho da chave da operação criptográfica. |
| virtual void [set_Mode](./set_mode/)([CipherMode](../ciphermode/)) | Define o modo da operação criptográfica. |
| virtual void [set_Padding](./set_padding/)([PaddingMode](../paddingmode/)) | Define o preenchimento da operação criptográfica. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e devolve o contador de referência compartilhada. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoga ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| **bool** [ValidKeySize](./validkeysize/)(int) | Verifica se o tamanho da chave é válido. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Ver também

* Classe [Object](../../system/object/)
* Espaço de nomes [System::Security::Cryptography](../)
* Biblioteca [Aspose.Slides](../../)