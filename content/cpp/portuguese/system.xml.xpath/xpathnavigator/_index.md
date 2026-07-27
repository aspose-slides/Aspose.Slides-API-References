---
title: XPathNavigator
second_title: Referência da API Aspose.Slides for C++
description: Fornece um modelo de cursor para navegar e editar dados XML.
type: docs
weight: 66
url: /pt/system.xml.xpath/xpathnavigator/
---
## XPathNavigator classe

Provides a cursor model for navigating and editing XML data.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | Retorna um objeto [XmlWriter](../../system.xml/xmlwriter/) usado para criar um ou mais novos nós filhos ao final da lista de nós filhos do nó atual. |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | Cria um novo nó filho ao final da lista de nós filhos do nó atual usando a cadeia de dados XML especificada. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Cria um novo nó filho ao final da lista de nós filhos do nó atual usando o conteúdo XML do objeto [XmlReader](../../system.xml/xmlreader/) especificado. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Cria um novo nó filho ao final da lista de nós filhos do nó atual usando os nós no [XPathNavigator](./) especificado. |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Cria um novo nó de elemento filho ao final da lista de nós filhos do nó atual usando o prefixo de namespace, nome local e URI de namespace especificados com o valor especificado. |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | Verifica se os dados XML em [XPathNavigator](./) estão em conformidade com o esquema XSD (linguagem de definição XML [Schema](../../system.xml.schema/)) fornecido. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | Quando sobrescrito em uma classe derivada, cria um novo [XPathNavigator](./) posicionado no mesmo nó que este [XPathNavigator](./). |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Compara a posição do [XPathNavigator](./) atual com a posição do [XPathNavigator](./) especificado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | Compila uma cadeia que representa uma expressão [XPath](../) e retorna um objeto [XPathExpression](../xpathexpression/). |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Cria um nó de atributo no elemento atual usando o prefixo de namespace, nome local e URI de namespace especificados com o valor especificado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | Retorna um objeto [XmlWriter](../../system.xml/xmlwriter/) usado para criar novos atributos no elemento atual. |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | Retorna uma cópia do [XPathNavigator](./). |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Exclui um intervalo de nós irmãos do nó atual até o nó especificado. |
| virtual void [DeleteSelf](./deleteself/)() | Exclui o nó atual e seus nós filhos. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência ao estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor ao estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | Avalia a expressão [XPath](../) especificada e retorna o resultado tipado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Avalia a expressão [XPath](../) especificada e retorna o resultado tipado, usando o objeto [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) especificado para resolver os prefixos de namespace na expressão [XPath](../). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Avalia [XPathExpression](../xpathexpression/) e retorna o resultado tipado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | Usa o contexto fornecido para avaliar [XPathExpression](../xpathexpression/) e retorna o resultado tipado. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Quando sobrescrito em uma classe derivada, obtém o URI base para o nó atual. |
| virtual **bool** [get_CanEdit](./get_canedit/)() | Retorna um valor que indica se [XPathNavigator](./) pode editar os dados XML subjacentes. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Retorna um valor que indica se o nó atual possui atributos. |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | Retorna um valor que indica se o nó atual possui nós filhos. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | Retorna a marcação que representa os nós filhos do nó atual. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | Quando sobrescrito em uma classe derivada, obtém um valor que indica se o nó atual é um elemento vazio sem tag de fim de elemento. |
| **bool** [get_IsNode](./get_isnode/)() override | Retorna um valor que indica se o nó atual representa um nó [XPath](../). |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | Quando sobrescrito em uma classe derivada, obtém o [XPathNavigator::get_Name](./get_name/) do nó atual sem nenhum prefixo de namespace. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Quando sobrescrito em uma classe derivada, obtém o nome qualificado do nó atual. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | Quando sobrescrito em uma classe derivada, obtém o URI de namespace do nó atual. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | Quando sobrescrito em uma classe derivada, obtém o [XmlNameTable](../../system.xml/xmlnametable/) do [XPathNavigator](./). |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | Retorna um [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) usado para comparação de igualdade de objetos [XPathNavigator](./). |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | Quando sobrescrito em uma classe derivada, obtém o XPathNodeType do nó atual. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | Retorna a marcação que representa as tags de abertura e fechamento do nó atual e de seus nós filhos. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | Quando sobrescrito em uma classe derivada, obtém o prefixo de namespace associado ao nó atual. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Retorna as informações de esquema que foram atribuídas ao nó atual como resultado da validação de esquema. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | Retorna o nó atual como um objeto encapsulado do tipo mais apropriado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | Usado por implementações [XPathNavigator](./) que fornecem uma visualização XML \"virtualized\" sobre um armazenamento, para fornecer acesso aos objetos subjacentes. |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | Quando sobrescrito em uma classe derivada, obtém o valor **string** do item. |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | Retorna o valor do nó atual como um [Boolean](../../system/boolean/). |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | Retorna o valor do nó atual como um [DateTime](../../system/datetime/). |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | Retorna o valor do nó atual como um [Double](../../system/double/). |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | Retorna o valor do nó atual como um [Int32](../../system/int32/). |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | Retorna o valor do nó atual como um [Int64](../../system/int64/). |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | Retorna o tipo do nó atual. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Retorna o escopo **xml:lang** do nó atual. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | Retorna as informações XmlSchemaType do nó atual. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Retorna o valor do atributo com o nome local e URI de namespace especificados. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | Retorna o valor do nó de namespace correspondente ao nome local especificado. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | Retorna os namespaces em escopo do nó atual. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | Retorna um objeto [XmlWriter](../../system.xml/xmlwriter/) usado para criar um novo nó irmão após o nó atualmente selecionado. |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | Cria um novo nó irmão após o nó atualmente selecionado usando a cadeia XML especificada. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Cria um novo nó irmão após o nó atualmente selecionado usando o conteúdo XML do objeto [XmlReader](../../system.xml/xmlreader/) especificado. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Cria um novo nó irmão após o nó atualmente selecionado usando os nós no objeto [XPathNavigator](./) especificado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | Retorna um objeto [XmlWriter](../../system.xml/xmlwriter/) usado para criar um novo nó irmão antes do nó atualmente selecionado. |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | Cria um novo nó irmão antes do nó atualmente selecionado usando a cadeia XML especificada. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Cria um novo nó irmão antes do nó atualmente selecionado usando o conteúdo XML do objeto [XmlReader](../../system.xml/xmlreader/) especificado. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Cria um novo nó irmão antes do nó atualmente selecionado usando os nós no [XPathNavigator](./) especificado. |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Cria um novo elemento irmão após o nó atual usando o prefixo de namespace, nome local e URI de namespace especificados, com o valor especificado. |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Cria um novo elemento irmão antes do nó atual usando o prefixo de namespace, nome local e URI de namespace especificados, com o valor especificado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Determina se o [XPathNavigator](./) especificado é um descendente do [XPathNavigator](./) atual. |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Quando sobrescrito em uma classe derivada, determina se o [XPathNavigator](./) atual está na mesma posição do [XPathNavigator](./) especificado. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Retorna o URI de namespace para o prefixo especificado. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | Retorna o prefixo declarado para o URI de namespace especificado. |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Determina se o nó atual corresponde ao [XPathExpression](../xpathexpression/) especificado. |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | Determina se o nó atual corresponde à expressão [XPath](../) especificada. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Quando sobrescrito em uma classe derivada, move o [XPathNavigator](./) para a mesma posição do [XPathNavigator](./) especificado. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | Move o [XPathNavigator](./) para o atributo com o nome local e URI de namespace correspondentes. |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | Move o [XPathNavigator](./) para o nó filho com o nome local e URI de namespace especificados. |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | Move o [XPathNavigator](./) para o nó filho do XPathNodeType especificado. |
| virtual **bool** [MoveToFirst](./movetofirst/)() | Move o [XPathNavigator](./) para o primeiro nó irmão do nó atual. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | Quando sobrescrito em uma classe derivada, move o [XPathNavigator](./) para o primeiro atributo do nó atual. |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | Quando sobrescrito em uma classe derivada, move o [XPathNavigator](./) para o primeiro nó filho do nó atual. |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Quando sobrescrito em uma classe derivada, move o [XPathNavigator](./) para o primeiro nó de namespace que corresponde ao XPathNamespaceScope especificado. |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | Move o [XPathNavigator](./) para o primeiro nó de namespace do nó atual. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | Move o [XPathNavigator](./) para o elemento com o nome local e URI de namespace especificados na ordem do documento. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Move o [XPathNavigator](./) para o elemento com o nome local e URI de namespace especificados, até o limite especificado, na ordem do documento. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | Move o [XPathNavigator](./) para o próximo elemento do XPathNodeType especificado na ordem do documento. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Move o [XPathNavigator](./) para o próximo elemento do XPathNodeType especificado, até o limite especificado, na ordem do documento. |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | Quando sobrescrito em uma classe derivada, move para o nó que possui um atributo do tipo **ID** cujo valor corresponde ao [String](../../system/string/) especificado. |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | Move o [XPathNavigator](./) para o nó de namespace com o prefixo de namespace especificado. |
| virtual **bool** [MoveToNext](./movetonext/)() | Quando sobrescrito em uma classe derivada, move o [XPathNavigator](./) para o próximo nó irmão do nó atual. |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | Move o [XPathNavigator](./) para o próximo nó irmão com o nome local e URI de namespace especificados. |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | Move o [XPathNavigator](./) para o próximo nó irmão do nó atual que corresponde ao XPathNodeType especificado. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | Quando sobrescrito em uma classe derivada, move o [XPathNavigator](./) para o próximo atributo. |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Quando sobrescrito em uma classe derivada, move o [XPathNavigator](./) para o próximo nó de namespace que corresponde ao XPathNamespaceScope especificado. |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | Move o [XPathNavigator](./) para o próximo nó de namespace. |
| virtual **bool** [MoveToParent](./movetoparent/)() | Quando sobrescrito em uma classe derivada, move o [XPathNavigator](./) para o nó pai do nó atual. |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | Quando sobrescrito em uma classe derivada, move o [XPathNavigator](./) para o nó irmão anterior do nó atual. |
| virtual void [MoveToRoot](./movetoroot/)() | Move o [XPathNavigator](./) para o nó raiz ao qual o nó atual pertence. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | Retorna um objeto [XmlWriter](../../system.xml/xmlwriter/) usado para criar um novo nó filho no início da lista de nós filhos do nó atual. |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | Cria um novo nó filho no início da lista de nós filhos do nó atual usando a string XML especificada. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Cria um novo nó filho no início da lista de nós filhos do nó atual usando o conteúdo XML do objeto [XmlReader](../../system.xml/xmlreader/) especificado. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Cria um novo nó filho no início da lista de nós filhos do nó atual usando os nós do objeto [XPathNavigator](./) especificado. |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Cria um novo elemento filho no início da lista de nós filhos do nó atual usando o prefixo de namespace, nome local e URI de namespace especificados com o valor especificado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | Retorna um objeto [XmlReader](../../system.xml/xmlreader/) que contém o nó atual e seus nós filhos. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui a contagem de referência compartilhada pelo valor especificado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Substitui um intervalo de nós irmãos do nó atual até o nó especificado. |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | Substitui o nó atual pelo conteúdo da string especificada. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Substitui o nó atual pelo conteúdo do objeto [XmlReader](../../system.xml/xmlreader/) especificado. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Substitui o nó atual pelo conteúdo do objeto [XPathNavigator](./) especificado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | Seleciona um conjunto de nós, usando a expressão [XPath](../) especificada. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Seleciona um conjunto de nós usando a expressão [XPath](../) especificada com o objeto [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) especificado para resolver prefixos de namespace. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Seleciona um conjunto de nós usando o [XPathExpression](../xpathexpression/) especificado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | Seleciona todos os nós antecessores do nó atual que têm um XPathNodeType correspondente. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | Seleciona todos os nós antecessores do nó atual que têm o nome local e URI de namespace especificados. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | Seleciona todos os nós filhos do nó atual que têm o XPathNodeType correspondente. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | Seleciona todos os nós filhos do nó atual que têm o nome local e URI de namespace especificados. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | Seleciona todos os nós descendentes do nó atual que têm um XPathNodeType correspondente. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | Seleciona todos os nós descendentes do nó atual com o nome local e URI de namespace especificados. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | Seleciona um único nó no [XPathNavigator](./) usando a consulta [XPath](../) especificada. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Seleciona um único nó no objeto [XPathNavigator](./) usando a consulta [XPath](../) especificada com o objeto [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) especificado para resolver prefixos de namespace. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Seleciona um único nó no [XPathNavigator](./) usando o objeto [XPathExpression](../xpathexpression/) especificado. |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | Define a marcação que representa os nós filhos do nó atual. |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | Define a marcação que representa as tags de abertura e fechamento do nó atual e seus nós filhos. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Define o valor tipado do nó atual. |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | Define o valor do nó atual. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual da contagem de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa a contagem de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna a contagem de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Retorna o valor de texto do nó atual. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | Retorna o valor do nó atual como o Tipo especificado, usando o objeto [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) especificado para resolver prefixos de namespace. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | Retorna o valor do item como o tipo especificado. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa a contagem de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa a contagem de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | Transmite o nó atual e seus nós filhos para o objeto [XmlWriter](../../system.xml/xmlwriter/) especificado. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Tipos

| Typedef | Descrição |
| --- | --- |
| [Ptr](./ptr/) | Um alias para ponteiro compartilhado para uma instância desta classe. |

## Veja Também

* Classe [XPathItem](../xpathitem/)
* Classe [IXPathNavigable](../ixpathnavigable/)
* Classe [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* Espaço de nomes [System::Xml::XPath](../)
* Biblioteca [Aspose.Slides](../../)