---
title: XmlSchemaSimpleTypeList
second_title: Aspose.Slides para C++ Referência da API
description: Representa o elemento list do XML Schema conforme especificado pelo World Wide Web Consortium (W3C). Esta classe pode ser usada para definir um elemento simpleType como uma lista de valores de um tipo de dado especificado.
type: docs
weight: 859
url: /pt/system.xml.schema/xmlschemasimpletypelist/
---
## XmlSchemaSimpleTypeList classe


Representa o elemento **list** do XML [Schema](../) conforme especificado pelo Consórcio World Wide [Web](../../system.web/) (W3C). Esta classe pode ser usada para definir um elemento **simpleType** como uma lista de valores de um tipo de dado especificado.

```cpp
class XmlSchemaSimpleTypeList : public System::Xml::Schema::XmlSchemaSimpleTypeContent
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Retorna a propriedade **annotation**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [get_BaseItemType](./get_baseitemtype/)() | Retorna o [XmlSchemaSimpleType](../xmlschemasimpletype/) que representa o tipo do elemento **simpleType** com base nos valores [XmlSchemaSimpleTypeList::get_ItemType](./get_itemtype/) e [XmlSchemaSimpleTypeList::get_ItemTypeName](./get_itemtypename/) do tipo simples. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Retorna o id de string. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [get_ItemType](./get_itemtype/)() | Retorna o elemento **simpleType** que é derivado do tipo especificado pelo valor base. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_ItemTypeName](./get_itemtypename/)() | Retorna o nome de um tipo de dado embutido ou elemento **simpleType** definido neste esquema (ou outro esquema indicado pelo namespace especificado). |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Retorna o número da linha no arquivo ao qual o elemento **schema** se refere. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Retorna a posição da linha no arquivo ao qual o elemento **schema** se refere. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Retorna o XmlSerializerNamespaces a ser usado com este objeto de esquema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Retorna o pai deste [XmlSchemaObject](../xmlschemaobject/). |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Retorna a localização de origem do arquivo que carregou o esquema. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Retorna os atributos qualificados que não pertencem ao namespace de destino do esquema atual. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhado pelo valor especificado. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Define a propriedade **annotation**. |
| void [set_BaseItemType](./set_baseitemtype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\>\&) | Define o [XmlSchemaSimpleType](../xmlschemasimpletype/) que representa o tipo do elemento **simpleType** com base nos valores [XmlSchemaSimpleTypeList::get_ItemType](./get_itemtype/) e [XmlSchemaSimpleTypeList::get_ItemTypeName](./get_itemtypename/) do tipo simples. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Define o id de string. |
| void [set_ItemType](./set_itemtype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\>\&) | Define o elemento **simpleType** que é derivado do tipo especificado pelo valor base. |
| void [set_ItemTypeName](./set_itemtypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Define o nome de um tipo de dado embutido ou elemento **simpleType** definido neste esquema (ou outro esquema indicado pelo namespace especificado). |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Define o número da linha no arquivo ao qual o elemento **schema** se refere. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Define a posição da linha no arquivo ao qual o elemento **schema** se refere. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Define o XmlSerializerNamespaces a ser usado com este objeto de esquema. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Define o pai deste [XmlSchemaObject](../xmlschemaobject/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Define a localização de origem do arquivo que carregou o esquema. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Define os atributos qualificados que não pertencem ao namespace de destino do esquema atual. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhado. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhado. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhado. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico ao método C# [Object.ToString()](../../system/object/tostring/). Habilita conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa o construto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraco. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraco. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Inicializa uma nova instância da classe [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaSimpleTypeList](./xmlschemasimpletypelist/)() | Inicializa uma nova instância da classe [XmlSchemaSimpleTypeList](./). |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Tipos definidos

| Typedef | Descrição |
| --- | --- |
| [Ptr](./ptr/) | Um alias para ponteiro compartilhado a uma instância desta classe. |

## Observações



Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. 

## Veja Também

* Classe [XmlSchemaSimpleTypeContent](../xmlschemasimpletypecontent/)
* Espaço de nomes [System::Xml::Schema](../)
* Biblioteca [Aspose.Slides](../../)