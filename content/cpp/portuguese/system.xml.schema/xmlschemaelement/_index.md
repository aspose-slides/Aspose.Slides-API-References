---
title: XmlSchemaElement
second_title: Referência da API Aspose.Slides para C++
description: Representa o elemento do XML Schema conforme especificado pelo World Wide Web Consortium (W3C). Esta classe é a classe base para todos os tipos de partícula e é usada para descrever um elemento em um documento XML.
type: docs
weight: 365
url: /pt/system.xml.schema/xmlschemaelement/
---
## XmlSchemaElement classe

Representa o **elemento** do XML [Schema](../) conforme especificado pelo Consórcio World Wide [Web](../../system.web/) (W3C). Esta classe é a classe base para todos os tipos de partícula e é usada para descrever um elemento em um documento XML.

```cpp
class XmlSchemaElement : public System::Xml::Schema::XmlSchemaParticle
```

## Métodos

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Retorna a propriedade **annotation**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | Retorna uma derivação **Block**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | Retorna a interpretação pós-compilação do valor **Block**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Constraints](./get_constraints/)() | Retorna a coleção de restrições sobre o elemento. |
| [String](../../system/string/) [get_DefaultValue](./get_defaultvalue/)() | Retorna o valor padrão do elemento se seu conteúdo for um tipo simples ou se o conteúdo do elemento for **textOnly**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_ElementSchemaType](./get_elementschematype/)() | Retorna um objeto [XmlSchemaType](../xmlschematype/) que representa o tipo do elemento com base nos valores [XmlSchemaElement::get_SchemaType](./get_schematype/) ou [XmlSchemaElement::get_SchemaTypeName](./get_schematypename/) do elemento. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ElementType](./get_elementtype/)() | Retorna um objeto com base em [XmlSchemaElement](./) ou [XmlSchemaElement](./) do elemento, que contém a interpretação pós-compilação do valor **ElementType**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | Retorna o valor **Final** para indicar que nenhuma derivação adicional é permitida. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | Retorna a interpretação pós-compilação do valor **Final**. |
| [String](../../system/string/) [get_FixedValue](./get_fixedvalue/)() | Retorna o valor fixo. |
| [XmlSchemaForm](../xmlschemaform/) [get_Form](./get_form/)() | Retorna a forma do elemento. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Retorna o identificador de string. |
| **bool** [get_IsAbstract](./get_isabstract/)() | Retorna informação que indica se o elemento pode ser usado em um documento de instância. |
| **bool** [get_IsNillable](./get_isnillable/)() | Retorna informação que indica se **xsi:nil** pode ocorrer nos dados de instância. Indica se um valor nil explícito pode ser atribuído ao elemento. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Retorna o número da linha no arquivo ao qual o elemento **schema** se refere. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Retorna a posição da linha no arquivo ao qual o elemento **schema** se refere. |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | Retorna o número máximo de vezes que a partícula pode ocorrer. |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | Retorna o número como valor de string. Número máximo de vezes que a partícula pode ocorrer. |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | Retorna o número mínimo de vezes que a partícula pode ocorrer. |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | Retorna o número como valor de string. O número mínimo de vezes que a partícula pode ocorrer. |
| [String](../../system/string/) [get_Name](./get_name/)() | Retorna o nome do elemento. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Retorna o XmlSerializerNamespaces a ser usado com este objeto de esquema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Retorna o pai deste [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | Retorna o nome qualificado real para o elemento fornecido. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | Retorna o nome de referência de um elemento declarado neste esquema (ou em outro esquema indicado pelo namespace especificado). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_SchemaType](./get_schematype/)() | Retorna o tipo do elemento. Pode ser um tipo complexo ou um tipo simples. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SchemaTypeName](./get_schematypename/)() | Retorna o nome de um tipo de dado embutido definido neste esquema ou em outro esquema indicado pelo namespace especificado. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Retorna a localização de origem do arquivo que carregou o esquema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SubstitutionGroup](./get_substitutiongroup/)() | Retorna o nome de um elemento que está sendo substituído por este elemento. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Retorna os atributos qualificados que não pertencem ao namespace de destino do esquema atual. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, apenas inicializa um novo objeto e permite construir cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, apenas inicializa um novo objeto e permite construir cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Define a propriedade **annotation**. |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Define uma derivação **Block**. |
| void [set_DefaultValue](./set_defaultvalue/)(const [String](../../system/string/)\&) | Define o valor padrão do elemento se seu conteúdo for um tipo simples ou se o conteúdo do elemento for **textOnly**. |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Define o valor **Final** para indicar que nenhuma derivação adicional é permitida. |
| void [set_FixedValue](./set_fixedvalue/)(const [String](../../system/string/)\&) | Define o valor fixo. |
| void [set_Form](./set_form/)([XmlSchemaForm](../xmlschemaform/)) | Define a forma do elemento. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Define o identificador de string. |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | Define informação que indica se o elemento pode ser usado em um documento de instância. |
| void [set_IsNillable](./set_isnillable/)(**bool**) | Define informação que indica se **xsi:nil** pode ocorrer nos dados de instância. Indica se um valor nil explícito pode ser atribuído ao elemento. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Define o número da linha no arquivo ao qual o elemento **schema** se refere. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Define a posição da linha no arquivo ao qual o elemento **schema** se refere. |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | Define o número máximo de vezes que a partícula pode ocorrer. |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | Define o número como valor de string. Número máximo de vezes que a partícula pode ocorrer. |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | Define o número mínimo de vezes que a partícula pode ocorrer. |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | Define o número como valor de string. O número mínimo de vezes que a partícula pode ocorrer. |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | Define o nome do elemento. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Define o XmlSerializerNamespaces a ser usado com este objeto de esquema. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Define o pai deste [XmlSchemaObject](../xmlschemaobject/). |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Define o nome de referência de um elemento declarado neste esquema (ou em outro esquema indicado pelo namespace especificado). |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&) | Define o tipo do elemento. Pode ser um tipo complexo ou um tipo simples. |
| void [set_SchemaTypeName](./set_schematypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Define o nome de um tipo de dado embutido definido neste esquema ou em outro esquema indicado pelo namespace especificado. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Define a localização de origem do arquivo que carregou o esquema. |
| void [set_SubstitutionGroup](./set_substitutiongroup/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Define o nome de um elemento que está sendo substituído por este elemento. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Define os atributos qualificados que não pertencem ao namespace de destino do esquema atual. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| [XmlSchemaElement](./xmlschemaelement/)() | Inicializa uma nova instância da classe [XmlSchemaElement](./). |
| [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Inicializa uma nova instância da classe [XmlSchemaObject](../xmlschemaobject/). |
| [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | Inicializa uma nova instância da classe [XmlSchemaParticle](../xmlschemaparticle/). |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Definições de tipo

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Um alias para ponteiro compartilhado de uma instância desta classe. |

## Observações

Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-la a funções como argumento. 

## Ver Também

* Classe [XmlSchemaParticle](../xmlschemaparticle/)
* Espaço de nomes [System::Xml::Schema](../)
* Biblioteca [Aspose.Slides](../../)