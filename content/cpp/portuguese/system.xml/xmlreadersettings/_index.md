---
title: XmlReaderSettings
second_title: Referência da API Aspose.Slides para C++
description: "Especifica um conjunto de recursos a serem suportados no objeto XmlReader criado pelo método XmlReader::Create."
type: docs
weight: 443
url: /pt/system.xml/xmlreadersettings/
---
## XmlReaderSettings classe

Especifica um conjunto de recursos a serem suportados no objeto [XmlReader](../xmlreader/) criado pelo método [XmlReader::Create](../xmlreader/create/).

```cpp
class XmlReaderSettings : public System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | Cria uma cópia da instância [XmlReaderSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Retorna um valor indicando se deve realizar verificação de caracteres. |
| **bool** [get_CloseInput](./get_closeinput/)() | Retorna um valor indicando se o fluxo subjacente ou TextReader deve ser fechado quando o leitor for fechado. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Retorna o nível de conformidade que o [XmlReader](../xmlreader/) seguirá. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Retorna um valor que determina o processamento de DTDs. |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | Retorna um valor indicando se deve ignorar comentários. |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | Retorna um valor indicando se deve ignorar instruções de processamento. |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | Retorna um valor indicando se deve ignorar espaços em branco insignificantes. |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | Retorna o deslocamento do número da linha do objeto [XmlReader](../xmlreader/). |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | Retorna o deslocamento da posição da linha do objeto [XmlReader](../xmlreader/). |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | Retorna um valor indicando o número máximo permitido de caracteres em um documento resultante da expansão de entidades. |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | Retorna um valor indicando o número máximo permitido de caracteres em um documento XML. Um valor zero (0) significa que não há limites para o tamanho do documento XML. Um valor diferente de zero especifica o tamanho máximo, em caracteres. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Retorna o [XmlNameTable](../xmlnametable/) usado para comparações de strings atomizadas. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Retorna um valor indicando se deve proibir o processamento de definição de tipo de documento (DTD). |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | Retorna o XmlSchemaSet a ser usado ao realizar validação de esquema. |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | Retorna um valor indicando as configurações de validação de esquema. Esta configuração se aplica a objetos [XmlReader](../xmlreader/) que validam esquemas (o valor [XmlReaderSettings::get_ValidationType](./get_validationtype/) é [ValidationType::Schema](../validationtype/)). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Retorna um valor indicando se o [XmlReader](../xmlreader/) realizará validação ou atribuição de tipo ao ler. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita clonagem de tipos personalizados. |
| [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [Reset](./reset/)() | Redefine os membros da classe de configurações para seus valores padrão. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Define um valor indicando se deve realizar verificação de caracteres. |
| void [set_CloseInput](./set_closeinput/)(**bool**) | Define um valor indicando se o fluxo subjacente ou TextReader deve ser fechado quando o leitor for fechado. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Define o nível de conformidade que o [XmlReader](../xmlreader/) seguirá. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Define um valor que determina o processamento de DTDs. |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | Define um valor indicando se deve ignorar comentários. |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | Define um valor indicando se deve ignorar instruções de processamento. |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | Define um valor indicando se deve ignorar espaços em branco insignificantes. |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | Define o deslocamento do número da linha do objeto [XmlReader](../xmlreader/). |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | Define o deslocamento da posição da linha do objeto [XmlReader](../xmlreader/). |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | Define um valor indicando o número máximo permitido de caracteres em um documento resultante da expansão de entidades. |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | Define um valor indicando o número máximo permitido de caracteres em um documento XML. Um valor zero (0) significa que não há limites para o tamanho do documento XML. Um valor diferente de zero especifica o tamanho máximo, em caracteres. |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Define o [XmlNameTable](../xmlnametable/) usado para comparações de strings atomizadas. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Define um valor indicando se deve proibir o processamento de definição de tipo de documento (DTD). |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | Define o XmlSchemaSet a ser usado ao realizar validação de esquema. |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | Define um valor indicando as configurações de validação de esquema. Esta configuração se aplica a objetos [XmlReader](../xmlreader/) que validam esquemas (o valor [XmlReaderSettings::get_ValidationType](./get_validationtype/) é [ValidationType::Schema](../validationtype/)). |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Define um valor indicando se o [XmlReader](../xmlreader/) realizará validação ou atribuição de tipo ao ler. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Define o [XmlResolver](../xmlresolver/) usado para acessar documentos externos. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Adiciona um manipulador de evento que ocorre quando o leitor encontra erros de validação. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Remove um manipulador de evento que ocorre quando o leitor encontra erros de validação. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| [XmlReaderSettings](./xmlreadersettings/)() | Inicializa uma nova instância da classe [XmlReaderSettings](./). |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Typedefs

| Typedef | Descrição |
| --- | --- |
| [Ptr](./ptr/) | Um alias para ponteiro compartilhado a uma instância desta classe. |

## Observações

Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

## Veja Também

* Classe [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)