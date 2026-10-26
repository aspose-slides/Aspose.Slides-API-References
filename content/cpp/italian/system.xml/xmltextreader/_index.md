---
title: XmlTextReader
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta un lettore che fornisce accesso rapido, non memorizzato nella cache e solo in avanti ai dati XML.
type: docs
weight: 508
url: /it/system.xml/xmltextreader/
---
## XmlTextReader classe

Rappresenta un lettore che fornisce un accesso rapido, non memorizzato nella cache e solo in avanti ai dati XML.

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [Close](./close/)() override | Cambia il [XmlReader::get_ReadState](../xmlreader/get_readstate/) a **Closed**. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Crea una nuova istanza [XmlReader](../xmlreader/) con l'URI specificato. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Crea una nuova istanza [XmlReader](../xmlreader/) utilizzando l'URI e le impostazioni specificate. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Crea una nuova istanza [XmlReader](../xmlreader/) utilizzando l'URI, le impostazioni e le informazioni di contesto per l'analisi. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Crea una nuova istanza [XmlReader](../xmlreader/) usando lo stream specificato con le impostazioni predefinite. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Crea una nuova istanza [XmlReader](../xmlreader/) con lo stream e le impostazioni specificate. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Crea una nuova istanza [XmlReader](../xmlreader/) usando lo stream, l'URI di base e le impostazioni. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Crea una nuova istanza [XmlReader](../xmlreader/) usando lo stream, le impostazioni e le informazioni di contesto per l'analisi. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Crea una nuova istanza [XmlReader](../xmlreader/) usando il lettore di testo specificato. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Crea una nuova istanza [XmlReader](../xmlreader/) usando il lettore di testo e le impostazioni specificate. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Crea una nuova istanza [XmlReader](../xmlreader/) usando il lettore di testo, le impostazioni e l'URI di base. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Crea una nuova istanza [XmlReader](../xmlreader/) usando il lettore di testo, le impostazioni e le informazioni di contesto per l'analisi. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Crea una nuova istanza [XmlReader](../xmlreader/) usando il lettore XML e le impostazioni specificate. |
| void [Dispose](../xmlreader/dispose/)() override | Rilascia tutte le risorse utilizzate dall'istanza corrente della classe [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Esegue il confronto di punti flottanti in stile C# dove due NaN sono considerati uguali, anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Esegue il confronto di punti flottanti in stile C# dove due NaN sono considerati uguali, anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Restituisce il numero di attributi nel nodo corrente. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Restituisce l'URI di base del nodo corrente. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Restituisce un valore che indica se il [XmlTextReader](./) implementa i metodi di lettura del contenuto binario. |
| **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | Restituisce un valore che indica se il [XmlTextReader](./) implementa il metodo [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Restituisce un valore che indica se questo lettore può analizzare e risolvere le entità. |
| **int32_t** [get_Depth](./get_depth/)() override | Restituisce la profondità del nodo corrente nel documento XML. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Restituisce l'enumerazione DtdProcessing. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Restituisce la codifica del documento. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | Restituisce un valore che specifica come il lettore gestisce le entità. |
| **bool** [get_EOF](./get_eof/)() override | Restituisce un valore che indica se il lettore è posizionato alla fine dello stream. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | Restituisce un valore che indica se il nodo corrente ha attributi. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Restituisce un valore che indica se il nodo corrente può avere un [XmlTextReader::get_Value](./get_value/) diverso da [String::Empty](../../system/string/empty/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Restituisce un valore che indica se il nodo corrente è un attributo generato dal valore predefinito definito nel DTD o nello schema. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Restituisce un valore che indica se il nodo corrente è un elemento vuoto (ad esempio, **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | Restituisce il numero di riga corrente. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | Restituisce la posizione nella riga corrente. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Restituisce il nome locale del nodo corrente. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Restituisce il nome qualificato del nodo corrente. |
| **bool** [get_Namespaces](./get_namespaces/)() | Restituisce un valore che indica se abilitare il supporto dei namespace. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Restituisce l'URI del namespace (come definito nella specifica W3C Namespace) del nodo su cui il lettore è posizionato. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Restituisce il [XmlNameTable](../xmlnametable/) associato a questa implementazione. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Restituisce il tipo del nodo corrente. |
| **bool** [get_Normalization](./get_normalization/)() | Restituisce un valore che indica se normalizzare spazi bianchi e valori degli attributi. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Restituisce il prefisso del namespace associato al nodo corrente. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Restituisce un valore che indica se consentire l'elaborazione DTD. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | Restituisce il carattere di virgolette usato per racchiudere il valore di un nodo attributo. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Restituisce lo stato del lettore. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | Restituisce le informazioni di schema assegnate al nodo corrente come risultato della convalida dello schema. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Restituisce l'oggetto [XmlReaderSettings](../xmlreadersettings/) usato per creare questa istanza [XmlReader](../xmlreader/). |
| [String](../../system/string/) [get_Value](./get_value/)() override | Restituisce il valore di testo del nodo corrente. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Restituisce il tipo per il nodo corrente. |
| [System::Xml::WhitespaceHandling](../whitespacehandling/) [get_WhitespaceHandling](./get_whitespacehandling/)() | Restituisce un valore che specifica come vengono gestiti gli spazi bianchi. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Restituisce l'ambito **xml:lang** corrente. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Restituisce l'ambito **xml:space** corrente. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Restituisce il valore dell'attributo con il nome specificato. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Restituisce il valore dell'attributo con il nome locale e l'URI del namespace specificati. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Restituisce il valore dell'attributo con l'indice specificato. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../xmlnamespacescope/)) override | Restituisce una collezione che contiene tutti i namespace attualmente in ambito. |
| [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\> [GetRemainder](./getremainder/)() | Restituisce il resto dell'XML buffered. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [HasLineInfo](./haslineinfo/)() override | Restituisce un valore che indica se la classe può restituire informazioni di riga. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Quando sovrascritto in una classe derivata, ottiene il valore dell'attributo con l'indice specificato. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Quando sovrascritto in una classe derivata, ottiene il valore dell'attributo con il valore [XmlReader::get_Name](../xmlreader/get_name/) specificato. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Quando sovrascritto in una classe derivata, ottiene il valore dell'attributo con i valori [XmlReader::get_LocalName](../xmlreader/get_localname/) e [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) specificati. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Restituisce un valore che indica se la stringa passata è un nome XML valido. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Restituisce un valore che indica se la stringa passata è un token di nome XML valido. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Chiama [XmlReader::MoveToContent](../xmlreader/movetocontent/) e verifica se il nodo di contenuto corrente è un tag di apertura o un tag elemento vuoto. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Chiama [XmlReader::MoveToContent](../xmlreader/movetocontent/) e verifica se il nodo di contenuto corrente è un tag di apertura o un tag elemento vuoto e se il valore [XmlReader::get_Name](../xmlreader/get_name/) dell'elemento trovato corrisponde all'argomento fornito. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Chiama [XmlReader::MoveToContent](../xmlreader/movetocontent/) e verifica se il nodo di contenuto corrente è un tag di apertura o un tag elemento vuoto e se i valori [XmlReader::get_LocalName](../xmlreader/get_localname/) e [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) dell'elemento trovato corrispondono alle stringhe fornite. |
| void [Lock](../../system/object/lock/)() | Implementa l'istruzione C# lock() per il lock. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Risolve un prefisso di namespace nell'ambito dell'elemento corrente. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Si sposta all'attributo con il nome specificato. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Si sposta all'attributo con il nome locale e l'URI del namespace specificati. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Si sposta all'attributo con l'indice specificato. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Verifica se il nodo corrente è un nodo di contenuto (testo non bianco, **CDATA**, **Element**, **EndElement**, **EntityReference** o **EndEntity**). Se il nodo non è un nodo di contenuto, il lettore salta al nodo di contenuto successivo o alla fine del file. Salta i nodi dei seguenti tipi: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, o **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Si sposta all'elemento che contiene il nodo attributo corrente. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Si sposta al primo attributo. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Si sposta al prossimo attributo. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, ma inizializza un nuovo oggetto e abilita la copia di sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, ma inizializza un nuovo oggetto e abilita la copia di sottoclassi. |
| **bool** [Read](./read/)() override | Legge il nodo successivo dallo stream. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Analizza il valore dell'attributo in uno o più nodi **[Text](../../system.text/)**, **EntityReference** o **EndEntity**. |
| **int32_t** [ReadBase64](./readbase64/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Decodifica Base64 e restituisce i byte binari decodificati. |
| **int32_t** [ReadBinHex](./readbinhex/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Decodifica **BinHex** e restituisce i byte binari decodificati. |
| **int32_t** [ReadChars](./readchars/)(const [ArrayPtr](../../system/arrayptr/)\<char16_t\>\&, **int32_t**, **int32_t**) | Legge il contenuto testuale di un elemento in un buffer di caratteri. Questo metodo è progettato per leggere grandi flussi di testo incorporato chiamandolo successivamente. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Legge il contenuto come un oggetto del tipo specificato. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Legge il contenuto e restituisce i byte binari decodificati in **Base64**. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Legge il contenuto e restituisce i byte binari decodificati in **BinHex**. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Legge il contenuto testuale nella posizione corrente come un [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Legge il contenuto testuale nella posizione corrente come un oggetto [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Legge il contenuto testuale nella posizione corrente come un oggetto [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Legge il contenuto testuale nella posizione corrente come un oggetto [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Legge il contenuto testuale nella posizione corrente come un numero in virgola mobile a doppia precisione. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Legge il contenuto testuale nella posizione corrente come un numero in virgola mobile a precisione singola. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Legge il contenuto testuale nella posizione corrente come un intero con segno a 32 bit. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Legge il contenuto testuale nella posizione corrente come un intero con segno a 64 bit. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Legge il contenuto testuale nella posizione corrente come un [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Legge il contenuto testuale nella posizione corrente come un oggetto [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Legge il contenuto dell'elemento come il tipo richiesto. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Controlla che il nome locale e l'URI dello spazio dei nomi specificati corrispondano a quelli dell'elemento corrente, quindi legge il contenuto dell'elemento come il tipo richiesto. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Legge l'elemento e decodifica il contenuto in Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Legge l'elemento e decodifica il contenuto **BinHex**. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Legge l'elemento corrente e restituisce il contenuto come un oggetto [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Controlla che il nome locale e l'URI dello spazio dei nomi specificati corrispondano a quelli dell'elemento corrente, quindi legge l'elemento corrente e restituisce il contenuto come un oggetto [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Legge l'elemento corrente e restituisce il contenuto come un oggetto [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Controlla che il nome locale e l'URI dello spazio dei nomi specificati corrispondano a quelli dell'elemento corrente, quindi legge l'elemento corrente e restituisce il contenuto come un oggetto [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Legge l'elemento corrente e restituisce il contenuto come un oggetto [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Controlla che il nome locale e l'URI dello spazio dei nomi specificati corrispondano a quelli dell'elemento corrente, quindi legge l'elemento corrente e restituisce il contenuto come un oggetto [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Legge l'elemento corrente e restituisce il contenuto come un numero in virgola mobile a doppia precisione. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Controlla che il nome locale e l'URI dello spazio dei nomi specificati corrispondano a quelli dell'elemento corrente, quindi legge l'elemento corrente e restituisce il contenuto come un numero in virgola mobile a doppia precisione. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Legge l'elemento corrente e restituisce il contenuto come un numero in virgola mobile a precisione singola. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Controlla che il nome locale e l'URI dello spazio dei nomi specificati corrispondano a quelli dell'elemento corrente, quindi legge l'elemento corrente e restituisce il contenuto come un numero in virgola mobile a precisione singola. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Legge l'elemento corrente e restituisce il contenuto come un intero con segno a 32 bit. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Controlla che il nome locale e l'URI dello spazio dei nomi specificati corrispondano a quelli dell'elemento corrente, quindi legge l'elemento corrente e restituisce il contenuto come un intero con segno a 32 bit. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Legge l'elemento corrente e restituisce il contenuto come un intero con segno a 64 bit. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Controlla che il nome locale e l'URI dello spazio dei nomi specificati corrispondano a quelli dell'elemento corrente, quindi legge l'elemento corrente e restituisce il contenuto come un intero con segno a 64 bit. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Legge l'elemento corrente e restituisce il contenuto come un [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Controlla che il nome locale e l'URI dello spazio dei nomi specificati corrispondano a quelli dell'elemento corrente, quindi legge l'elemento corrente e restituisce il contenuto come un [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Legge l'elemento corrente e restituisce il contenuto come un oggetto [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Controlla che il nome locale e l'URI dello spazio dei nomi specificati corrispondano a quelli dell'elemento corrente, quindi legge l'elemento corrente e restituisce il contenuto come un oggetto [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Legge un elemento solo testuale. Tuttavia, si consiglia di usare il metodo [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) invece, perché offre un modo più semplice per gestire questa operazione. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Controlla che il valore [XmlReader::get_Name](../xmlreader/get_name/) dell'elemento trovato corrisponda alla stringa fornita prima di leggere un elemento solo testuale. Tuttavia, si consiglia di usare il metodo [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) invece, perché offre un modo più semplice per gestire questa operazione. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Controlla che i valori [XmlReader::get_LocalName](../xmlreader/get_localname/) e [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) dell'elemento trovato corrispondano alle stringhe fornite prima di leggere un elemento solo testuale. Tuttavia, si consiglia di usare il metodo [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) invece, perché offre un modo più semplice per gestire questa operazione. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Verifica che il nodo di contenuto corrente sia un tag di chiusura e sposta il lettore al nodo successivo. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Quando sovrascritto in una classe derivata, legge tutto il contenuto, inclusi markup, come una stringa. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Quando sovrascritto in una classe derivata, legge il contenuto, inclusi markup, che rappresenta questo nodo e tutti i suoi figli. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Verifica che il nodo corrente sia un elemento e sposta il lettore al nodo successivo. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Verifica che il nodo di contenuto corrente sia un elemento con il valore [XmlReader::get_Name](../xmlreader/get_name/) fornito e sposta il lettore al nodo successivo. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Verifica che il nodo di contenuto corrente sia un elemento con i valori [XmlReader::get_LocalName](../xmlreader/get_localname/) e [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) forniti e sposta il lettore al nodo successivo. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Legge il contenuto di un elemento o di un nodo di testo come una stringa. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Restituisce una nuova istanza di [XmlReader](../xmlreader/) che può essere usata per leggere il nodo corrente e tutti i suoi discendenti. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Avanza il [XmlReader](../xmlreader/) al prossimo elemento discendente con il nome qualificato specificato. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Avanza il [XmlReader](../xmlreader/) al prossimo elemento discendente con il nome locale e l'URI dello spazio dei nomi specificati. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Legge fino a quando viene trovato un elemento con il nome qualificato specificato. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Legge fino a quando viene trovato un elemento con il nome locale e l'URI dello spazio dei nomi specificati. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Avanza il [XmlReader](../xmlreader/) al prossimo elemento fratello con il nome qualificato specificato. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Avanza il [XmlReader](../xmlreader/) al prossimo elemento fratello con il nome locale e l'URI dello spazio dei nomi specificati. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Legge grandi flussi di testo incorporati in un documento XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| void [ResetState](./resetstate/)() | Reimposta lo stato del lettore a [ReadState::Initial](../readstate/). |
| void [ResolveEntity](./resolveentity/)() override | Risolve il riferimento all'entità per i nodi **EntityReference**. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Imposta l'enumerazione DtdProcessing. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Imposta un valore che specifica come il lettore gestisce le entità. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Imposta un valore che indica se abilitare il supporto agli spazi dei nomi. |
| void [set_Normalization](./set_normalization/)(**bool**) | Imposta un valore che indica se normalizzare spazi bianchi e valori degli attributi. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Imposta un valore che indica se consentire l'elaborazione DTD. |
| void [set_WhitespaceHandling](./set_whitespacehandling/)([System::Xml::WhitespaceHandling](../whitespacehandling/)) | Imposta un valore che specifica come gestire gli spazi bianchi. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Imposta il [XmlResolver](../xmlresolver/) utilizzato per risolvere i riferimenti DTD. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (invece di condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| void [Skip](./skip/)() override | Salta i figli del nodo corrente. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente di convertire oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Inizializza una nuova istanza della classe [XmlTextReader](./) con lo stream specificato. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Inizializza una nuova istanza della classe [XmlTextReader](./) con l'URL e lo stream specificati. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Inizializza una nuova istanza della classe [XmlTextReader](./) con lo stream e il [XmlNameTable](../xmlnametable/) specificati. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Inizializza una nuova istanza della classe [XmlTextReader](./) con l'URL, lo stream e il [XmlNameTable](../xmlnametable/) specificati. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Inizializza una nuova istanza della classe [XmlTextReader](./) con il TextReader specificato. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Inizializza una nuova istanza della classe [XmlTextReader](./) con l'URL e il TextReader specificati. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Inizializza una nuova istanza della classe [XmlTextReader](./) con il TextReader e [XmlNameTable](../xmlnametable/) specificati. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Inizializza una nuova istanza della classe [XmlTextReader](./) con l'URL, il TextReader e [XmlNameTable](../xmlnametable/) specificati. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Inizializza una nuova istanza della classe [XmlTextReader](./) con lo stream, XmlNodeType e [XmlParserContext](../xmlparsercontext/) specificati. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Inizializza una nuova istanza della classe [XmlTextReader](./) con la stringa, XmlNodeType e [XmlParserContext](../xmlparsercontext/) specificati. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&) | Inizializza una nuova istanza della classe [XmlTextReader](./) con il file specificato. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Inizializza una nuova istanza della classe [XmlTextReader](./) con il file e [XmlNameTable](../xmlnametable/) specificati. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
## Typedefs

| Typedef | Descrizione |
| --- | --- |
| [Ptr](./ptr/) | Un alias per un puntatore condiviso a un'istanza di questa classe. |
## Remarks

Si consiglia di utilizzare la classe [XmlReader](../xmlreader/) al suo posto. 

Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché ciò provocerebbe errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarla alle funzioni come argomento. 

## See Also

* Classe [XmlReader](../xmlreader/)
* Classe [IXmlLineInfo](../ixmllineinfo/)
* Classe [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namespace [System::Xml](../)
* Libreria [Aspose.Slides](../../)