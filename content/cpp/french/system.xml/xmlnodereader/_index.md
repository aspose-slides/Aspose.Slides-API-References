---
title: XmlNodeReader
second_title: Référence API Aspose.Slides pour C++
description: Représente un lecteur qui fournit un accès rapide, non mis en cache, en avant uniquement aux données XML dans un XmlNode.
type: docs
weight: 365
url: /fr/system.xml/xmlnodereader/
---
## XmlNodeReader classe


Représente un lecteur qui fournit un accès rapide, non mis en cache, en avant uniquement aux données XML dans un [XmlNode](../xmlnode/).

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## Méthodes

| Méthode | Description |
| --- | --- |
| void [Close](./close/)() override | Modifie le [XmlNodeReader::get_ReadState](./get_readstate/) en [ReadState::Closed](../readstate/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Crée une nouvelle instance [XmlReader](../xmlreader/) avec l'URI spécifié. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Crée une nouvelle instance [XmlReader](../xmlreader/) en utilisant l'URI et les paramètres spécifiés. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Crée une nouvelle instance [XmlReader](../xmlreader/) en utilisant l'URI, les paramètres et les informations de contexte spécifiés pour l'analyse. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Crée une nouvelle instance [XmlReader](../xmlreader/) en utilisant le flux spécifié avec les paramètres par défaut. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Crée une nouvelle instance [XmlReader](../xmlreader/) avec le flux et les paramètres spécifiés. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Crée une nouvelle instance [XmlReader](../xmlreader/) en utilisant le flux, l'URI de base et les paramètres spécifiés. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Crée une nouvelle instance [XmlReader](../xmlreader/) en utilisant le flux, les paramètres et les informations de contexte spécifiés pour l'analyse. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Crée une nouvelle instance [XmlReader](../xmlreader/) en utilisant le lecteur de texte spécifié. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Crée une nouvelle instance [XmlReader](../xmlreader/) en utilisant le lecteur de texte et les paramètres spécifiés. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Crée une nouvelle instance [XmlReader](../xmlreader/) en utilisant le lecteur de texte, les paramètres et l'URI de base spécifiés. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Crée une nouvelle instance [XmlReader](../xmlreader/) en utilisant le lecteur de texte, les paramètres et les informations de contexte spécifiés pour l'analyse. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Crée une nouvelle instance [XmlReader](../xmlreader/) en utilisant le lecteur XML et les paramètres spécifiés. |
| void [Dispose](../xmlreader/dispose/)() override | Libère toutes les ressources utilisées par l'instance actuelle de la classe [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Retourne le nombre d’attributs du nœud actuel. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Retourne l’URI de base du nœud actuel. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Retourne une valeur indiquant si le [XmlNodeReader](./) implémente les méthodes de lecture de contenu binaire. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | Retourne une valeur indiquant si le [XmlReader](../xmlreader/) implémente la méthode [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Retourne une valeur indiquant si ce lecteur peut analyser et résoudre les entités. |
| **int32_t** [get_Depth](./get_depth/)() override | Retourne la profondeur du nœud actuel dans le document XML. |
| **bool** [get_EOF](./get_eof/)() override | Retourne une valeur indiquant si le lecteur est positionné à la fin du flux. |
| **bool** [get_HasAttributes](./get_hasattributes/)() override | Retourne une valeur indiquant si le nœud actuel possède des attributs. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Retourne une valeur indiquant si le nœud actuel peut avoir une valeur [XmlNodeReader::get_Value](./get_value/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Retourne une valeur indiquant si le nœud actuel est un attribut généré à partir de la valeur par défaut définie dans la DTD ou le schéma. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Retourne une valeur indiquant si le nœud actuel est un élément vide (par exemple, **<MyElement/>**). |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Retourne le nom local du nœud actuel. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Retourne le nom qualifié du nœud actuel. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Retourne l’URI de l’espace de noms (tel que défini dans la spécification W3C Namespace) du nœud où le lecteur est positionné. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Retourne le [XmlNameTable](../xmlnametable/) associé à cette implémentation. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Retourne le type du nœud actuel. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Retourne le préfixe d’espace de noms associé au nœud actuel. |
| virtual char16_t [get_QuoteChar](../xmlreader/get_quotechar/)() | Lorsqu’il est surchargé dans une classe dérivée, obtient le caractère de guillemet utilisé pour entourer la valeur d’un nœud attribut. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Retourne l’état du lecteur. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | Retourne les informations de schéma qui ont été assignées au nœud actuel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Retourne l’objet [XmlReaderSettings](../xmlreadersettings/) utilisé pour créer cette instance [XmlReader](../xmlreader/). |
| [String](../../system/string/) [get_Value](./get_value/)() override | Retourne la valeur texte du nœud actuel. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Retourne le type du nœud actuel. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Retourne la portée actuelle du **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Retourne la portée actuelle du **xml:space**. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Retourne la valeur de l’attribut portant le nom spécifié. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Retourne la valeur de l’attribut portant le nom local et l’URI d’espace de noms spécifiés. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Retourne la valeur de l’attribut à l’indice spécifié. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d’objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Lorsqu’il est surchargé dans une classe dérivée, obtient la valeur de l’attribut à l’indice spécifié. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Lorsqu’il est surchargé dans une classe dérivée, obtient la valeur de l’attribut portant la valeur [XmlReader::get_Name](../xmlreader/get_name/) spécifiée. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Lorsqu’il est surchargé dans une classe dérivée, obtient la valeur de l’attribut portant les valeurs [XmlReader::get_LocalName](../xmlreader/get_localname/) et [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) spécifiées. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur C# ‘is’. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Retourne une valeur indiquant si la chaîne passée est un nom XML valide. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Retourne une valeur indiquant si la chaîne passée est un jeton de nom XML valide. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Appelle [XmlReader::MoveToContent](../xmlreader/movetocontent/) et teste si le nœud de contenu actuel est une balise d’ouverture ou une balise d’élément vide. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Appelle [XmlReader::MoveToContent](../xmlreader/movetocontent/) et teste si le nœud de contenu actuel est une balise d’ouverture ou une balise d’élément vide et si la valeur [XmlReader::get_Name](../xmlreader/get_name/) de l’élément trouvé correspond à l’argument donné. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Appelle [XmlReader::MoveToContent](../xmlreader/movetocontent/) et teste si le nœud de contenu actuel est une balise d’ouverture ou une balise d’élément vide et si les valeurs [XmlReader::get_LocalName](../xmlreader/get_localname/) et [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) de l’élément trouvé correspondent aux chaînes données. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Résout un préfixe d’espace de noms dans la portée de l’élément actuel. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Se déplace vers l’attribut portant le nom spécifié. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Se déplace vers l’attribut portant le nom local et l’URI d’espace de noms spécifiés. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Se déplace vers l’attribut à l’indice spécifié. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Vérifie si le nœud actuel est un nœud de contenu (texte non blanc, **CDATA**, **Element**, **EndElement**, **EntityReference** ou **EndEntity**). Si le nœud n’est pas un nœud de contenu, le lecteur saute au nœud de contenu suivant ou à la fin du fichier. Il ignore les nœuds des types suivants : **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, ou **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Se déplace vers l’élément contenant le nœud d’attribut actuel. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Se déplace vers le premier attribut. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Se déplace vers l’attribut suivant. |
|  [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, initialise simplement un nouvel objet et permet la copie des classes dérivées. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien, initialise simplement un nouvel objet et permet la copie des classes dérivées. |
| **bool** [Read](./read/)() override | Lit le nœud suivant du flux. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Analyse la valeur de l’attribut en un ou plusieurs nœuds **[Text](../../system.text/)**, **EntityReference** ou **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Lit le contenu comme un objet du type spécifié. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Lit le contenu et renvoie les octets binaires décodés en Base64. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Lit le contenu et renvoie les octets binaires décodés en BinHex. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Lit le contenu texte à la position actuelle comme un [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Lit le contenu texte à la position actuelle comme un objet [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Lit le contenu texte à la position actuelle comme un objet [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Lit le contenu texte à la position actuelle comme un objet [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Lit le contenu texte à la position actuelle comme un nombre à virgule flottante double précision. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Lit le contenu texte à la position actuelle comme un nombre à virgule flottante simple précision. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Lit le contenu texte à la position actuelle comme un entier signé 32 bits. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Lit le contenu texte à la position actuelle comme un entier signé 64 bits. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Lit le contenu texte à la position actuelle comme un [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Lit le contenu texte à la position actuelle comme un objet [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Lit le contenu de l’élément comme le type demandé. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Vérifie que le nom local et l’URI d’espace de noms spécifiés correspondent à ceux de l’élément actuel, puis lit le contenu de l’élément comme le type demandé. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Lit l’élément et décode le contenu Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Lit l’élément et décode le contenu BinHex. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Lit l’élément actuel et renvoie le contenu comme un objet [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que le nom local et l’URI d’espace de noms spécifiés correspondent à ceux de l’élément actuel, puis lit l’élément actuel et renvoie le contenu comme un objet [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Lit l’élément actuel et renvoie le contenu comme un objet [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que le nom local et l’URI d’espace de noms spécifiés correspondent à ceux de l’élément actuel, puis lit l’élément actuel et renvoie le contenu comme un objet [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Lit l’élément actuel et renvoie le contenu comme un objet [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que le nom local et l’URI d’espace de noms spécifiés correspondent à ceux de l’élément actuel, puis lit l’élément actuel et renvoie le contenu comme un objet [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Lit l’élément actuel et renvoie le contenu comme un nombre à virgule flottante double précision. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que le nom local et l’URI d’espace de noms spécifiés correspondent à ceux de l’élément actuel, puis lit l’élément actuel et renvoie le contenu comme un nombre à virgule flottante double précision. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Lit l’élément actuel et renvoie le contenu comme un nombre à virgule flottante simple précision. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que le nom local et l’URI d’espace de noms spécifiés correspondent à ceux de l’élément actuel, puis lit l’élément actuel et renvoie le contenu comme un nombre à virgule flottante simple précision. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Lit l’élément actuel et renvoie le contenu comme un entier signé 32 bits. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que le nom local et l’URI d’espace de noms spécifiés correspondent à ceux de l’élément actuel, puis lit l’élément actuel et renvoie le contenu comme un entier signé 32 bits. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Lit l’élément actuel et renvoie le contenu comme un entier signé 64 bits. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que le nom local et l’URI d’espace de noms spécifiés correspondent à ceux de l’élément actuel, puis lit l’élément actuel et renvoie le contenu comme un entier signé 64 bits. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Lit l’élément actuel et renvoie le contenu comme un [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que le nom local et l’URI d’espace de noms spécifiés correspondent à ceux de l’élément actuel, puis lit l’élément actuel et renvoie le contenu comme un [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Lit l’élément actuel et renvoie le contenu comme un objet [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que le nom local et l’URI d’espace de noms spécifiés correspondent à ceux de l’élément actuel, puis lit l’élément actuel et renvoie le contenu comme un [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Lit un élément contenant uniquement du texte. Cependant, il est recommandé d’utiliser la méthode [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) à la place, car elle offre une manière plus directe de gérer cette opération. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Vérifie que la valeur [XmlReader::get_Name](../xmlreader/get_name/) de l’élément trouvé correspond à la chaîne donnée avant de lire un élément contenant uniquement du texte. Cependant, il est recommandé d’utiliser la méthode [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) à la place, car elle offre une manière plus directe de gérer cette opération. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que les valeurs [XmlReader::get_LocalName](../xmlreader/get_localname/) et [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) de l’élément trouvé correspondent aux chaînes données avant de lire un élément contenant uniquement du texte. Cependant, il est recommandé d’utiliser la méthode [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) à la place, car elle offre une manière plus directe de gérer cette opération. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Vérifie que le nœud de contenu actuel est une balise de fin et avance le lecteur au nœud suivant. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Lorsqu’il est surchargé dans une classe dérivée, lit tout le contenu, y compris le balisage, sous forme de chaîne. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Lorsqu’il est surchargé dans une classe dérivée, lit le contenu, y compris le balisage, représentant ce nœud et tous ses enfants. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Vérifie que le nœud actuel est un élément et avance le lecteur au nœud suivant. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Vérifie que le nœud de contenu actuel est un élément avec la valeur [XmlReader::get_Name](../xmlreader/get_name/) donnée et avance le lecteur au nœud suivant. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que le nœud de contenu actuel est un élément avec les valeurs [XmlReader::get_LocalName](../xmlreader/get_localname/) et [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) données et avance le lecteur au nœud suivant. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Lit le contenu d’un élément ou d’un nœud texte sous forme de chaîne. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Retourne une nouvelle instance [XmlReader](../xmlreader/) qui peut être utilisée pour lire le nœud actuel et tous ses descendants. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Avance le [XmlReader](../xmlreader/) vers le prochain élément descendant avec le nom qualifié spécifié. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Avance le [XmlReader](../xmlreader/) vers le prochain élément descendant avec le nom local et l’URI d’espace de noms spécifiés. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Lit jusqu’à ce qu’un élément avec le nom qualifié spécifié soit trouvé. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Lit jusqu’à ce qu’un élément avec le nom local et l’URI d’espace de noms spécifiés soit trouvé. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Avance le [XmlReader](../xmlreader/) vers le prochain élément frère avec le nom qualifié spécifié. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Avance le [XmlReader](../xmlreader/) vers le prochain élément frère avec le nom local et l’URI d’espace de noms spécifiés. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Lit de grands flux de texte intégrés dans un document XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [ResolveEntity](./resolveentity/)() override | Résout la référence d’entité pour les nœuds **EntityReference**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [Skip](./skip/)() override | Ignore les enfants du nœud actuel. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
|  [XmlNodeReader](./xmlnodereader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | Crée une instance de la classe [XmlNodeReader](./) en utilisant le [XmlNode](../xmlnode/) spécifié. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Un alias pour un pointeur partagé vers une instance de cette classe. |

## Remarques



Les objets de cette classe ne devraient être alloués qu’en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d’instances de ce type sur la pile ou en utilisant l’opérateur new, car cela entraînera des erreurs d’exécution et/ou des assertions. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu’argument. 

## Voir aussi

* Class [XmlReader](../xmlreader/)
* Class [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)