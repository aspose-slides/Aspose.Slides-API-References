---
title: XmlSchema
second_title: Referência da API Aspose.Slides para C++
description: Uma representação em memória de um Schema XML, conforme especificado no Consórcio World Wide Web (W3C) e .
type: docs
weight: 79
url: /pt/system.xml.schema/xmlschema/
---
## XmlSchema classe


Uma representação em memória de um XML [Schema](../), conforme especificado no Consórcio World Wide [Web](../../system.web/) (W3C) [XML Schema Part 1: Structures](https://www.w3.org/TR/xmlschema-1/) e [XML Schema Part 2: Datatypes](https://www.w3.org/TR/xmlschema-2/).

```cpp
class XmlSchema : public System::Xml::Schema::XmlSchemaObject
```


## Métodos

| Método | Descrição |
| --- | --- |
| void [Compile](./compile/)([ValidationEventHandler](../validationeventhandler/)) | Compila o Modelo XML [Schema](../)[Object](../../system/object/) (SOM) em informações de esquema para validação. Usado para verificar a estrutura sintática e semântica do SOM construído programaticamente. A verificação de validação semântica é realizada durante a compilação. |
| void [Compile](./compile/)([ValidationEventHandler](../validationeventhandler/), const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | Compila o Modelo XML [Schema](../)[Object](../../system/object/) (SOM) em informações de esquema para validação. Usado para verificar a estrutura sintática e semântica do SOM construído programaticamente. A verificação de validação semântica é realizada durante a compilação. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora conforme IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora conforme IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| [XmlSchemaForm](../xmlschemaform/) [get_AttributeFormDefault](./get_attributeformdefault/)() | Retorna o formulário para atributos declarados no namespace de destino do esquema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeGroups](./get_attributegroups/)() | Retorna o valor pós-compilação do esquema de todos os grupos de atributos globais no esquema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Attributes](./get_attributes/)() | Retorna o valor pós-compilação do esquema para todos os atributos no esquema. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockDefault](./get_blockdefault/)() | Retorna o atributo **blockDefault** que define o valor padrão do atributo **block** em elementos e tipos complexos no **targetNamespace** do esquema. |
| [XmlSchemaForm](../xmlschemaform/) [get_ElementFormDefault](./get_elementformdefault/)() | Retorna o formulário para elementos declarados no namespace de destino do esquema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Elements](./get_elements/)() | Retorna o valor pós-compilação do esquema para todos os elementos no esquema. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalDefault](./get_finaldefault/)() | Retorna o atributo **finalDefault** que define o valor padrão do atributo **final** em elementos e tipos complexos no namespace de destino do esquema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Groups](./get_groups/)() | Retorna o valor pós-compilação do esquema de todos os grupos no esquema. |
| [String](../../system/string/) [get_Id](./get_id/)() | Retorna o ID da string. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Includes](./get_includes/)() | Retorna a coleção de esquemas incluídos e importados. |
| **bool** [get_IsCompiled](./get_iscompiled/)() | Indica se o esquema foi compilado. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Items](./get_items/)() | Retorna a coleção de elementos do esquema e é usado para adicionar novos tipos de elemento no nível do elemento **schema**. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Retorna o número da linha no arquivo ao qual o elemento **schema** se refere. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Retorna a posição da linha no arquivo ao qual o elemento **schema** se refere. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Retorna o XmlSerializerNamespaces a ser usado com este objeto de esquema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Notations](./get_notations/)() | Retorna o valor pós-compilação do esquema para todas as notações no esquema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Retorna o pai deste [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_SchemaTypes](./get_schematypes/)() | Retorna o valor pós-compilação do esquema de todos os tipos de esquema no esquema. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Retorna a localização de origem do arquivo que carregou o esquema. |
| [String](../../system/string/) [get_TargetNamespace](./get_targetnamespace/)() | Retorna o Identificador Uniforme de Recursos (URI) do namespace de destino do esquema. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](./get_unhandledattributes/)() | Retorna os atributos qualificados que não pertencem ao namespace de destino do esquema. |
| [String](../../system/string/) [get_Version](./get_version/)() | Retorna a versão do esquema. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método [Object.GetHashCode()](../../system/object/gethashcode/) do C#. Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada [System.Object.GetType()](../../system/object/gettype/) do C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador 'is' do C#. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) do C#. Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | Lê um [Schema](../) XML a partir do [IO::TextReader](../../system.io/textreader/) fornecido. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | Lê um [Schema](../) XML a partir do fluxo fornecido. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | Lê um [Schema](../) XML a partir do [XmlReader](../../system.xml/xmlreader/) fornecido. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_AttributeFormDefault](./set_attributeformdefault/)([XmlSchemaForm](../xmlschemaform/)) | Define o formulário para atributos declarados no namespace de destino do esquema. |
| void [set_BlockDefault](./set_blockdefault/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Define o atributo **blockDefault** que define o valor padrão do atributo **block** em elementos e tipos complexos no **targetNamespace** do esquema. |
| void [set_ElementFormDefault](./set_elementformdefault/)([XmlSchemaForm](../xmlschemaform/)) | Define o formulário para elementos declarados no namespace de destino do esquema. |
| void [set_FinalDefault](./set_finaldefault/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Define o atributo **finalDefault** que define o valor padrão do atributo **final** em elementos e tipos complexos no namespace de destino do esquema. |
| void [set_Id](./set_id/)(const [String](../../system/string/)\&) | Define o ID da string. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Define o número da linha no arquivo ao qual o elemento **schema** se refere. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Define a posição da linha no arquivo ao qual o elemento **schema** se refere. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Define o XmlSerializerNamespaces a ser usado com este objeto de esquema. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Define o pai deste [XmlSchemaObject](../xmlschemaobject/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Define a localização de origem do arquivo que carregou o esquema. |
| void [set_TargetNamespace](./set_targetnamespace/)(const [String](../../system/string/)\&) | Define o Identificador Uniforme de Recursos (URI) do namespace de destino do esquema. |
| void [set_UnhandledAttributes](./set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Define os atributos qualificados que não pertencem ao namespace de destino do esquema. |
| void [set_Version](./set_version/)(const [String](../../system/string/)\&) | Define a versão do esquema. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método [Object.ToString()](../../system/object/tostring/) do C#. Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Escreve o XML [Schema](../) no fluxo de dados fornecido. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | Escreve o XML [Schema](../) no Stream fornecido usando o [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/) especificado. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Escreve o XML [Schema](../) no [IO::TextWriter](../../system.io/textwriter/) fornecido. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | Escreve o XML [Schema](../) no TextWriter fornecido. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | Escreve o XML [Schema](../) no [XmlWriter](../../system.xml/xmlwriter/) fornecido. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | Escreve o XML [Schema](../) no [XmlWriter](../../system.xml/xmlwriter/) fornecido. |
|  [XmlSchema](./xmlschema/)() | Inicializa uma nova instância da classe [XmlSchema](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Inicializa uma nova instância da classe [XmlSchemaObject](../xmlschemaobject/). |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [InstanceNamespace](./instancenamespace/) | O namespace da instância do esquema XML. Este campo é constante. |
| static [Namespace](./namespace/) | O namespace do esquema XML. Este campo é constante. |

## Typedefs

| Typedef | Descrição |
| --- | --- |
| [Ptr](./ptr/) | Um alias para ponteiro compartilhado para uma instância desta classe. |

## Observações



Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. 

## Veja também

* Classe [XmlSchemaObject](../xmlschemaobject/)
* Namespace [System::Xml::Schema](../)
* Biblioteca [Aspose.Slides](../../)