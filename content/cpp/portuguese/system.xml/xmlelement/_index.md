---
title: XmlElement
second_title: Referência da API Aspose.Slides para C++
description: Representa um elemento.
type: docs
weight: 222
url: /pt/system.xml/xmlelement/
---
## XmlElement classe

Representa um elemento.

```cpp
class XmlElement : public System::Xml::XmlLinkedNode
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Adiciona o nó especificado ao final da lista de nós filho deste nó. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Obtém um iterador apontando para o primeiro elemento (se houver) da coleção. Este iterador não pode ser usado para alterar um objeto referenciado porque [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) retorna um objeto cópia de T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Obtém um iterador apontando para o primeiro elemento (se houver) da instância da coleção qualificada como const. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Obtém um iterador apontando para o primeiro elemento qualificado como const (se houver) da coleção. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Obtém um iterador apontando logo após o último elemento qualificado como const (se houver) da coleção. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | Cria uma duplicata deste nó. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](./clonenode/)(**bool**) override | Cria uma duplicata deste nó. |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](../xmlnode/createnavigator/)() override | Cria um XPathNavigator para navegar neste objeto. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Obtém um iterador apontando logo após o último elemento (se houver) da coleção. Este iterador não pode ser usado para alterar um objeto referenciado porque [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) retorna um objeto cópia de T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Obtém um iterador apontando logo após o último elemento (se houver) da instância da coleção qualificada como const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | Retorna um [XmlAttributeCollection](../xmlattributecollection/) contendo os atributos deste nó. |
| virtual [String](../../system/string/) [get_BaseURI](../xmlnode/get_baseuri/)() | Retorna o URI base do nó atual. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | Retorna todos os nós filho do nó. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | Retorna o primeiro filho do nó. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Retorna um valor **bool** indicando se o nó atual possui algum atributo. |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | Retorna um valor indicando se este nó possui nós filho. |
| [String](../../system/string/) [get_InnerText](./get_innertext/)() override | Retorna os valores concatenados do nó e de todos os seus filhos. |
| [String](../../system/string/) [get_InnerXml](./get_innerxml/)() override | Retorna a marcação que representa apenas os filhos deste nó. |
| **bool** [get_IsEmpty](./get_isempty/)() | Retorna o formato da tag do elemento. |
| virtual **bool** [get_IsReadOnly](../xmlnode/get_isreadonly/)() | Retorna um valor indicando se o nó é somente leitura. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | Retorna o último filho do nó. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Retorna o nome local do nó atual. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Retorna o nome qualificado do nó. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Retorna o URI do namespace deste nó. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | Retorna o nó imediatamente seguinte a este nó. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Retorna o tipo do nó atual. |
| virtual [String](../../system/string/) [get_OuterXml](../xmlnode/get_outerxml/)() | Retorna a marcação que contém este nó e todos os seus nós filho. |
| [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](./get_ownerdocument/)() override | Retorna o [XmlDocument](../xmldocument/) ao qual este nó pertence. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | Retorna o pai deste nó (para nós que podem ter pais). |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Retorna o prefixo do namespace deste nó. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | Retorna o nó imediatamente anterior a este nó. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](../xmlnode/get_previoustext/)() | Retorna o nó de texto que precede imediatamente este nó. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | Retorna o conjunto de informações de validação de esquema posterior que foi atribuído a este nó como resultado da validação de esquema. |
| virtual [String](../../system/string/) [get_Value](../xmlnode/get_value/)() | Retorna o valor do nó. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | Retorna o valor do atributo com o nome especificado. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Retorna o valor do atributo com o nome local e o URI do namespace especificados. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [GetAttributeNode](./getattributenode/)([String](../../system/string/)) | Retorna o [XmlAttribute](../xmlattribute/) com o nome especificado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [GetAttributeNode](./getattributenode/)([String](../../system/string/), [String](../../system/string/)) | Retorna o [XmlAttribute](../xmlattribute/) com o nome local e o URI do namespace especificados. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [GetElementsByTagName](./getelementsbytagname/)([String](../../system/string/)) | Retorna um [XmlNodeList](../xmlnodelist/) contendo uma lista de todos os elementos descendentes que correspondem ao [XmlElement::get_Name](./get_name/) especificado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [GetElementsByTagName](./getelementsbytagname/)([String](../../system/string/), [String](../../system/string/)) | Retorna um [XmlNodeList](../xmlnodelist/) contendo uma lista de todos os elementos descendentes que correspondem aos valores [XmlElement::get_LocalName](./get_localname/) e [XmlElement::get_NamespaceURI](./get_namespaceuri/) especificados. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | Retorna um enumerador que itera pelos nós filho no nó atual. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite a geração de hash de objetos personalizados. |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | Procura a declaração **xmlns** mais próxima para o prefixo fornecido que está no escopo deste nó e retorna o URI do namespace na declaração. |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | Procura a declaração **xmlns** mais próxima para o URI do namespace fornecido que está no escopo deste nó e retorna o prefixo definido nessa declaração. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [HasAttribute](./hasattribute/)([String](../../system/string/)) | Determina se o nó atual possui um atributo com o nome especificado. |
| virtual **bool** [HasAttribute](./hasattribute/)([String](../../system/string/), [String](../../system/string/)) | Determina se o nó atual possui um atributo com o nome local e o URI do namespace especificados. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](./)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | Retorna o primeiro elemento filho com o [XmlNode::get_Name](../xmlnode/get_name/) especificado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](./)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Retorna o primeiro elemento filho com os valores [XmlNode::get_LocalName](../xmlnode/get_localname/) e [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) especificados. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Insere o nó especificado imediatamente após o nó de referência especificado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Insere o nó especificado imediatamente antes do nó de referência especificado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Aplica uma função acumuladora sobre uma sequência. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Determina se todos os elementos de uma sequência satisfazem uma condição. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Determina se uma sequência contém algum elemento. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Determina se algum elemento de uma sequência existe ou satisfaz uma condição. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Computa a média de uma sequência de valores numéricos. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Computa a média de uma sequência de valores obtidos ao invocar uma função de transformação em cada elemento da sequência de entrada. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Converte os elementos para o tipo especificado. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Concatena duas sequências. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Determina se uma sequência contém um valor especificado. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Retorna o número de elementos na sequência (calculado via contagem direta). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Retorna o número de elementos na sequência que satisfazem a condição especificada. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Retorna o elemento em um índice especificado em uma sequência. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Retorna o elemento em um índice especificado em uma sequência. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Retorna o primeiro elemento de uma sequência. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Retorna o primeiro elemento de uma sequência que satisfaz a condição especificada. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Retorna o primeiro elemento de uma sequência, ou um valor padrão se a sequência estiver vazia. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Retorna o primeiro elemento da sequência que satisfaz uma condição ou um valor padrão se nenhum elemento for encontrado. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Agrupa os elementos de uma sequência. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Agrupa os elementos de uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Retorna o último elemento de uma sequência. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Retorna o último elemento de uma sequência, ou um valor padrão se a sequência estiver vazia. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoca uma função de transformação em cada elemento de uma sequência genérica e retorna o valor máximo resultante. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoca uma função de transformação em cada elemento de uma sequência genérica e retorna o valor mínimo resultante. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtra os elementos da sequência com base no tipo especificado. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordena os elementos de uma sequência em ordem crescente de acordo com os valores de chave selecionados por keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordena os elementos de uma sequência em ordem decrescente de acordo com os valores de chave selecionados por keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Inverte a ordem dos elementos em uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transforma os elementos de uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transforma cada elemento de uma sequência em uma nova forma incorporando o índice do elemento. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projeta cada elemento de uma sequência e combina as sequências resultantes em uma única sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Ignora um número especificado de elementos contíguos do início de uma sequência e retorna o restante. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Retorna um número especificado de elementos contíguos do início de uma sequência. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Cria um array a partir de uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Cria um List<T> a partir de uma sequência. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtra uma sequência com base no predicado especificado. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| virtual void [Normalize](../xmlnode/normalize/)() | Coloca todos os nós [XmlText](../xmltext/) em toda a profundidade da sub-árvore abaixo deste [XmlNode](../xmlnode/) em uma forma "normal" onde apenas marcação (ou seja, tags, comentários, instruções de processamento, seções CDATA e referências de entidade) separa nós [XmlText](../xmltext/), isto é, não há nós [XmlText](../xmltext/) adjacentes. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Adiciona o nó especificado ao início da lista de nós filhos deste nó. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto do tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| void [RemoveAll](./removeall/)() override | Remove todos os atributos especificados e filhos do nó atual. Atributos padrão não são removidos. |
| virtual void [RemoveAllAttributes](./removeallattributes/)() | Remove todos os atributos especificados do elemento. Atributos padrão não são removidos. |
| virtual void [RemoveAttribute](./removeattribute/)([String](../../system/string/)) | Remove um atributo pelo nome. |
| virtual void [RemoveAttribute](./removeattribute/)([String](../../system/string/), [String](../../system/string/)) | Remove um atributo com o nome local e URI de namespace especificados. (Se o atributo removido tem um valor padrão, ele é imediatamente substituído). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveAttributeAt](./removeattributeat/)(**int32_t**) | Remove o nó de atributo com o índice especificado do elemento. (Se o atributo removido tem um valor padrão, ele é imediatamente substituído). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [RemoveAttributeNode](./removeattributenode/)([SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\>) | Remove o [XmlAttribute](../xmlattribute/) especificado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [RemoveAttributeNode](./removeattributenode/)([String](../../system/string/), [String](../../system/string/)) | Remove o [XmlAttribute](../xmlattribute/) especificado pelo nome local e URI de namespace. (Se o atributo removido tem um valor padrão, ele é imediatamente substituído). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Remove o nó filho especificado. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui a contagem de referência compartilhada em um valor especificado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Substitui o nó filho **oldChild** pelo nó **newChild**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | Seleciona uma lista de nós que correspondem à expressão [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Seleciona uma lista de nós que correspondem à expressão [XPath](../../system.xml.xpath/). Quaisquer prefixos encontrados na expressão [XPath](../../system.xml.xpath/) são resolvidos usando o [XmlNamespaceManager](../xmlnamespacemanager/) fornecido. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | Seleciona o primeiro [XmlNode](../xmlnode/) que corresponde à expressão [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Seleciona o primeiro [XmlNode](../xmlnode/) que corresponde à expressão [XPath](../../system.xml.xpath/). Quaisquer prefixos encontrados na expressão [XPath](../../system.xml.xpath/) são resolvidos usando o [XmlNamespaceManager](../xmlnamespacemanager/) fornecido. |
| void [set_InnerText](./set_innertext/)([String](../../system/string/)) override | Define os valores concatenados do nó e de todos os seus filhos. |
| void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) override | Define a marcação que representa apenas os filhos deste nó. |
| void [set_IsEmpty](./set_isempty/)(**bool**) | Define o formato da tag do elemento. |
| void [set_Prefix](./set_prefix/)([String](../../system/string/)) override | Define o prefixo de namespace deste nó. |
| virtual void [set_Value](../xmlnode/set_value/)([String](../../system/string/)) | Define o valor do nó. |
| virtual void [SetAttribute](./setattribute/)([String](../../system/string/), [String](../../system/string/)) | Define o valor do atributo com o nome especificado. |
| virtual [String](../../system/string/) [SetAttribute](./setattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Define o valor do atributo com o nome local e URI de namespace especificados. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [SetAttributeNode](./setattributenode/)([SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\>) | Adiciona o [XmlAttribute](../xmlattribute/) especificado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [SetAttributeNode](./setattributenode/)([String](../../system/string/), [String](../../system/string/)) | Adiciona o [XmlAttribute](../xmlattribute/) especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa a contagem de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna a contagem de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | Teste se a implementação DOM suporta um recurso específico. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentry [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | Obtém a implementação do iterador begin const para o contêiner atual. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | Obtém a implementação do iterador begin para o contêiner atual. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | Obtém a implementação do iterador end const para o contêiner atual. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | Obtém a implementação do iterador end para o contêiner atual. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa a contagem de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa a contagem de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Salva todos os filhos do nó no [XmlWriter](../xmlwriter/) especificado. |
| void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Salva o nó atual no [XmlWriter](../xmlwriter/) especificado. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |
## Tipos Definidos

| Typedef | Descrição |
| --- | --- |
| [Ptr](./ptr/) | Um alias para ponteiro compartilhado a uma instância desta classe. |
## Observações



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## Veja Também

* Classe [XmlLinkedNode](../xmllinkednode/)
* Namespace [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)