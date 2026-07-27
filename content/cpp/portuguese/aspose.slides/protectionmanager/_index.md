---
title: ProtectionManager
second_title: Referência da API Aspose.Slides para C++
description: Gerenciamento de proteção por senha de apresentação.
type: docs
weight: 4915
url: /pt/aspose.slides/protectionmanager/
---
## classe ProtectionManager

[Presentation](../presentation/) gerenciamento de proteção por senha.

```cpp
class ProtectionManager : public Aspose::Slides::IProtectionManager
```

## Métodos

| Método | Descrição |
| --- | --- |
| **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) override | Determina se uma apresentação está protegida por senha para modificar. |
| void [Encrypt](./encrypt/)([System::String](../../system/string/)) override | Criptografa [Presentation](../presentation/) com a senha especificada. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| **bool** [get_EncryptDocumentProperties](./get_encryptdocumentproperties/)() override | Esta propriedade faz sentido se a apresentação estiver protegida por senha. Se true, então as propriedades do documento são criptografadas no arquivo da apresentação. Se false, as propriedades do documento são públicas enquanto a apresentação está criptografada. Leitura **bool**. |
| [System::String](../../system/string/) [get_EncryptionPassword](./get_encryptionpassword/)() override | Obtém a senha que é usada para criptografia da apresentação. Somente leitura [System::String](../../system/string/). |
| **bool** [get_IsEncrypted](./get_isencrypted/)() override | Obtém um valor que indica se esta instância está criptografada. Somente leitura **bool**. |
| **bool** [get_IsOnlyDocumentPropertiesLoaded](./get_isonlydocumentpropertiesloaded/)() override | Esta propriedade faz sentido se o arquivo da apresentação estiver protegido por senha e as propriedades do documento deste arquivo forem públicas. Valor true significa que apenas as propriedades do documento são carregadas de um arquivo de apresentação criptografado sem uso de senha. Valor false significa que toda a apresentação criptografada é carregada usando a senha correta, não apenas as propriedades do documento. Se a apresentação não estiver criptografada, então o valor da propriedade é sempre false. Se as propriedades do documento de um arquivo criptografado não forem públicas, então o valor da propriedade é sempre false. Se Presentation.EncryptDocumentProperties for true, então o valor da propriedade IsOnlyDocumentPropertiesLoaded é sempre false. Somente leitura **bool**. |
| **bool** [get_IsWriteProtected](./get_iswriteprotected/)() override | Obtém um valor que indica se esta apresentação está protegida contra gravação. Somente leitura **bool**. |
| **bool** [get_ReadOnlyRecommended](./get_readonlyrecommended/)() override | Obtém recomendação somente leitura. Leitura **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita clonagem de tipos personalizados. |
| [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [RemoveEncryption](./removeencryption/)() override | Remove a criptografia. |
| void [RemoveWriteProtection](./removewriteprotection/)() override | Remove a proteção contra gravação desta apresentação. |
| void [set_EncryptDocumentProperties](./set_encryptdocumentproperties/)(**bool**) override | Esta propriedade faz sentido se a apresentação estiver protegida por senha. Se true, então as propriedades do documento são criptografadas no arquivo da apresentação. Se false, as propriedades do documento são públicas enquanto a apresentação está criptografada. Escrita **bool**. |
| void [set_ReadOnlyRecommended](./set_readonlyrecommended/)(**bool**) override | Define recomendação somente leitura. Escrita **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como weak pointer (em vez de shared). Permite trocar ponteiros em contêineres para modo fraco. |
| void [SetWriteProtection](./setwriteprotection/)([System::String](../../system/string/)) override | Define proteção contra gravação para esta apresentação com a senha especificada. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Ver também

* Classe [IProtectionManager](../iprotectionmanager/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)