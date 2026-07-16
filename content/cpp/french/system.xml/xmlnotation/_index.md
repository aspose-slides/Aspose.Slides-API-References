---
title: XmlNotation
second_title: Référence API Aspose.Slides pour C++
description: Représente une déclaration de notation, telle que <!NOTATION... >.
type: docs
weight: 378
url: /fr/system.xml/xmlnotation/
---
## XmlNotation classe


Represents a notation declaration, such as **<!NOTATION... >**.

```cpp
class XmlNotation : public System::Xml::XmlNode
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Ajoute le nœud spécifié à la fin de la liste des nœuds enfants de ce nœud. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Obtient l'itérateur pointant vers le premier élément (le cas échéant) de la collection. Cet itérateur ne peut pas être utilisé pour modifier un objet référencé car [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) renvoie une copie-objet de T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Obtient l'itérateur pointant vers le premier élément (le cas échéant) de l'instance en lecture seule de la collection. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Obtient l'itérateur pointant vers le premier élément en lecture seule (le cas échéant) de la collection. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Obtient l'itérateur pointant juste après le dernier élément en lecture seule (le cas échéant) de la collection. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | Crée un duplicata de ce nœud. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](./clonenode/)(**bool**) override | Crée un duplicata de ce nœud. Les nœuds de notation ne peuvent pas être clonés. Appeler cette méthode sur un objet [XmlNotation](./) lève une exception. |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](../xmlnode/createnavigator/)() override | Crée un XPathNavigator pour parcourir cet objet. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Obtient l'itérateur pointant juste après le dernier élément (le cas échéant) de la collection. Cet itérateur ne peut pas être utilisé pour modifier un objet référencé car [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) renvoie une copie-objet de T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Obtient l'itérateur pointant juste après le dernier élément (le cas échéant) de l'instance en lecture seule de la collection. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | Retourne un [XmlAttributeCollection](../xmlattributecollection/) contenant les attributs de ce nœud. |
| virtual [String](../../system/string/) [get_BaseURI](../xmlnode/get_baseuri/)() | Retourne l’URI de base du nœud actuel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | Retourne tous les nœuds enfants du nœud. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | Retourne le premier enfant du nœud. |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | Retourne une valeur indiquant si ce nœud possède des nœuds enfants. |
| virtual [String](../../system/string/) [get_InnerText](../xmlnode/get_innertext/)() | Retourne les valeurs concaténées du nœud et de tous ses nœuds enfants. |
| [String](../../system/string/) [get_InnerXml](./get_innerxml/)() override | Retourne le balisage représentant les enfants de ce nœud. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() override | Retourne une valeur indiquant si le nœud est en lecture seule. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | Retourne le dernier enfant du nœud. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Retourne le nom du nœud actuel sans le préfixe de l’espace de noms. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Retourne le nom du nœud actuel. |
| virtual [String](../../system/string/) [get_NamespaceURI](../xmlnode/get_namespaceuri/)() | Retourne l’URI de l’espace de noms de ce nœud. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | Retourne le nœud immédiatement suivant ce nœud. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Retourne le type du nœud actuel. |
| [String](../../system/string/) [get_OuterXml](./get_outerxml/)() override | Retourne le balisage représentant ce nœud et tous ses enfants. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](../xmlnode/get_ownerdocument/)() | Retourne le [XmlDocument](../xmldocument/) auquel ce nœud appartient. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | Retourne le parent de ce nœud (pour les nœuds pouvant avoir des parents). |
| virtual [String](../../system/string/) [get_Prefix](../xmlnode/get_prefix/)() | Retourne le préfixe d’espace de noms de ce nœud. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | Retourne le nœud immédiatement précédent ce nœud. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](../xmlnode/get_previoustext/)() | Retourne le nœud texte qui précède immédiatement ce nœud. |
| [String](../../system/string/) [get_PublicId](./get_publicid/)() | Retourne la valeur de l’identifiant public dans la déclaration de notation. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlnode/get_schemainfo/)() | Retourne le jeu d’informations post-validation de schéma assigné à ce nœud à la suite d’une validation de schéma. |
| [String](../../system/string/) [get_SystemId](./get_systemid/)() | Retourne la valeur de l’identifiant système dans la déclaration de notation. |
| virtual [String](../../system/string/) [get_Value](../xmlnode/get_value/)() | Retourne la valeur du nœud. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | Retourne un énumérateur qui parcourt les nœuds enfants du nœud actuel. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d’objets personnalisés. |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | Recherche la déclaration **xmlns** la plus proche pour le préfixe donné qui est en portée pour le nœud actuel et renvoie l’URI d’espace de noms dans la déclaration. |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | Recherche la déclaration **xmlns** la plus proche pour l’URI d’espace de noms donné qui est en portée pour le nœud actuel et renvoie le préfixe défini dans cette déclaration. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | Retourne le premier élément enfant avec le [XmlNode::get_Name](../xmlnode/get_name/) spécifié. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Retourne le premier élément enfant avec les valeurs [XmlNode::get_LocalName](../xmlnode/get_localname/) et [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) spécifiées. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Insère le nœud spécifié immédiatement après le nœud de référence spécifié. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Insère le nœud spécifié immédiatement avant le nœud de référence spécifié. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Applique une fonction accumulateur sur une séquence. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Détermine si tous les éléments d’une séquence satisfont une condition. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Détermine si une séquence contient des éléments. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Détermine si un élément d’une séquence existe ou satisfait une condition. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Convertit les éléments au type spécifié. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Concatène deux séquences. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Détermine si une séquence contient une valeur spécifiée. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Retourne le nombre d’éléments dans la séquence (calculé par comptage direct). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Retourne le nombre d’éléments dans la séquence qui satisfont la condition spécifiée. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Retourne l’élément à l’index spécifié dans une séquence. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Retourne l’élément à l’index spécifié dans une séquence. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Retourne le premier élément d’une séquence. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Retourne le premier élément d’une séquence qui satisfait la condition spécifiée. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Retourne le premier élément d’une séquence, ou une valeur par défaut si la séquence est vide. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Retourne le premier élément de la séquence qui satisfait une condition ou une valeur par défaut si aucun élément ne correspond. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Regroupe les éléments d’une séquence. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Regroupe les éléments d’une séquence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Retourne le dernier élément d’une séquence. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Retourne le dernier élément d’une séquence, ou une valeur par défaut si la séquence est vide. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoque une fonction de transformation sur chaque élément d’une séquence générique et retourne la valeur maximale résultante. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoque une fonction de transformation sur chaque élément d’une séquence générique et retourne la valeur minimale résultante. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtre les éléments de la séquence en fonction du type spécifié. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Trie les éléments d’une séquence par ordre croissant selon les valeurs de clé sélectionnées par keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Trie les éléments d’une séquence par ordre décroissant selon les valeurs de clé sélectionnées par keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Inverse l’ordre des éléments d’une séquence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transforme les éléments d’une séquence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transforme chaque élément d’une séquence en une nouvelle forme en incorporant l’indice de l’élément. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projette chaque élément d’une séquence et combine les séquences résultantes en une seule séquence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Retourne un nombre spécifié d’éléments contigus depuis le début d’une séquence. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Crée un tableau à partir d’une séquence. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Crée une List<T> à partir d’une séquence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtre une séquence selon le prédicat spécifié. |
| void [Lock](../../system/object/lock/)() | Implémente l’instruction C# lock() de verrouillage. Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
| virtual void [Normalize](../xmlnode/normalize/)() | Met tous les nœuds [XmlText](../xmltext/) de la profondeur totale du sous-arbre sous ce [XmlNode](../xmlnode/) dans une forme « normale » où seul le balisage (c’est-à-dire les balises, les commentaires, les instructions de traitement, les sections CDATA et les références d’entité) sépare les nœuds [XmlText](../xmltext/), c’est-à-dire qu’il n’y a pas de nœuds [XmlText](../xmltext/) adjacents. |
|  [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la copie des sous-classes. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Ajoute le nœud spécifié au début de la liste des nœuds enfants pour ce nœud. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| virtual void [RemoveAll](../xmlnode/removeall/)() | Supprime tous les nœuds enfants et/ou les attributs du nœud actuel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Supprime le nœud enfant spécifié. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Remplace le nœud enfant **oldChild** par le nœud **newChild**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | Sélectionne une liste de nœuds correspondant à l’expression [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Sélectionne une liste de nœuds correspondant à l’expression [XPath](../../system.xml.xpath/). Tous les préfixes trouvés dans l’expression [XPath](../../system.xml.xpath/) sont résolus à l’aide du [XmlNamespaceManager](../xmlnamespacemanager/) fourni. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | Sélectionne le premier [XmlNode](../xmlnode/) qui correspond à l’expression [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Sélectionne le premier [XmlNode](../xmlnode/) qui correspond à l’expression [XPath](../../system.xml.xpath/). Tous les préfixes trouvés dans l’expression [XPath](../../system.xml.xpath/) sont résolus à l’aide du [XmlNamespaceManager](../xmlnamespacemanager/) fourni. |
| virtual void [set_InnerText](../xmlnode/set_innertext/)([String](../../system/string/)) | Définit les valeurs concaténées du nœud et de tous ses nœuds enfants. |
| void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) override | Définit le balisage représentant les enfants de ce nœud. |
| virtual void [set_Prefix](../xmlnode/set_prefix/)([String](../../system/string/)) | Définit le préfixe d’espace de noms de ce nœud. |
| virtual void [set_Value](../xmlnode/set_value/)([String](../../system/string/)) | Définit la valeur du nœud. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Diminue et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | Teste si l’implémentation DOM implémente une fonction spécifique. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d’objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente le construct C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente l’instruction C# lock() de déverrouillage. Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | Obtient l’implémentation de l’itérateur const begin pour le conteneur actuel. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | Obtient l’implémentation de l’itérateur begin pour le conteneur actuel. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | Obtient l’implémentation de l’itérateur const end pour le conteneur actuel. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | Obtient l’implémentation de l’itérateur end pour le conteneur actuel. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Diminue le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Enregistre les enfants du nœud dans le [XmlWriter](../xmlwriter/) spécifié. Cette méthode n’a aucun effet sur les nœuds [XmlNotation](./). |
| void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Enregistre le nœud dans le [XmlWriter](../xmlwriter/) spécifié. Cette méthode n’a aucun effet sur les nœuds [XmlNotation](./). |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Un alias pour un pointeur partagé vers une instance de cette classe. |
## Remarques



Les objets de cette classe ne doivent être alloués qu’avec la fonction [System::MakeObject()](../../system/makeobject/). Ne jamais créer d’instances de ce type sur la pile ou avec l’opérateur new, car cela provoquera des erreurs d’exécution et/ou des fautes d’assertion. Toujours envelopper cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utiliser ce pointeur pour le passer aux fonctions comme argument. 

## Voir aussi

* Class [XmlNode](../xmlnode/)
* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)