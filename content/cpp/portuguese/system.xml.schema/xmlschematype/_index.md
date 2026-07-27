---
title: XmlSchemaType
second_title: Aspose.Slides para C++ Referência da API
description: A classe base para todos os tipos simples e tipos complexos.
type: docs
weight: 911
url: /pt/system.xml.schema/xmlschematype/
---
## XmlSchemaType classe

A classe base para todos os tipos simples e tipos complexos.

```cpp
class XmlSchemaType : public System::Xml::Schema::XmlSchemaAnnotated
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para fins internos. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Retorna a propriedade **annotation**. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](./get_baseschematype/)() | Retorna o tipo de objeto pós-compilação ou o tipo de dado embutido da Definição de Linguagem XML [Schema](../) (XSD), elemento simpleType ou elemento complexType. Este é um valor de infoset pós-compilação de esquema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](./)\> [get_BaseXmlSchemaType](./get_basexmlschematype/)() | Retorna o valor pós-compilação para o tipo base deste tipo de esquema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](./get_datatype/)() | Retorna o valor pós-compilação para o tipo de dado do tipo complexo. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](./get_derivedby/)() | Retorna a informação pós-compilação sobre como este elemento foi derivado do seu tipo base. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | Retorna o atributo final da derivação de tipo que indica se derivações adicionais são permitidas. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | Retorna a interpretação pós-compilação do valor [XmlSchemaType::get_Final](./get_final/). |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Retorna o id da string. |
| virtual **bool** [get_IsMixed](./get_ismixed/)() | Retorna um valor indicando se este tipo possui um modelo de conteúdo misto. Esta chamada é válida apenas em um tipo complexo. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Retorna o número da linha no arquivo ao qual o elemento **schema** se refere. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Retorna a posição da linha no arquivo ao qual o elemento **schema** se refere. |
| [String](../../system/string/) [get_Name](./get_name/)() | Retorna o nome do tipo. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Retorna o XmlSerializerNamespaces a ser usado com este objeto de esquema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Retorna o pai deste [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | Retorna o nome qualificado para o tipo construído a partir do atributo **Name** deste tipo. Este é um valor pós-compilação de esquema. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Retorna a localização de origem do arquivo que carregou o esquema. |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](./get_typecode/)() | Retorna o XmlTypeCode do tipo. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Retorna os atributos qualificados que não pertencem ao namespace de destino do esquema atual. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](./getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | Retorna um [XmlSchemaComplexType](../xmlschemacomplextype/) que representa o tipo complexo embutido do tipo complexo especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](./getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Retorna um [XmlSchemaComplexType](../xmlschemacomplextype/) que representa o tipo complexo embutido do tipo complexo especificado por nome qualificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](./getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Retorna um [XmlSchemaSimpleType](../xmlschemasimpletype/) que representa o tipo simples embutido do tipo simples especificado por nome qualificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](./getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | Retorna um [XmlSchemaSimpleType](../xmlschemasimpletype/) que representa o tipo simples embutido do tipo simples especificado. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita a geração de hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| static **bool** [IsDerivedFrom](./isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](./)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](./)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Retorna um valor indicando se o tipo de esquema derivado especificado é derivado do tipo de esquema base especificado. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita a clonagem de tipos personalizados. |
|   [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|   [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e habilita a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e habilita a construção de cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência o objeto do tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhado pelo valor especificado. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Define a propriedade **annotation**. |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Define o atributo final da derivação de tipo que indica se derivações adicionais são permitidas. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Define o id da string. |
| virtual void [set_IsMixed](./set_ismixed/)(**bool**) | Define um valor indicando se este tipo possui um modelo de conteúdo misto. Esta chamada é válida apenas em um tipo complexo. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Define o número da linha no arquivo ao qual o elemento **schema** se refere. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Define a posição da linha no arquivo ao qual o elemento **schema** se refere. |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | Define o nome do tipo. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Define o XmlSerializerNamespaces a ser usado com este objeto de esquema. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Define o pai deste [XmlSchemaObject](../xmlschemaobject/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Define a localização de origem do arquivo que carregou o esquema. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Define os atributos qualificados que não pertencem ao namespace de destino do esquema atual. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhado. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
|   [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Inicializa uma nova instância da classe [XmlSchemaObject](../xmlschemaobject/). |
|   [XmlSchemaType](./xmlschematype/)() | Inicializa uma nova instância da classe [XmlSchemaType](./). |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Definições de Tipo

| Definição | Descrição |
| --- | --- |
| [Ptr](./ptr/) | Um alias para ponteiro compartilhado a uma instância desta classe. |

## Observações

Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. 

## Ver Também

* Classe [XmlSchemaAnnotated](../xmlschemaannotated/)
* Namespace [System::Xml::Schema](../)
* Biblioteca [Aspose.Slides](../../)