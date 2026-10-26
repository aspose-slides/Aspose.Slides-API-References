---
title: XmlNodeReader
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt einen Reader dar, der schnellen, nicht zwischengespeicherten Nur-Vorwärts-Zugriff auf XML-Daten in einem XmlNode ermöglicht.
type: docs
weight: 365
url: /de/system.xml/xmlnodereader/
---
## XmlNodeReader Klasse


Stellt einen Leser dar, der schnellen, nicht zwischengespeicherten Nur-vorwärts-Zugriff auf XML-Daten in einem [XmlNode](../xmlnode/) bietet.

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [Close](./close/)() override | Ändert das [XmlNodeReader::get_ReadState](./get_readstate/) zu [ReadState::Closed](../readstate/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Erstellt eine neue [XmlReader](../xmlreader/) Instanz mit angegebener URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Erstellt eine neue [XmlReader](../xmlreader/) Instanz, indem die angegebene URI und Einstellungen verwendet werden. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Erstellt eine neue [XmlReader](../xmlreader/) Instanz, indem die angegebene URI, Einstellungen und Kontextinformationen zum Parsen verwendet werden. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Erstellt eine neue [XmlReader](../xmlreader/) Instanz unter Verwendung des angegebenen Streams mit Standardeinstellungen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Erstellt eine neue [XmlReader](../xmlreader/) Instanz mit dem angegebenen Stream und den Einstellungen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Erstellt eine neue [XmlReader](../xmlreader/) Instanz unter Verwendung des angegebenen Streams, der Basis-URI und der Einstellungen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Erstellt eine neue [XmlReader](../xmlreader/) Instanz unter Verwendung des angegebenen Streams, der Einstellungen und Kontextinformationen zum Parsen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Erstellt eine neue [XmlReader](../xmlreader/) Instanz unter Verwendung des angegebenen Text-Readers. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Erstellt eine neue [XmlReader](../xmlreader/) Instanz unter Verwendung des angegebenen Text-Readers und der Einstellungen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Erstellt eine neue [XmlReader](../xmlreader/) Instanz unter Verwendung des angegebenen Text-Readers, der Einstellungen und der Basis-URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Erstellt eine neue [XmlReader](../xmlreader/) Instanz unter Verwendung des angegebenen Text-Readers, der Einstellungen und Kontextinformationen zum Parsen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Erstellt eine neue [XmlReader](../xmlreader/) Instanz unter Verwendung des angegebenen XML-Readers und der Einstellungen. |
| void [Dispose](../xmlreader/dispose/)() override | Gibt alle von der aktuellen Instanz der [XmlReader](../xmlreader/) Klasse verwendeten Ressourcen frei. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Gibt die Anzahl der Attribute des aktuellen Knotens zurück. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Gibt die Basis-URI des aktuellen Knotens zurück. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Gibt einen Wert zurück, der angibt, ob [XmlNodeReader](./) die Methoden zum Lesen binärer Inhalte implementiert. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | Gibt einen Wert zurück, der angibt, ob [XmlReader](../xmlreader/) die [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/)-Methode implementiert. |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Gibt einen Wert zurück, der angibt, ob dieser Leser Entitäten parsen und auflösen kann. |
| **int32_t** [get_Depth](./get_depth/)() override | Gibt die Tiefe des aktuellen Knotens im XML-Dokument zurück. |
| **bool** [get_EOF](./get_eof/)() override | Gibt einen Wert zurück, der angibt, ob der Leser am Ende des Streams positioniert ist. |
| **bool** [get_HasAttributes](./get_hasattributes/)() override | Gibt einen Wert zurück, der angibt, ob der aktuelle Knoten Attribute besitzt. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Gibt einen Wert zurück, der angibt, ob der aktuelle Knoten einen [XmlNodeReader::get_Value](./get_value/)-Wert haben kann. |
| **bool** [get_IsDefault](./get_isdefault/)() override | Gibt einen Wert zurück, der angibt, ob der aktuelle Knoten ein Attribut ist, das aus dem in der DTD bzw. im Schema definierten Standardwert erzeugt wurde. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Gibt einen Wert zurück, der angibt, ob der aktuelle Knoten ein leeres Element ist (z. B. **<MyElement/>**). |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Gibt den lokalen Namen des aktuellen Knotens zurück. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Gibt den qualifizierten Namen des aktuellen Knotens zurück. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Gibt die Namespace-URI (wie in der W3C-Namespace-Spezifikation definiert) des Knotens zurück, auf dem der Leser positioniert ist. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Gibt das [XmlNameTable](../xmlnametable/) zurück, das mit dieser Implementierung verknüpft ist. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Gibt den Typ des aktuellen Knotens zurück. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Gibt das Namespace-Präfix zurück, das mit dem aktuellen Knoten verknüpft ist. |
| virtual char16_t [get_QuoteChar](../xmlreader/get_quotechar/)() | Gibt im abgeleiteten Klassen-Override das Anführungszeichen-Zeichen zurück, das zum Einschließen des Attributwerts verwendet wird. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Gibt den Zustand des Lesers zurück. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | Gibt die Schema-Information zurück, die dem aktuellen Knoten zugewiesen wurde. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Gibt das [XmlReaderSettings](../xmlreadersettings/)-Objekt zurück, das zur Erstellung dieser [XmlReader](../xmlreader/) Instanz verwendet wurde. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Gibt den Textwert des aktuellen Knotens zurück. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Gibt den Typ des aktuellen Knotens zurück. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Gibt den aktuellen **xml:lang**-Geltungsbereich zurück. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Gibt den aktuellen **xml:space**-Geltungsbereich zurück. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Gibt den Wert des Attributs mit dem angegebenen Namen zurück. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Gibt den Wert des Attributs mit dem angegebenen lokalen Namen und der Namespace-URI zurück. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Gibt den Wert des Attributs mit dem angegebenen Index zurück. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analogie zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Gibt im abgeleiteten Klassen-Override den Wert des Attributs mit dem angegebenen Index zurück. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Gibt im abgeleiteten Klassen-Override den Wert des Attributs mit dem angegebenen [XmlReader::get_Name](../xmlreader/get_name/)-Wert zurück. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Gibt im abgeleiteten Klassen-Override den Wert des Attributs mit den angegebenen [XmlReader::get_LocalName](../xmlreader/get_localname/)- und [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-Werten zurück. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs ist. Analogie zum C#-„is“-Operator. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Gibt einen Wert zurück, der angibt, ob das Zeichenkettenargument ein gültiger XML-Name ist. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Gibt einen Wert zurück, der angibt, ob das Zeichenkettenargument ein gültiger XML-Name-Token ist. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Ruft [XmlReader::MoveToContent](../xmlreader/movetocontent/) auf und prüft, ob der aktuelle Inhaltsknoten ein Start-Tag oder ein leeres Element-Tag ist. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Ruft [XmlReader::MoveToContent](../xmlreader/movetocontent/) auf und prüft, ob der aktuelle Inhaltsknoten ein Start-Tag oder ein leeres Element-Tag ist und ob der [XmlReader::get_Name](../xmlreader/get_name/)-Wert des gefundenen Elements mit dem angegebenen Argument übereinstimmt. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Ruft [XmlReader::MoveToContent](../xmlreader/movetocontent/) auf und prüft, ob der aktuelle Inhaltsknoten ein Start-Tag oder ein leeres Element-Tag ist und ob die [XmlReader::get_LocalName](../xmlreader/get_localname/)- und [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-Werte des gefundenen Elements mit den angegebenen Zeichenketten übereinstimmen. |
| void [Lock](../../system/object/lock/)() | Implementiert das C#-`lock()`-Statement. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Sentry-Objekt verwenden. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Löst ein Namespace-Präfix im Geltungsbereich des aktuellen Elements auf. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Wechselt zum Attribut mit dem angegebenen Namen. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Wechselt zum Attribut mit dem angegebenen lokalen Namen und der Namespace-URI. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Wechselt zum Attribut mit dem angegebenen Index. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Prüft, ob der aktuelle Knoten ein Inhalts-Knoten (nicht-Leerzeichen-Text, **CDATA**, **Element**, **EndElement**, **EntityReference** oder **EndEntity**) ist. Ist er keiner, springt der Leser zum nächsten Inhalts-Knoten oder zum Dateiende. Er überspringt Knoten der folgenden Typen: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** oder **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Wechselt zum Element, das das aktuelle Attribut-Node enthält. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Wechselt zum ersten Attribut. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Wechselt zum nächsten Attribut. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von abgeleiteten Klassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von abgeleiteten Klassen. |
| **bool** [Read](./read/)() override | Liest den nächsten Knoten aus dem Stream. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Parsiert den Attributwert in einen oder mehrere **[Text](../../system.text/)**, **EntityReference** oder **EndEntity**-Knoten. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Liest den Inhalt als Objekt des angegebenen Typs. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Liest den Inhalt und gibt die Base64-decodierten Binärbytes zurück. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Liest den Inhalt und gibt die BinHex-decodierten Binärbytes zurück. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Liest den Textinhalt an der aktuellen Position als [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Liest den Textinhalt an der aktuellen Position als [DateTime](../../system/datetime/)-Objekt. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Liest den Textinhalt an der aktuellen Position als [DateTimeOffset](../../system/datetimeoffset/)-Objekt. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Liest den Textinhalt an der aktuellen Position als [Decimal](../../system/decimal/)-Objekt. |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Liest den Textinhalt an der aktuellen Position als double-Präzisions-Gleitkommazahl. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Liest den Textinhalt an der aktuellen Position als single-Präzisions-Gleitkommazahl. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Liest den Textinhalt an der aktuellen Position als 32-Bit-vorzeichenbehaftete Ganzzahl. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Liest den Textinhalt an der aktuellen Position als 64-Bit-vorzeichenbehaftete Ganzzahl. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Liest den Textinhalt an der aktuellen Position als [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Liest den Textinhalt an der aktuellen Position als ein [String](../../system/string/)-Objekt. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Liest den Inhalt des Elements als den angeforderten Typ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Überprüft, ob der angegebene lokale Name und die Namespace-URI mit denen des aktuellen Elements übereinstimmen, und liest anschließend den Inhalt des Elements als den angeforderten Typ. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Liest das Element und dekodiert den Base64-Inhalt. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Liest das Element und dekodiert den BinHex-Inhalt. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Liest das aktuelle Element und gibt den Inhalt als [Boolean](../../system/boolean/)-Objekt zurück. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Überprüft, ob der angegebene lokale Name und die Namespace-URI mit denen des aktuellen Elements übereinstimmen, und liest anschließend das aktuelle Element, wobei der Inhalt als [Boolean](../../system/boolean/)-Objekt zurückgegeben wird. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Liest das aktuelle Element und gibt den Inhalt als [DateTime](../../system/datetime/)-Objekt zurück. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Überprüft, ob der angegebene lokale Name und die Namespace-URI mit denen des aktuellen Elements übereinstimmen, und liest anschließend das aktuelle Element, wobei der Inhalt als [DateTime](../../system/datetime/)-Objekt zurückgegeben wird. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Liest das aktuelle Element und gibt den Inhalt als [Decimal](../../system/decimal/)-Objekt zurück. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Überprüft, ob der angegebene lokale Name und die Namespace-URI mit denen des aktuellen Elements übereinstimmen, und liest anschließend das aktuelle Element, wobei der Inhalt als [Decimal](../../system/decimal/)-Objekt zurückgegeben wird. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Liest das aktuelle Element und gibt den Inhalt als Gleitkommazahl mit doppelter Genauigkeit zurück. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Überprüft, ob der angegebene lokale Name und die Namespace-URI mit denen des aktuellen Elements übereinstimmen, und liest anschließend das aktuelle Element, wobei der Inhalt als Gleitkommazahl mit doppelter Genauigkeit zurückgegeben wird. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Liest das aktuelle Element und gibt den Inhalt als Gleitkommazahl mit einfacher Genauigkeit zurück. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Überprüft, ob der angegebene lokale Name und die Namespace-URI mit denen des aktuellen Elements übereinstimmen, und liest anschließend das aktuelle Element, wobei der Inhalt als Gleitkommazahl mit einfacher Genauigkeit zurückgegeben wird. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Liest das aktuelle Element und gibt den Inhalt als 32-Bit-vorzeichenbehaftete Ganzzahl zurück. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Überprüft, ob der angegebene lokale Name und die Namespace-URI mit denen des aktuellen Elements übereinstimmen, und liest anschließend das aktuelle Element, wobei der Inhalt als 32-Bit-vorzeichenbehaftete Ganzzahl zurückgegeben wird. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Liest das aktuelle Element und gibt den Inhalt als 64-Bit-vorzeichenbehaftete Ganzzahl zurück. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Überprüft, ob der angegebene lokale Name und die Namespace-URI mit denen des aktuellen Elements übereinstimmen, und liest anschließend das aktuelle Element, wobei der Inhalt als 64-Bit-vorzeichenbehaftete Ganzzahl zurückgegeben wird. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Liest das aktuelle Element und gibt den Inhalt als [Object](../../system/object/) zurück. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Überprüft, ob der angegebene lokale Name und die Namespace-URI mit denen des aktuellen Elements übereinstimmen, und liest anschließend das aktuelle Element, wobei der Inhalt als [Object](../../system/object/) zurückgegeben wird. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Liest das aktuelle Element und gibt den Inhalt als [String](../../system/string/)-Objekt zurück. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Überprüft, ob der angegebene lokale Name und die Namespace-URI mit denen des aktuellen Elements übereinstimmen, und liest anschließend das aktuelle Element, wobei der Inhalt als [String](../../system/string/)-Objekt zurückgegeben wird. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Liest ein ausschließlich aus Text bestehendes Element. Es wird jedoch empfohlen, stattdessen die [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/)-Methode zu verwenden, da sie eine einfachere Handhabung dieser Operation bietet. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Überprüft, ob der [XmlReader::get_Name](../xmlreader/get_name/)-Wert des gefundenen Elements mit der angegebenen Zeichenkette übereinstimmt, bevor ein ausschließlich aus Text bestehendes Element gelesen wird. Es wird jedoch empfohlen, stattdessen die [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/)-Methode zu verwenden, da sie eine einfachere Handhabung dieser Operation bietet. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Überprüft, ob die [XmlReader::get_LocalName](../xmlreader/get_localname/)- und [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-Werte des gefundenen Elements mit den angegebenen Zeichenketten übereinstimmen, bevor ein ausschließlich aus Text bestehendes Element gelesen wird. Es wird jedoch empfohlen, stattdessen die [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/)-Methode zu verwenden, da sie eine einfachere Handhabung dieser Operation bietet. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Überprüft, ob der aktuelle Inhaltsknoten ein End-Tag ist, und bewegt den Reader zum nächsten Knoten. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Wird in einer abgeleiteten Klasse überschrieben, liest sie den gesamten Inhalt, einschließlich Markup, als Zeichenkette. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Wird in einer abgeleiteten Klasse überschrieben, liest sie den Inhalt, einschließlich Markup, der diesen Knoten und alle seine Kinder darstellt. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Überprüft, ob der aktuelle Knoten ein Element ist, und bewegt den Reader zum nächsten Knoten. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Überprüft, ob der aktuelle Inhaltsknoten ein Element mit dem angegebenen [XmlReader::get_Name](../xmlreader/get_name/)-Wert ist, und bewegt den Reader zum nächsten Knoten. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Überprüft, ob der aktuelle Inhaltsknoten ein Element mit den angegebenen [XmlReader::get_LocalName](../xmlreader/get_localname/)- und [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-Werten ist, und bewegt den Reader zum nächsten Knoten. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Liest den Inhalt eines Elements oder Textknotens als Zeichenkette. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Gibt eine neue [XmlReader](../xmlreader/)-Instanz zurück, die zum Lesen des aktuellen Knotens und aller seiner Nachkommen verwendet werden kann. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Bewegt die [XmlReader](../xmlreader/) zum nächsten Nachkommen-Element mit dem angegebenen qualifizierten Namen. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Bewegt die [XmlReader](../xmlreader/) zum nächsten Nachkommen-Element mit dem angegebenen lokalen Namen und der Namespace-URI. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Liest, bis ein Element mit dem angegebenen qualifizierten Namen gefunden wird. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Liest, bis ein Element mit dem angegebenen lokalen Namen und der Namespace-URI gefunden wird. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Bewegt die [XmlReader](../xmlreader/) zum nächsten Geschwisterelement mit dem angegebenen qualifizierten Namen. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Bewegt die [XmlReader](../xmlreader/) zum nächsten Geschwisterelement mit dem angegebenen lokalen Namen und der Namespace-URI. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Liest große Textströme, die in ein XML-Dokument eingebettet sind. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Verweist den Vergleich von Werttyp-Objekten mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den geteilten Referenzzähler um den angegebenen Wert. |
| void [ResolveEntity](./resolveentity/)() override | Löst die Entity-Referenz für **EntityReference**-Knoten auf. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Vorlagenargument zu einem schwachen Zeiger (statt einem geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des geteilten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den geteilten Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [Skip](./skip/)() override | Überspringt die Kinder des aktuellen Knotens. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in eine Zeichenkette. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-Konstrukt typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
|  [XmlNodeReader](./xmlnodereader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | Erzeugt eine Instanz der Klasse [XmlNodeReader](./) mit dem angegebenen [XmlNode](../xmlnode/). |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
## Typdefinitionen

| Typdefinition | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared-Pointer auf eine Instanz dieser Klasse. |
## Anmerkungen



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## Siehe auch

* Klasse [XmlReader](../xmlreader/)
* Klasse [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namensraum [System::Xml](../)
* Bibliothek [Aspose.Slides](../../)