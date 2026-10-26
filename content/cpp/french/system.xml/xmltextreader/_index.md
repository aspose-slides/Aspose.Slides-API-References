---
title: XmlTextReader
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente un lecteur qui fournit un accès rapide, non mis en cache, en lecture seule aux données XML.
type: docs
weight: 508
url: /fr/system.xml/xmltextreader/
---
## classe XmlTextReader

Représente un lecteur qui fournit un accès rapide, non mis en cache, en lecture seule aux données XML.

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```

## Méthodes

| Méthode | Description |
| --- | --- |
| void [Close](./close/)() override | Modifie le [XmlReader::get_ReadState](../xmlreader/get_readstate/) en **Closed**. |
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
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Renvoie le nombre d'attributs du nœud actuel. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Renvoie l'URI de base du nœud actuel. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Renvoie une valeur indiquant si [XmlTextReader](./) implémente les méthodes de lecture de contenu binaire. |
| **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | Renvoie une valeur indiquant si [XmlTextReader](./) implémente la méthode [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Renvoie une valeur indiquant si ce lecteur peut analyser et résoudre les entités. |
| **int32_t** [get_Depth](./get_depth/)() override | Renvoie la profondeur du nœud actuel dans le document XML. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Renvoie l'énumération DtdProcessing. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Renvoie le codage du document. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | Renvoie une valeur qui spécifie la façon dont le lecteur gère les entités. |
| **bool** [get_EOF](./get_eof/)() override | Renvoie une valeur indiquant si le lecteur est positionné à la fin du flux. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | Renvoie une valeur indiquant si le nœud actuel possède des attributs. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Renvoie une valeur indiquant si le nœud actuel peut avoir un [XmlTextReader::get_Value](./get_value/) autre que [String::Empty](../../system/string/empty/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Renvoie une valeur indiquant si le nœud actuel est un attribut généré à partir de la valeur par défaut définie dans le DTD ou le schéma. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Renvoie une valeur indiquant si le nœud actuel est un élément vide (par exemple, **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | Renvoie le numéro de ligne actuel. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | Renvoie la position de ligne actuelle. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Renvoie le nom local du nœud actuel. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Renvoie le nom qualifié du nœud actuel. |
| **bool** [get_Namespaces](./get_namespaces/)() | Renvoie une valeur indiquant s'il faut activer la prise en charge des espaces de noms. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Renvoie l'URI de l'espace de noms (tel que défini dans la spécification W3C Namespace) du nœud sur lequel le lecteur est positionné. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Renvoie le [XmlNameTable](../xmlnametable/) associé à cette implémentation. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Renvoie le type du nœud actuel. |
| **bool** [get_Normalization](./get_normalization/)() | Renvoie une valeur indiquant s'il faut normaliser les espaces blancs et les valeurs d'attribut. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Renvoie le préfixe d'espace de noms associé au nœud actuel. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Renvoie une valeur indiquant s'il faut autoriser le traitement DTD. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | Renvoie le caractère de guillemet utilisé pour encadrer la valeur d'un nœud d'attribut. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Renvoie l'état du lecteur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | Renvoie les informations de schéma qui ont été assignées au nœud actuel à la suite de la validation du schéma. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Renvoie l'objet [XmlReaderSettings](../xmlreadersettings/) utilisé pour créer cette instance [XmlReader](../xmlreader/). |
| [String](../../system/string/) [get_Value](./get_value/)() override | Renvoie la valeur texte du nœud actuel. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Renvoie le type du nœud actuel. |
| [System::Xml::WhitespaceHandling](../whitespacehandling/) [get_WhitespaceHandling](./get_whitespacehandling/)() | Renvoie une valeur qui spécifie comment les espaces blancs sont gérés. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Renvoie la portée **xml:lang** actuelle. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Renvoie la portée **xml:space** actuelle. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Renvoie la valeur de l'attribut portant le nom spécifié. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Renvoie la valeur de l'attribut portant le nom local et l'URI d'espace de noms spécifiés. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Renvoie la valeur de l'attribut à l'index spécifié. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode [Object.GetHashCode()](../../system/object/gethashcode/) de C#. Permet le hachage d'objets personnalisés. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../xmlnamespacescope/)) override | Renvoie une collection contenant tous les espaces de noms actuellement en portée. |
| [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\> [GetRemainder](./getremainder/)() | Renvoie le reste du XML mis en mémoire tampon. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel [System.Object.GetType()](../../system/object/gettype/) de C#. |
| **bool** [HasLineInfo](./haslineinfo/)() override | Renvoie une valeur indiquant si la classe peut retourner des informations de ligne. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Lorsqu'elle est redéfinie dans une classe dérivée, obtient la valeur de l'attribut à l'index spécifié. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Lorsqu'elle est redéfinie dans une classe dérivée, obtient la valeur de l'attribut avec la valeur [XmlReader::get_Name](../xmlreader/get_name/) spécifiée. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Lorsqu'elle est redéfinie dans une classe dérivée, obtient la valeur de l'attribut avec les valeurs [XmlReader::get_LocalName](../xmlreader/get_localname/) et [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) spécifiées. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur 'is' de C#. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Renvoie une valeur indiquant si la chaîne passée en argument est un nom XML valide. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Renvoie une valeur indiquant si la chaîne passée en argument est un jeton de nom XML valide. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Appelle [XmlReader::MoveToContent](../xmlreader/movetocontent/) et teste si le nœud de contenu actuel est une balise d'ouverture ou une balise d'élément vide. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Appelle [XmlReader::MoveToContent](../xmlreader/movetocontent/) et teste si le nœud de contenu actuel est une balise d'ouverture ou une balise d'élément vide et si la valeur [XmlReader::get_Name](../xmlreader/get_name/) de l'élément trouvé correspond à l'argument fourni. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Appelle [XmlReader::MoveToContent](../xmlreader/movetocontent/) et teste si le nœud de contenu actuel est une balise d'ouverture ou une balise d'élément vide et si les valeurs [XmlReader::get_LocalName](../xmlreader/get_localname/) et [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) de l'élément trouvé correspondent aux chaînes fournies. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Résout un préfixe d'espace de noms dans la portée de l'élément actuel. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode [Object.MemberwiseClone()](../../system/object/memberwiseclone/) de C#. Permet le clonage de types personnalisés. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Se déplace vers l'attribut portant le nom spécifié. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Se déplace vers l'attribut portant le nom local et l'URI d'espace de noms spécifiés. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Se déplace vers l'attribut à l'index spécifié. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Vérifie si le nœud actuel est un nœud de contenu (texte non blanc, **CDATA**, **Element**, **EndElement**, **EntityReference** ou **EndEntity**). Si le nœud n'est pas un nœud de contenu, le lecteur saute au nœud de contenu suivant ou à la fin du fichier. Il saute les nœuds des types suivants : **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, ou **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Se déplace vers l'élément contenant le nœud d'attribut actuel. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Se déplace vers le premier attribut. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Se déplace vers l'attribut suivant. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, il initialise simplement un nouvel objet et permet la construction de copies pour les sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'assignation. Ne copie rien, il initialise simplement un nouvel objet et permet la construction de copies pour les sous-classes. |
| **bool** [Read](./read/)() override | Lit le nœud suivant depuis le flux. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Analyse la valeur de l'attribut en un ou plusieurs nœuds **[Text](../../system.text/)**, **EntityReference** ou **EndEntity**. |
| **int32_t** [ReadBase64](./readbase64/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Décode Base64 et renvoie les octets binaires décodés. |
| **int32_t** [ReadBinHex](./readbinhex/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Décode **BinHex** et renvoie les octets binaires décodés. |
| **int32_t** [ReadChars](./readchars/)(const [ArrayPtr](../../system/arrayptr/)\<char16_t\>\&, **int32_t**, **int32_t**) | Lit le contenu texte d'un élément dans un tampon de caractères. Cette méthode est conçue pour lire de grands flux de texte intégré en l'appelant successivement. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Lit le contenu comme un objet du type spécifié. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Lit le contenu et renvoie les octets binaires décodés **Base64**. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Lit le contenu et renvoie les octets binaires décodés **BinHex**. |
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
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Lit le contenu de l'élément comme le type demandé. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Vérifie que le nom local et l'URI d'espace de noms spécifiés correspondent à ceux de l'élément actuel, puis lit le contenu de l'élément comme le type demandé. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Lit l'élément et décode le contenu Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Lit l'élément et décode le contenu **BinHex**. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Lit le contenu de l'élément actuel et renvoie le contenu sous forme d'objet [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que le nom local et l'URI d'espace de noms spécifiés correspondent à ceux de l'élément actuel, puis lit l'élément actuel et renvoie le contenu sous forme d'objet [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Lit l'élément actuel et renvoie le contenu sous forme d'objet [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que le nom local et l'URI d'espace de noms spécifiés correspondent à ceux de l'élément actuel, puis lit l'élément actuel et renvoie le contenu sous forme d'objet [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Lit l'élément actuel et renvoie le contenu sous forme d'objet [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que le nom local et l'URI d'espace de noms spécifiés correspondent à ceux de l'élément actuel, puis lit l'élément actuel et renvoie le contenu sous forme d'objet [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Lit l'élément actuel et renvoie le contenu sous forme d'un nombre à virgule flottante double précision. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que le nom local et l'URI d'espace de noms spécifiés correspondent à ceux de l'élément actuel, puis lit l'élément actuel et renvoie le contenu sous forme d'un nombre à virgule flottante double précision. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Lit l'élément actuel et renvoie le contenu sous forme d'un nombre à virgule flottante simple précision. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que le nom local et l'URI d'espace de noms spécifiés correspondent à ceux de l'élément actuel, puis lit l'élément actuel et renvoie le contenu sous forme d'un nombre à virgule flottante simple précision. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Lit l'élément actuel et renvoie le contenu sous forme d'un entier signé 32 bits. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que le nom local et l'URI d'espace de noms spécifiés correspondent à ceux de l'élément actuel, puis lit l'élément actuel et renvoie le contenu sous forme d'un entier signé 32 bits. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Lit l'élément actuel et renvoie le contenu sous forme d'un entier signé 64 bits. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que le nom local et l'URI d'espace de noms spécifiés correspondent à ceux de l'élément actuel, puis lit l'élément actuel et renvoie le contenu sous forme d'un entier signé 64 bits. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Lit l'élément actuel et renvoie le contenu sous forme d'un [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que le nom local et l'URI d'espace de noms spécifiés correspondent à ceux de l'élément actuel, puis lit l'élément actuel et renvoie le contenu sous forme d'un [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Lit l'élément actuel et renvoie le contenu sous forme d'un objet [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que le nom local et l'URI d'espace de noms spécifiés correspondent à ceux de l'élément actuel, puis lit l'élément actuel et renvoie le contenu sous forme d'un objet [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Lit un élément texte uniquement. Cependant, il est recommandé d'utiliser la méthode [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) à la place, car elle offre une façon plus simple de gérer cette opération. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Vérifie que la valeur [XmlReader::get_Name](../xmlreader/get_name/) de l'élément trouvé correspond à la chaîne fournie avant de lire un élément texte uniquement. Cependant, il est recommandé d'utiliser la méthode [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) à la place, car elle offre une façon plus simple de gérer cette opération. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que les valeurs [XmlReader::get_LocalName](../xmlreader/get_localname/) et [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) de l'élément trouvé correspondent aux chaînes fournies avant de lire un élément texte uniquement. Cependant, il est recommandé d'utiliser la méthode [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) à la place, car elle offre une façon plus simple de gérer cette opération. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Vérifie que le nœud de contenu actuel est une balise de fin et avance le lecteur au nœud suivant. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Lorsqu'elle est redéfinie dans une classe dérivée, lit tout le contenu, y compris le balisage, sous forme de chaîne. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Lorsqu'elle est redéfinie dans une classe dérivée, lit le contenu, y compris le balisage, représentant ce nœud et tous ses enfants. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Vérifie que le nœud actuel est un élément et avance le lecteur au nœud suivant. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Vérifie que le nœud de contenu actuel est un élément avec la valeur [XmlReader::get_Name](../xmlreader/get_name/) donnée et avance le lecteur au nœud suivant. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Vérifie que le nœud de contenu actuel est un élément avec les valeurs [XmlReader::get_LocalName](../xmlreader/get_localname/) et [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) données et avance le lecteur au nœud suivant. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Lit le contenu d'un élément ou d'un nœud texte sous forme de chaîne. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Renvoie une nouvelle instance [XmlReader](../xmlreader/) qui peut être utilisée pour lire le nœud actuel et tous ses descendants. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Fait avancer le [XmlReader](../xmlreader/) vers l'élément descendant suivant portant le nom qualifié spécifié. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Fait avancer le [XmlReader](../xmlreader/) vers l'élément descendant suivant portant le nom local et l'URI d'espace de noms spécifiés. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Lit jusqu'à ce qu'un élément portant le nom qualifié spécifié soit trouvé. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Lit jusqu'à ce qu'un élément portant le nom local et l'URI d'espace de noms spécifiés soit trouvé. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Fait avancer le [XmlReader](../xmlreader/) vers l'élément frère suivant portant le nom qualifié spécifié. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Fait avancer le [XmlReader](../xmlreader/) vers l'élément frère suivant portant le nom local et l'URI d'espace de noms spécifiés. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Lit de gros flux de texte intégrés dans un document XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [ResetState](./resetstate/)() | Réinitialise l'état du lecteur à [ReadState::Initial](../readstate/). |
| void [ResolveEntity](./resolveentity/)() override | Résout la référence d'entité pour les nœuds **EntityReference**. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Définit l'énumération DtdProcessing. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Définit une valeur qui spécifie comment le lecteur gère les entités. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Définit une valeur indiquant s'il faut activer la prise en charge des espaces de noms. |
| void [set_Normalization](./set_normalization/)(**bool**) | Définit une valeur indiquant s'il faut normaliser les espaces blancs et les valeurs d'attribut. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Définit une valeur indiquant s'il faut autoriser le traitement DTD. |
| void [set_WhitespaceHandling](./set_whitespacehandling/)([System::Xml::WhitespaceHandling](../whitespacehandling/)) | Définit une valeur qui spécifie comment les espaces blancs sont gérés. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Définit le [XmlResolver](../xmlresolver/) utilisé pour résoudre les références DTD. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez à la place des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez à la place des pointeurs intelligents ou ThisProtector. |
| void [Skip](./skip/)() override | Saute les enfants du nœud actuel. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode [Object.ToString()](../../system/object/tostring/) de C#. Permet la conversion d'objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez à la place des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez à la place des pointeurs intelligents ou ThisProtector. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Initialise une nouvelle instance de la classe [XmlTextReader](./) avec le flux spécifié. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Initialise une nouvelle instance de la classe [XmlTextReader](./) avec l'URL et le flux spécifiés. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Initialise une nouvelle instance de la classe [XmlTextReader](./) avec le flux et [XmlNameTable](../xmlnametable/) spécifiés. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Initialise une nouvelle instance de la classe [XmlTextReader](./) avec l'URL, le flux et [XmlNameTable](../xmlnametable/) spécifiés. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Initialise une nouvelle instance de la classe [XmlTextReader](./) avec le TextReader spécifié. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Initialise une nouvelle instance de la classe [XmlTextReader](./) avec l'URL et le TextReader spécifiés. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Initialise une nouvelle instance de la classe [XmlTextReader](./) avec le TextReader et [XmlNameTable](../xmlnametable/) spécifiés. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Initialise une nouvelle instance de la classe [XmlTextReader](./) avec l'URL, le TextReader et [XmlNameTable](../xmlnametable/) spécifiés. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Initialise une nouvelle instance de la classe [XmlTextReader](./) avec le flux, XmlNodeType et [XmlParserContext](../xmlparsercontext/) spécifiés. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Initialise une nouvelle instance de la classe [XmlTextReader](./) avec la chaîne, XmlNodeType et [XmlParserContext](../xmlparsercontext/) spécifiés. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&) | Initialise une nouvelle instance de la classe [XmlTextReader](./) avec le fichier spécifié. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Initialise une nouvelle instance de la classe [XmlTextReader](./) avec le fichier et [XmlNameTable](../xmlnametable/) spécifiés. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Alias de type

| Alias | Description |
| --- | --- |
| [Ptr](./ptr/) | Un alias pour un pointeur partagé vers une instance de cette classe. |

## Remarques

Il est recommandé d'utiliser la classe [XmlReader](../xmlreader/) à la place.  

Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instances de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions comme argument.  

## Voir aussi

* Classe [XmlReader](../xmlreader/)
* Classe [IXmlLineInfo](../ixmllineinfo/)
* Classe [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Espace de noms [System::Xml](../)
* Bibliothèque [Aspose.Slides](../../)