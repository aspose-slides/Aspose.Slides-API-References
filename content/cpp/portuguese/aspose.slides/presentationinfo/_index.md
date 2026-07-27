---
title: PresentationInfo
second_title: Referência da API Aspose.Slides para C++
description: Informações sobre o arquivo de apresentação
type: docs
weight: 4876
url: /pt/aspose.slides/presentationinfo/
---
## PresentationInfo classe


Informações sobre o arquivo de apresentação

```cpp
class PresentationInfo : public Aspose::Slides::IPresentationInfo
```

## Métodos

| Método | Descrição |
| --- | --- |
| **bool** [CheckPassword](./checkpassword/)([System::String](../../system/string/)) override | Verifica se a senha está correta para uma apresentação protegida com senha de abertura. |
| **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) override | Verifica se a senha de modificação está correta para uma apresentação protegida contra gravação. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| **bool** [get_IsEncrypted](./get_isencrypted/)() override | Obtém True se a apresentação vinculada estiver criptografada, caso contrário False. Somente leitura **bool**. |
| **bool** [get_IsPasswordProtected](./get_ispasswordprotected/)() override | Obtém um valor que indica se a apresentação vinculada está protegida por uma senha de abertura. |
| [NullableBool](../nullablebool/) [get_IsWriteProtected](./get_iswriteprotected/)() override | Obtém um valor que indica se a apresentação vinculada está protegida contra gravação. |
| [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() override | Obtém o formato da apresentação vinculada. Somente leitura [Slides::LoadFormat](../loadformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógia do método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógia da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógia do operador C# `is`. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógia do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita a clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [ReadDocumentProperties](./readdocumentproperties/)() override | Obtém as propriedades do documento da apresentação vinculada. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e devolve o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógia do método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| void [UpdateDocumentProperties](./updatedocumentproperties/)([System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\>) override | Atualiza as propriedades da apresentação vinculada. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WriteBindedPresentation](./writebindedpresentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Grava a apresentação vinculada no fluxo. |
| void [WriteBindedPresentation](./writebindedpresentation/)([System::String](../../system/string/)) override | Grava a apresentação vinculada em arquivo. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |
## Veja Também

* Classe [IPresentationInfo](../ipresentationinfo/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)