---
title: XmlTextReader
second_title: Aspose.Slides C++ API referencia
description: Egy olvasót reprezentál, amely gyors, nem gyorsítótárazott, csak előrehaladó hozzáférést biztosít az XML adatokhoz.
type: docs
weight: 508
url: /hu/system.xml/xmltextreader/
---
## XmlTextReader osztály

Egy olvasót képvisel, amely gyors, nem gyorsítótárazott, csak előre haladó hozzáférést biztosít az XML adatokhoz.

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| void [Close](./close/)() override | Megváltoztatja a [XmlReader::get_ReadState](../xmlreader/get_readstate/) értékét **Closed**-ra. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott URI-val. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott URI és beállítások használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott URI, beállítások és a feldolgozási kontextus információk használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott adatfolyam használatával alapértelmezett beállításokkal. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott adatfolyam és beállítások használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott adatfolyam, alap URI és beállítások használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott adatfolyam, beállítások és a feldolgozási kontextus információk használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott szövegolvasó használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott szövegolvasó és beállítások használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott szövegolvasó, beállítások és alap URI használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott szövegolvasó, beállítások és a feldolgozási kontextus információk használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott XML-olvasó és beállítások használatával. |
| void [Dispose](../xmlreader/dispose/)() override | Felszabadítja az összes erőforrást, amelyet a jelenlegi [XmlReader](../xmlreader/) osztálypéldány használ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlít referenciatípusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlít értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Visszaadja az aktuális csomópont attribútumainak számát. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Visszaadja az aktuális csomópont alap-URI-ját. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Visszaad egy értéket, amely jelzi, hogy a [XmlTextReader](./) implementálja-e a bináris tartalom olvasási metódusokat. |
| **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | Visszaad egy értéket, amely jelzi, hogy a [XmlTextReader](./) implementálja-e a [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) metódust. |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Visszaad egy értéket, amely jelzi, hogy ez az olvasó képes-e entitások feldolgozására és feloldására. |
| **int32_t** [get_Depth](./get_depth/)() override | Visszaadja az aktuális csomópont mélységét az XML dokumentumban. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Visszaadja a DtdProcessing felsorolást. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Visszaadja a dokumentum kódolását. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | Visszaad egy értéket, amely meghatározza, hogyan kezeli az olvasó az entitásokat. |
| **bool** [get_EOF](./get_eof/)() override | Visszaad egy értéket, amely jelzi, hogy az olvasó a stream végén helyezkedik-e el. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | Visszaad egy értéket, amely jelzi, hogy az aktuális csomópont rendelkezik-e attribútumokkal. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Visszaad egy értéket, amely jelzi, hogy az aktuális csomópont rendelkezhet-e [XmlTextReader::get_Value](./get_value/)-vel, amely nem [String::Empty](../../system/string/empty/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Visszaad egy értéket, amely jelzi, hogy az aktuális csomópont egy attribútum-e, amelyet a DTD vagy séma által definiált alapértelmezett értékből generáltak. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Visszaad egy értéket, amely jelzi, hogy az aktuális csomópont egy üres elem-e (például **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | Visszaadja az aktuális sor számát. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | Visszaadja az aktuális sor pozícióját. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Visszaadja az aktuális csomópont helyi nevét. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Visszaadja az aktuális csomópont minősített nevét. |
| **bool** [get_Namespaces](./get_namespaces/)() | Visszaad egy értéket, amely jelzi, hogy engedélyezni kell-e a névtér támogatást. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Visszaadja a névtér URI-ját (ahogy a W3C Namespace specifikáció definiálja) annak a csomópontnak, amelyen az olvasó pozícionálva van. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Visszaadja a [XmlNameTable](../xmlnametable/)-t, amely ehhez a megvalósításhoz kapcsolódik. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Visszaadja az aktuális csomópont típusát. |
| **bool** [get_Normalization](./get_normalization/)() | Visszaad egy értéket, amely jelzi, hogy normalizálni kell-e a szóközöket és az attribútum értékeket. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Visszaadja az aktuális csomóponthoz tartozó névtér előtagot. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Visszaad egy értéket, amely jelzi, hogy engedélyezni kell-e a DTD feldolgozást. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | Visszaadja azt az idézőjel karaktert, amelyet az attribútumcsomópont értékének körülvételéhez használnak. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Visszaadja az olvasó állapotát. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | Visszaadja a sémainformációt, amely a sémavalidáció eredményeként az aktuális csomópontra lett hozzárendelve. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Visszaadja a [XmlReaderSettings](../xmlreadersettings/) objektumot, amely ezzel a [XmlReader](../xmlreader/) példánnyal lett létrehozva. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Visszaadja az aktuális csomópont szöveges értékét. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Visszaadja az aktuális csomópont típusát. |
| [System::Xml::WhitespaceHandling](../whitespacehandling/) [get_WhitespaceHandling](./get_whitespacehandling/)() | Visszaad egy értéket, amely meghatározza, hogyan kezeli a szóközöket. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Visszaadja a jelenlegi **xml:lang** hatókört. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Visszaadja a jelenlegi **xml:space** hatókört. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Visszaadja a megadott névű attribútum értékét. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Visszaadja a megadott helyi névű és névtér URI-jú attribútum értékét. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Visszaadja a megadott indexű attribútum értékét. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../xmlnamespacescope/)) override | Visszaad egy gyűjteményt, amely tartalmazza az aktuálisan hatókörben lévő összes névteret. |
| [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\> [GetRemainder](./getremainder/)() | Visszaadja a pufferelt XML maradékát. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| **bool** [HasLineInfo](./haslineinfo/)() override | Visszaad egy értéket, amely jelzi, hogy az osztály vissza tud-e adni sorinformációt. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Felülírva egy leszármazott osztályban, visszaadja a megadott indexű attribútum értékét. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Felülírva egy leszármazott osztályban, visszaadja a megadott [XmlReader::get_Name](../xmlreader/get_name/) értékű attribútumot. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Felülírva egy leszármazott osztályban, visszaadja a megadott [XmlReader::get_LocalName](../xmlreader/get_localname/) és [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) értékekkel rendelkező attribútumot. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Visszaad egy értéket, amely jelzi, hogy a karakterlánc argumentum érvényes XML-név-e. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Visszaad egy értéket, amely jelzi, hogy a karakterlánc argumentum érvényes XML névtokent van-e. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Meghívja a [XmlReader::MoveToContent](../xmlreader/movetocontent/)-t, és ellenőrzi, hogy a jelenlegi tartalomcsomópont egy kezdő vagy üres elemcímke-e. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Meghívja a [XmlReader::MoveToContent](../xmlreader/movetocontent/)-t, és ellenőrzi, hogy a jelenlegi tartalomcsomópont egy kezdő vagy üres elemcímke-e, valamint hogy a megtalált elem [XmlReader::get_Name](../xmlreader/get_name/) értéke megegyezik-e a megadott argumentummal. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Meghívja a [XmlReader::MoveToContent](../xmlreader/movetocontent/)-t, és ellenőrzi, hogy a jelenlegi tartalomcsomópont egy kezdő vagy üres elemcímke-e, valamint hogy a megtalált elem [XmlReader::get_LocalName](../xmlreader/get_localname/) és [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) értékei megegyeznek-e a megadott karakterláncokkal. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) felügyeleti objektumot. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Feloldja a névtér előtagot az aktuális elem hatókörében. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Átmozdul a megadott nevű attribútumra. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Átmozdul a megadott helyi névű és névtér URI-jú attribútumra. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Átmozdul a megadott indexű attribútumra. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Ellenőrzi, hogy az aktuális csomópont tartalom (nem szóköz karakter, **CDATA**, **Element**, **EndElement**, **EntityReference**, vagy **EndEntity**) csomópont-e. Ha a csomópont nem tartalom, az olvasó a következő tartalomcsomópontra vagy a fájl végét ugrik. Átugorja a következő típusú csomópontokat: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, vagy **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Átmozdul arra az elemre, amely tartalmazza az aktuális attribútumcsomópontot. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Átmozdul az első attribútumra. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Átmozdul a következő attribútumra. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másoló konstrukcióját. |
| **bool** [Read](./read/)() override | Olvassa a következő csomópontot a stream-ből. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Az attribútum értékét egy vagy több **[Text](../../system.text/)**, **EntityReference**, vagy **EndEntity** csomóppá dolgozza fel. |
| **int32_t** [ReadBase64](./readbase64/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Dekódolja a Base64-et és visszaadja a dekódolt bináris bájtokat. |
| **int32_t** [ReadBinHex](./readbinhex/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Dekódolja a **BinHex**-et és visszaadja a dekódolt bináris bájtokat. |
| **int32_t** [ReadChars](./readchars/)(const [ArrayPtr](../../system/arrayptr/)\<char16_t\>\&, **int32_t**, **int32_t**) | Beolvassa egy elem szövegtartalmát egy karakterpufferbe. Ez a metódus nagy mennyiségű beágyazott szövegfolyam olvasására lett tervezve, egymást követő hívásokkal. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Beolvassa a tartalmat a megadott típusú objektumként. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Beolvassa a tartalmat, és visszaadja a **Base64**-del dekódolt bináris bájtokat. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Beolvassa a tartalmat, és visszaadja a **BinHex**-szel dekódolt bináris bájtokat. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Beolvassa a szövegtartalmat a jelenlegi pozícióban [Boolean](../../system/boolean/)-ként. |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Beolvassa a szövegtartalmat a jelenlegi pozícióban [DateTime](../../system/datetime/) objektumként. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Beolvassa a szövegtartalmat a jelenlegi pozícióban [DateTimeOffset](../../system/datetimeoffset/) objektumként. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Beolvassa a szövegtartalmat a jelenlegi pozícióban [Decimal](../../system/decimal/) objektumként. |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Beolvassa a szövegtartalmat a jelenlegi pozícióban dupla pontosságú lebegőpontos számként. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Beolvassa a szövegtartalmat a jelenlegi pozícióban egyszeres pontosságú lebegőpontos számként. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Beolvassa a szövegtartalmat a jelenlegi pozícióban 32 bites előjeles egész számként. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Beolvassa a szövegtartalmat a jelenlegi pozícióban 64 bites előjeles egész számként. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Beolvassa a szövegtartalmat a jelenlegi pozícióban [Object](../../system/object/)-ként. |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Beolvassa a szövegtartalmat a jelenlegi pozícióban [String](../../system/string/) objektumként. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Beolvassa az elem tartalmát a kért típusként. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI megegyezik-e a jelenlegi elemével, majd beolvassa az elem tartalmát a kért típusként. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Beolvassa az elemet, és dekódolja a Base64 tartalmat. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Beolvassa az elemet, és dekódolja a **BinHex** tartalmat. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Beolvassa a jelenlegi elemet, és visszaadja a tartalmat [Boolean](../../system/boolean/) objektumként. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI megegyezik-e a jelenlegi elemével, majd beolvassa a jelenlegi elemet, és visszaadja a tartalmat [Boolean](../../system/boolean/) objektumként. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Beolvassa a jelenlegi elemet, és visszaadja a tartalmat [DateTime](../../system/datetime/) objektumként. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI megegyezik-e a jelenlegi elemével, majd beolvassa a jelenlegi elemet, és visszaadja a tartalmat [DateTime](../../system/datetime/) objektumként. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Beolvassa a jelenlegi elemet, és visszaadja a tartalmat [Decimal](../../system/decimal/) objektumként. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI megegyezik-e a jelenlegi elemével, majd beolvassa a jelenlegi elemet, és visszaadja a tartalmat [Decimal](../../system/decimal/) objektumként. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Beolvassa a jelenlegi elemet, és visszaadja a tartalmat dupla pontosságú lebegőpontos számként. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI megegyezik-e a jelenlegi elemével, majd beolvassa a jelenlegi elemet, és visszaadja a tartalmat dupla pontosságú lebegőpontos számként. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Beolvassa a jelenlegi elemet, és visszaadja a tartalmat egyszeres pontosságú lebegőpontos számként. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI megegyezik-e a jelenlegi elemével, majd beolvassa a jelenlegi elemet, és visszaadja a tartalmat egyszeres pontosságú lebegőpontos számként. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Beolvassa a jelenlegi elemet, és visszaadja a tartalmat 32 bites előjeles egész számként. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI megegyezik-e a jelenlegi elemével, majd beolvassa a jelenlegi elemet, és visszaadja a tartalmat 32 bites előjeles egész számként. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Beolvassa a jelenlegi elemet, és visszaadja a tartalmat 64 bites előjeles egész számként. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI megegyezik-e a jelenlegi elemével, majd beolvassa a jelenlegi elemet, és visszaadja a tartalmat 64 bites előjeles egész számként. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Beolvassa a jelenlegi elemet, és visszaadja a tartalmat [Object](../../system/object/)-ként. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI megegyezik-e a jelenlegi elemével, majd beolvassa a jelenlegi elemet, és visszaadja a tartalmat [Object](../../system/object/)-ként. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Beolvassa a jelenlegi elemet, és visszaadja a tartalmat [String](../../system/string/) objektumként. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI megegyezik-e a jelenlegi elemével, majd beolvassa a jelenlegi elemet, és visszaadja a tartalmat [String](../../system/string/) objektumként. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Beolvassa a csak szövegből álló elemet. Azonban ajánlott a [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) metódust használni helyette, mert ez egyszerűbb megoldást kínál a művelet kezelésére. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Ellenőrzi, hogy a megtalált elem [XmlReader::get_Name](../xmlreader/get_name/) értéke megegyezik-e a megadott karakterlánccal, mielőtt csak szövegből álló elemet olvasna. Azonban ajánlott a [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) metódust használni helyette, mert ez egyszerűbb megoldást kínál a művelet kezelésére. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megtalált elem [XmlReader::get_LocalName](../xmlreader/get_localname/) és [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) értékei megegyeznek-e a megadott karakterláncokkal, mielőtt csak szövegből álló elemet olvasna. Azonban ajánlott a [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) metódust használni helyette, mert ez egyszerűbb megoldást kínál a művelet kezelésére. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Ellenőrzi, hogy a jelenlegi tartalomcsomópont egy záró címke, és a olvasót a következő csomópontra lépteti. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Ha felül van definiálva egy származtatott osztályban, a teljes tartalmat, beleértve a jelölőnyelvet, karakterláncként olvassa. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Ha felül van definiálva egy származtatott osztályban, a tartalmat, beleértve a jelölőnyelvet, amely ezt a csomópontot és minden gyermekét ábrázolja, olvassa. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Ellenőrzi, hogy a jelenlegi csomópont egy elem, és az olvasót a következő csomópontra lépteti. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Ellenőrzi, hogy a jelenlegi tartalomcsomópont egy elem a megadott [XmlReader::get_Name](../xmlreader/get_name/) értékkel, és az olvasót a következő csomópontra lépteti. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a jelenlegi tartalomcsomópont egy elem a megadott [XmlReader::get_LocalName](../xmlreader/get_localname/) és [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) értékekkel, és az olvasót a következő csomópontra lépteti. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Beolvassa egy elem vagy szövegcímke tartalmát karakterláncként. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Visszaad egy új [XmlReader](../xmlreader/) példányt, amely a jelenlegi csomópont és annak minden leszármazottja beolvasására használható. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | A [XmlReader](../xmlreader/)-t a megadott kvalifikált névvel rendelkező következő leszármazott elemhez lépteti. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | A [XmlReader](../xmlreader/)-t a megadott helyi névvel és névtér URI-val rendelkező következő leszármazott elemhez lépteti. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Olvas tovább, amíg a megadott kvalifikált névvel rendelkező elem meg nem jelenik. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Olvas tovább, amíg a megadott helyi névvel és névtér URI-val rendelkező elem meg nem jelenik. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | A [XmlReader](../xmlreader/)-t a megadott kvalifikált névvel rendelkező következő testvér elemhez lépteti. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | A [XmlReader](../xmlreader/)-t a megadott helyi névvel és névtér URI-val rendelkező következő testvér elemhez lépteti. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Nagy mennyiségű, XML-dokumentumba beágyazott szövegfolyamot olvas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot hivatkozás alapján hasonlít össze a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott hivatkozásszámlálót a megadott értékkel. |
| void [ResetState](./resetstate/)() | Visszaállítja az olvasó állapotát [ReadState::Initial](../readstate/)-ra. |
| void [ResolveEntity](./resolveentity/)() override | Feloldja az entitás hivatkozást **EntityReference** csomópontokhoz. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Beállítja a DtdProcessing felsorolást. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Beállít egy értéket, amely meghatározza, hogyan kezeli az olvasó az entitásokat. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Beállít egy értéket, amely jelzi, hogy legyen-e névtér támogatás. |
| void [set_Normalization](./set_normalization/)(**bool**) | Beállít egy értéket, amely jelzi, hogy normalizálja-e a szóközöket és attribútumértékeket. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Beállít egy értéket, amely jelzi, hogy engedélyezett-e a DTD feldolgozás. |
| void [set_WhitespaceHandling](./set_whitespacehandling/)([System::Xml::WhitespaceHandling](../whitespacehandling/)) | Beállít egy értéket, amely meghatározza, hogyan kezelje a szóközöket. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Beállítja a [XmlResolver](../xmlresolver/)-t a DTD hivatkozások feloldásához. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóként (nem megosztott). Lehetővé teszi a mutatók átkapcsolását konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott hivatkozásszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott hivatkozásszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott hivatkozásszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [Skip](./skip/)() override | Átugorja a jelenlegi csomópont gyermekelemeit. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge hivatkozásszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge hivatkozásszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Új példányt inicializál a [XmlTextReader](./) osztályból a megadott adatfolyammal. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Új példányt inicializál a [XmlTextReader](./) osztályból a megadott URL-lel és adatfolyammal. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Új példányt inicializál a [XmlTextReader](./) osztályból a megadott adatfolyammal és [XmlNameTable](../xmlnametable/)-val. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Új példányt inicializál a [XmlTextReader](./) osztályból a megadott URL-lel, adatfolyammal és [XmlNameTable](../xmlnametable/)-val. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Új példányt hoz létre a [XmlTextReader](./) osztályból a megadott TextReader-rel. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Új példányt hoz létre a [XmlTextReader](./) osztályból a megadott URL és TextReader használatával. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Új példányt hoz létre a [XmlTextReader](./) osztályból a megadott TextReader és [XmlNameTable](../xmlnametable/) használatával. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Új példányt hoz létre a [XmlTextReader](./) osztályból a megadott URL, TextReader és [XmlNameTable](../xmlnametable/) használatával. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Új példányt hoz létre a [XmlTextReader](./) osztályból a megadott stream, XmlNodeType és [XmlParserContext](../xmlparsercontext/) használatával. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Új példányt hoz létre a [XmlTextReader](./) osztályból a megadott string, XmlNodeType és [XmlParserContext](../xmlparsercontext/) használatával. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&) | Új példányt hoz létre a [XmlTextReader](./) osztályból a megadott fájllal. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Új példányt hoz létre a [XmlTextReader](./) osztályból a megadott fájl és [XmlNameTable](../xmlnametable/) használatával. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Egy alias a megosztott mutatóhoz, amely erre az osztályra mutat. |
## Megjegyzések

Javasolt a [XmlReader](../xmlreader/) osztályt használni helyette. 

Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányokat ebből a típusból a veremben vagy az operator new használatával, mivel ez futásidő hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek. 

## Lásd még

* [XmlReader](../xmlreader/) osztály
* [IXmlLineInfo](../ixmllineinfo/) osztály
* [IXmlNamespaceResolver](../ixmlnamespaceresolver/) osztály
* [System::Xml](../) névtér
* [Aspose.Slides](../../) könyvtár