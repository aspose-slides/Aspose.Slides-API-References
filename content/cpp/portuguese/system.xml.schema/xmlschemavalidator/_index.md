---
title: XmlSchemaValidator
second_title: Referência da API Aspose.Slides para C++
description: Representa um motor de validação de esquema XML Schema Definition Language (XSD). A classe XmlSchemaValidator não pode ser herdada.
type: docs
weight: 937
url: /pt/system.xml.schema/xmlschemavalidator/
---
## XmlSchemaValidator classe


Representa um motor de validação XML [Schema](../) Definition Language (XSD) [Schema](../). A classe [XmlSchemaValidator](./) não pode ser herdada.

```cpp
class XmlSchemaValidator : public System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| void [AddSchema](./addschema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Adiciona um esquema XML [Schema](../) Definition Language (XSD) ao conjunto de esquemas usados para validação. |
| void [EndValidation](./endvalidation/)() | Finaliza a validação e verifica as restrições de identidade para todo o documento XML. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para fins internos. |
| [SharedPtr](../../system/sharedptr/)\<[IXmlLineInfo](../../system.xml/ixmllineinfo/)\> [get_LineInfoProvider](./get_lineinfoprovider/)() | Retorna as informações de número da linha para o nó XML que está sendo validado. |
| [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_SourceUri](./get_sourceuri/)() | Retorna o URI de origem para o nó XML que está sendo validado. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ValidationEventSender](./get_validationeventsender/)() | Retorna o objeto enviado como o objeto remetente de um evento de validação. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchemaAttribute](../xmlschemaattribute/)\>\> [GetExpectedAttributes](./getexpectedattributes/)() | Retorna os atributos esperados para o contexto do elemento atual. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\>\> [GetExpectedParticles](./getexpectedparticles/)() | Retorna as partículas esperadas no contexto do elemento atual. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| void [GetUnspecifiedDefaultAttributes](./getunspecifieddefaultattributes/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\>\&) | Valida restrições de identidade nos atributos padrão e preenche a List especificada com objetos [XmlSchemaAttribute](../xmlschemaattribute/) para quaisquer atributos com valores padrão que não tenham sido previamente validados usando o método [XmlSchemaValidator::ValidateAttribute](./validateattribute/) no contexto do elemento. |
| void [Initialize](./initialize/)() | Inicializa o estado do objeto [XmlSchemaValidator](./). |
| void [Initialize](./initialize/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Inicializa o estado do objeto [XmlSchemaValidator](./) usando o [XmlSchemaObject](../xmlschemaobject/) especificado para validação parcial. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_LineInfoProvider](./set_lineinfoprovider/)(const [SharedPtr](../../system/sharedptr/)\<[IXmlLineInfo](../../system.xml/ixmllineinfo/)\>\&) | Define as informações de número da linha para o nó XML que está sendo validado. |
| void [set_SourceUri](./set_sourceuri/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&) | Define o URI de origem para o nó XML que está sendo validado. |
| void [set_ValidationEventSender](./set_validationeventsender/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Define o objeto enviado como o objeto remetente de um evento de validação. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Define o objeto [XmlResolver](../../system.xml/xmlresolver/) usado para resolver os elementos **xs:import** e **xs:include**, bem como os atributos **xsi:schemaLocation** e **xsi:noNamespaceSchemaLocation**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [SkipToEndElement](./skiptoendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Ignora a validação do conteúdo do elemento atual e prepara o objeto [XmlSchemaValidator](./) para validar o conteúdo no contexto do elemento pai. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa a liberação da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateAttribute](./validateattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Valida o nome do atributo, o URI do namespace e o valor no contexto do elemento atual. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateAttribute](./validateattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [XmlValueGetter](../xmlvaluegetter/), const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Valida o nome do atributo, o URI do namespace e o valor no contexto do elemento atual. |
| void [ValidateElement](./validateelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Valida o elemento no contexto atual. |
| void [ValidateElement](./validateelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Valida o elemento no contexto atual com os valores dos atributos **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** e **xsi:NoNamespaceSchemaLocation** especificados. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateEndElement](./validateendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Verifica se o conteúdo de texto do elemento é válido de acordo com seu tipo de dados para elementos com conteúdo simples, e verifica se o conteúdo do elemento atual está completo para elementos com conteúdo complexo. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateEndElement](./validateendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Verifica se o conteúdo de texto do elemento especificado é válido de acordo com seu tipo de dados. |
| void [ValidateEndOfAttributes](./validateendofattributes/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Verifica se todos os atributos exigidos no contexto do elemento estão presentes e prepara o objeto [XmlSchemaValidator](./) para validar o conteúdo filho do elemento. |
| void [ValidateText](./validatetext/)(const [String](../../system/string/)\&) | Valida se a **string** de texto especificada é permitida no contexto do elemento atual e acumula o texto para validação se o elemento atual tiver conteúdo simples. |
| void [ValidateText](./validatetext/)([XmlValueGetter](../xmlvaluegetter/)) | Valida se o texto retornado pelo objeto XmlValueGetter especificado é permitido no contexto do elemento atual e acumula o texto para validação se o elemento atual tiver conteúdo simples. |
| void [ValidateWhitespace](./validatewhitespace/)(const [String](../../system/string/)\&) | Valida se o espaço em branco na **string** especificada é permitido no contexto do elemento atual e acumula o espaço em branco para validação se o elemento atual tiver conteúdo simples. |
| void [ValidateWhitespace](./validatewhitespace/)([XmlValueGetter](../xmlvaluegetter/)) | Valida se o espaço em branco retornado pelo objeto XmlValueGetter especificado é permitido no contexto do elemento atual e acumula o espaço em branco para validação se o elemento atual tiver conteúdo simples. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
|  [XmlSchemaValidator](./xmlschemavalidator/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](../xmlschemaset/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>\&, [XmlSchemaValidationFlags](../xmlschemavalidationflags/)) | Inicializa uma nova instância da classe [XmlSchemaValidator](./). |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Um alias para ponteiro compartilhado para uma instância desta classe. |
## Observações



Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. 

## Ver Também

* Classe [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Biblioteca [Aspose.Slides](../../)