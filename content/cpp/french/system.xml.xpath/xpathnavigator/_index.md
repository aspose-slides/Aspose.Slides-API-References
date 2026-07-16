---
title: XPathNavigator
second_title: Référence de l'API Aspose.Slides pour C++
description: Fournit un modèle de curseur pour naviguer et modifier des données XML.
type: docs
weight: 66
url: /fr/system.xml.xpath/xpathnavigator/
---
## classe XPathNavigator

Fournit un modèle de curseur pour naviguer et modifier des données XML.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | Renvoie un objet [XmlWriter](../../system.xml/xmlwriter/) utilisé pour créer un ou plusieurs nouveaux nœuds enfants à la fin de la liste des nœuds enfants du nœud actuel. |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | Crée un nouveau nœud enfant à la fin de la liste des nœuds enfants du nœud actuel en utilisant la chaîne de données XML spécifiée. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Crée un nouveau nœud enfant à la fin de la liste des nœuds enfants du nœud actuel en utilisant le contenu XML de l'objet [XmlReader](../../system.xml/xmlreader/) spécifié. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Crée un nouveau nœud enfant à la fin de la liste des nœuds enfants du nœud actuel en utilisant les nœuds du [XPathNavigator](./) spécifié. |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Crée un nouveau nœud d'élément enfant à la fin de la liste des nœuds enfants du nœud actuel en utilisant le préfixe d'espace de noms, le nom local et l'URI d'espace de noms spécifiés avec la valeur indiquée. |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | Vérifie que les données XML dans [XPathNavigator](./) sont conformes au schéma de langage de définition XML [Schema](../../system.xml.schema/) (XSD) fourni. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | Lorsqu'il est remplacé dans une classe dérivée, crée un nouveau [XPathNavigator](./) positionné au même nœud que ce [XPathNavigator](./). |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Compare la position du [XPathNavigator](./) actuel avec la position du [XPathNavigator](./) spécifié. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | Compile une chaîne représentant une expression [XPath](../) et renvoie un objet [XPathExpression](../xpathexpression/). |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Crée un nœud d'attribut sur le nœud d'élément actuel en utilisant le préfixe d'espace de noms, le nom local et l'URI d'espace de noms spécifiés avec la valeur indiquée. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | Renvoie un objet [XmlWriter](../../system.xml/xmlwriter/) utilisé pour créer de nouveaux attributs sur l'élément actuel. |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | Renvoie une copie du [XPathNavigator](./). |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Supprime une plage de nœuds frères du nœud actuel jusqu'au nœud spécifié. |
| virtual void [DeleteSelf](./deleteself/)() | Supprime le nœud actuel ainsi que ses nœuds enfants. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés comme égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés comme égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | Évalue l'expression [XPath](../) spécifiée et renvoie le résultat typé. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Évalue l'expression [XPath](../) spécifiée et renvoie le résultat typé, en utilisant l'objet [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) spécifié pour résoudre les préfixes d'espace de noms dans l'expression [XPath](../). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Évalue le [XPathExpression](../xpathexpression/) et renvoie le résultat typé. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | Utilise le contexte fourni pour évaluer le [XPathExpression](../xpathexpression/) et renvoie le résultat typé. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Lorsqu'il est remplacé dans une classe dérivée, obtient l'URI de base du nœud actuel. |
| virtual **bool** [get_CanEdit](./get_canedit/)() | Renvoie une valeur indiquant si le [XPathNavigator](./) peut modifier les données XML sous-jacentes. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Renvoie une valeur indiquant si le nœud actuel possède des attributs. |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | Renvoie une valeur indiquant si le nœud actuel possède des nœuds enfants. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | Renvoie le balisage représentant les nœuds enfants du nœud actuel. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | Lorsqu'il est remplacé dans une classe dérivée, obtient une valeur indiquant si le nœud actuel est un élément vide sans balise de fin d'élément. |
| **bool** [get_IsNode](./get_isnode/)() override | Renvoie une valeur indiquant si le nœud actuel représente un nœud [XPath](../). |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | Lorsqu'il est remplacé dans une classe dérivée, obtient le [XPathNavigator::get_Name](./get_name/) du nœud actuel sans aucun préfixe d'espace de noms. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Lorsqu'il est remplacé dans une classe dérivée, obtient le nom qualifié du nœud actuel. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | Lorsqu'il est remplacé dans une classe dérivée, obtient l'URI d'espace de noms du nœud actuel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | Lorsqu'il est remplacé dans une classe dérivée, obtient le [XmlNameTable](../../system.xml/xmlnametable/) du [XPathNavigator](./). |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | Renvoie un [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) utilisé pour la comparaison d'égalité des objets [XPathNavigator](./). |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | Lorsqu'il est remplacé dans une classe dérivée, obtient le XPathNodeType du nœud actuel. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | Renvoie le balisage représentant les balises d'ouverture et de fermeture du nœud actuel et de ses nœuds enfants. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | Lorsqu'il est remplacé dans une classe dérivée, obtient le préfixe d'espace de noms associé au nœud actuel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Renvoie les informations de schéma qui ont été attribuées au nœud actuel à la suite de la validation du schéma. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | Renvoie le nœud actuel sous forme d'objet encapsulé du type le plus approprié. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | Utilisé par les implémentations [XPathNavigator](./) qui offrent une vue XML « virtualisée » sur un magasin, pour fournir l'accès aux objets sous-jacents. |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | Lorsqu'il est remplacé dans une classe dérivée, obtient la valeur **string** de l'élément. |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | Renvoie la valeur du nœud actuel en tant que [Boolean](../../system/boolean/). |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | Renvoie la valeur du nœud actuel en tant que [DateTime](../../system/datetime/). |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | Renvoie la valeur du nœud actuel en tant que [Double](../../system/double/). |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | Renvoie la valeur du nœud actuel en tant que [Int32](../../system/int32/). |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | Renvoie la valeur du nœud actuel en tant que [Int64](../../system/int64/). |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | Renvoie le type du nœud actuel. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Renvoie la portée **xml:lang** du nœud actuel. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | Renvoie les informations XmlSchemaType du nœud actuel. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Renvoie la valeur de l'attribut ayant le nom local et l'URI d'espace de noms spécifiés. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | Renvoie la valeur du nœud d'espace de noms correspondant au nom local spécifié. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | Renvoie les espaces de noms en portée du nœud actuel. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | Renvoie un objet [XmlWriter](../../system.xml/xmlwriter/) utilisé pour créer un nouveau nœud frère après le nœud actuellement sélectionné. |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | Crée un nouveau nœud frère après le nœud actuellement sélectionné en utilisant la chaîne XML spécifiée. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Crée un nouveau nœud frère après le nœud actuellement sélectionné en utilisant le contenu XML de l'objet [XmlReader](../../system.xml/xmlreader/) spécifié. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Crée un nouveau nœud frère après le nœud actuellement sélectionné en utilisant les nœuds de l'objet [XPathNavigator](./) spécifié. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | Renvoie un objet [XmlWriter](../../system.xml/xmlwriter/) utilisé pour créer un nouveau nœud frère avant le nœud actuellement sélectionné. |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | Crée un nouveau nœud frère avant le nœud actuellement sélectionné en utilisant la chaîne XML spécifiée. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Crée un nouveau nœud frère avant le nœud actuellement sélectionné en utilisant le contenu XML de l'objet [XmlReader](../../system.xml/xmlreader/) spécifié. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Crée un nouveau nœud frère avant le nœud actuellement sélectionné en utilisant les nœuds du [XPathNavigator](./) spécifié. |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Crée un nouvel élément frère après le nœud actuel en utilisant le préfixe d'espace de noms, le nom local et l'URI d'espace de noms spécifiés, avec la valeur indiquée. |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Crée un nouvel élément frère avant le nœud actuel en utilisant le préfixe d'espace de noms, le nom local et l'URI d'espace de noms spécifiés, avec la valeur indiquée. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Détermine si le [XPathNavigator](./) spécifié est un descendant du [XPathNavigator](./) actuel. |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Lorsqu'il est remplacé dans une classe dérivée, détermine si le [XPathNavigator](./) actuel est à la même position que le [XPathNavigator](./) spécifié. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Renvoie l'URI d'espace de noms pour le préfixe spécifié. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | Renvoie le préfixe déclaré pour l'URI d'espace de noms spécifié. |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Détermine si le nœud actuel correspond au [XPathExpression](../xpathexpression/) spécifié. |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | Détermine si le nœud actuel correspond à l'expression [XPath](../) spécifiée. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Lorsqu'il est remplacé dans une classe dérivée, déplace le [XPathNavigator](./) à la même position que le [XPathNavigator](./) spécifié. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | Déplace le [XPathNavigator](./) vers l'attribut ayant le même nom local et l'URI d'espace de noms. |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | Déplace le [XPathNavigator](./) vers le nœud enfant ayant le nom local et l'URI d'espace de noms spécifiés. |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | Déplace le [XPathNavigator](./) vers le nœud enfant du XPathNodeType spécifié. |
| virtual **bool** [MoveToFirst](./movetofirst/)() | Déplace le [XPathNavigator](./) vers le premier nœud frère du nœud actuel. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | Lorsqu'il est remplacé dans une classe dérivée, déplace le [XPathNavigator](./) vers le premier attribut du nœud actuel. |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | Lorsqu'il est remplacé dans une classe dérivée, déplace le [XPathNavigator](./) vers le premier nœud enfant du nœud actuel. |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Lorsqu'il est remplacé dans une classe dérivée, déplace le [XPathNavigator](./) vers le premier nœud d'espace de noms correspondant au XPathNamespaceScope spécifié. |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | Déplace le [XPathNavigator](./) vers le premier nœud d'espace de noms du nœud actuel. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | Déplace le [XPathNavigator](./) vers l'élément ayant le nom local et l'URI d'espace de noms spécifiés dans l'ordre du document. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Déplace le [XPathNavigator](./) vers l'élément ayant le nom local et l'URI d'espace de noms spécifiés, jusqu'à la limite spécifiée, dans l'ordre du document. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | Déplace le [XPathNavigator](./) vers l'élément suivant du XPathNodeType spécifié dans l'ordre du document. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Déplace le [XPathNavigator](./) vers l'élément suivant du XPathNodeType spécifié, jusqu'à la limite indiquée, dans l'ordre du document. |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | Lorsqu'il est remplacé dans une classe dérivée, se déplace vers le nœud qui possède un attribut de type **ID** dont la valeur correspond au [String](../../system/string/) spécifié. |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | Déplace le [XPathNavigator](./) vers le nœud d'espace de noms ayant le préfixe d'espace de noms spécifié. |
| virtual **bool** [MoveToNext](./movetonext/)() | Lorsqu'il est remplacé dans une classe dérivée, déplace le [XPathNavigator](./) vers le nœud frère suivant du nœud actuel. |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | Déplace le [XPathNavigator](./) vers le nœud frère suivant ayant le nom local et l'URI d'espace de noms spécifiés. |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | Déplace le [XPathNavigator](./) vers le nœud frère suivant du nœud actuel qui correspond au XPathNodeType spécifié. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | Lorsqu'il est remplacé dans une classe dérivée, déplace le [XPathNavigator](./) vers l'attribut suivant. |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Lorsqu'il est remplacé dans une classe dérivée, déplace le [XPathNavigator](./) vers le prochain nœud d'espace de noms correspondant au XPathNamespaceScope spécifié. |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | Déplace le [XPathNavigator](./) vers le nœud d'espace de noms suivant. |
| virtual **bool** [MoveToParent](./movetoparent/)() | Lorsqu'il est remplacé dans une classe dérivée, déplace le [XPathNavigator](./) vers le nœud parent du nœud actuel. |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | Lorsqu'il est remplacé dans une classe dérivée, déplace le [XPathNavigator](./) vers le nœud frère précédent du nœud actuel. |
| virtual void [MoveToRoot](./movetoroot/)() | Déplace le [XPathNavigator](./) vers le nœud racine auquel appartient le nœud actuel. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la construction copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la construction copie des sous-classes. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | Renvoie un objet [XmlWriter](../../system.xml/xmlwriter/) utilisé pour créer un nouveau nœud enfant au début de la liste des nœuds enfants du nœud actuel. |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | Crée un nouveau nœud enfant au début de la liste des nœuds enfants du nœud actuel en utilisant la chaîne XML spécifiée. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Crée un nouveau nœud enfant au début de la liste des nœuds enfants du nœud actuel en utilisant le contenu XML de l'objet [XmlReader](../../system.xml/xmlreader/) spécifié. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Crée un nouveau nœud enfant au début de la liste des nœuds enfants du nœud actuel en utilisant les nœuds de l'objet [XPathNavigator](./) spécifié. |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Crée un nouvel élément enfant au début de la liste des nœuds enfants du nœud actuel en utilisant le préfixe d'espace de noms, le nom local et l'URI d'espace de noms spécifiés avec la valeur indiquée. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | Renvoie un objet [XmlReader](../../system.xml/xmlreader/) contenant le nœud actuel et ses nœuds enfants. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Remplace une plage de nœuds frères du nœud actuel jusqu'au nœud spécifié. |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | Remplace le nœud actuel par le contenu de la chaîne spécifiée. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Remplace le nœud actuel par le contenu de l'objet [XmlReader](../../system.xml/xmlreader/) spécifié. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Remplace le nœud actuel par le contenu de l'objet [XPathNavigator](./) spécifié. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | Sélectionne un ensemble de nœuds à l'aide de l'expression [XPath](../) spécifiée. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Sélectionne un ensemble de nœuds à l'aide de l'expression [XPath](../) spécifiée avec l'objet [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) destiné à résoudre les préfixes d'espace de noms. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Sélectionne un ensemble de nœuds à l'aide du [XPathExpression](../xpathexpression/) spécifié. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | Sélectionne tous les nœuds ancêtres du nœud actuel ayant un XPathNodeType correspondant. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | Sélectionne tous les nœuds ancêtres du nœud actuel ayant le nom local et l'URI d'espace de noms spécifiés. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | Sélectionne tous les nœuds enfants du nœud actuel ayant le XPathNodeType correspondant. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | Sélectionne tous les nœuds enfants du nœud actuel ayant le nom local et l'URI d'espace de noms spécifiés. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | Sélectionne tous les nœuds descendants du nœud actuel ayant un XPathNodeType correspondant. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | Sélectionne tous les nœuds descendants du nœud actuel avec le nom local et l'URI d'espace de noms spécifiés. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | Sélectionne un seul nœud dans le [XPathNavigator](./) à l'aide de la requête [XPath](../) spécifiée. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Sélectionne un seul nœud dans l'objet [XPathNavigator](./) à l'aide de la requête [XPath](../) spécifiée avec l'objet [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) destiné à résoudre les préfixes d'espace de noms. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Sélectionne un seul nœud dans le [XPathNavigator](./) à l'aide de l'objet [XPathExpression](../xpathexpression/) spécifié. |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | Définit le balisage représentant les nœuds enfants du nœud actuel. |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | Définit le balisage représentant les balises d'ouverture et de fermeture du nœud actuel et de ses nœuds enfants. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de passer les pointeurs des conteneurs en mode faible. |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Définit la valeur typée du nœud actuel. |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | Définit la valeur du nœud actuel. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Renvoie la valeur texte du nœud actuel. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | Renvoie la valeur du nœud actuel en tant que Type spécifié, en utilisant l'objet [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) destiné à résoudre les préfixes d'espace de noms. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | Renvoie la valeur de l'élément en tant que type spécifié. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | Diffuse le nœud actuel et ses nœuds enfants vers l'objet [XmlWriter](../../system.xml/xmlwriter/) spécifié. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Alias de type

| Alias | Description |
| --- | --- |
| [Ptr](./ptr/) | Un alias pour un pointeur partagé vers une instance de cette classe. |

## Voir aussi

* Classe [XPathItem](../xpathitem/)
* Classe [IXPathNavigable](../ixpathnavigable/)
* Classe [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.Slides](../../)