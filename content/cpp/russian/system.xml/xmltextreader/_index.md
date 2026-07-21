---
title: XmlTextReader
second_title: Справочник API Aspose.Slides for C++
description: Представляет читатель, обеспечивающий быстрый, не кэшируемый, только прямой доступ к XML-данным.
type: docs
weight: 508
url: /ru/system.xml/xmltextreader/
---
## XmlTextReader класс


Представляет читатель, который обеспечивает быстрый, не кэшируемый, только прямой доступ к данным XML.

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```

## Методы

| Метод | Описание |
| --- | --- |
| void [Close](./close/)() override | Изменяет [XmlReader::get_ReadState](../xmlreader/get_readstate/) на **Closed**. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Создает новый экземпляр [XmlReader](../xmlreader/) с указанным URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Создает новый экземпляр [XmlReader](../xmlreader/) с использованием указанного URI и настроек. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Создает новый экземпляр [XmlReader](../xmlreader/) с использованием указанного URI, настроек и контекстной информации для разбора. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Создает новый экземпляр [XmlReader](../xmlreader/) с использованием указанного потока и настроек по умолчанию. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Создает новый экземпляр [XmlReader](../xmlreader/) с указанным потоком и настройками. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Создает новый экземпляр [XmlReader](../xmlreader/) с использованием указанного потока, базового URI и настроек. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Создает новый экземпляр [XmlReader](../xmlreader/) с использованием указанного потока, настроек и контекстной информации для разбора. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Создает новый экземпляр [XmlReader](../xmlreader/) с использованием указанного текстового читателя. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Создает новый экземпляр [XmlReader](../xmlreader/) с использованием указанного текстового читателя и настроек. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Создает новый экземпляр [XmlReader](../xmlreader/) с использованием указанного текстового читателя, настроек и базового URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Создает новый экземпляр [XmlReader](../xmlreader/) с использованием указанного текстового читателя, настроек и контекстной информации для разбора. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Создает новый экземпляр [XmlReader](../xmlreader/) с использованием указанного XML-читателя и настроек. |
| void [Dispose](../xmlreader/dispose/)() override | Освобождает все ресурсы, используемые текущим экземпляром класса [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равно никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равно никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Возвращает количество атрибутов в текущем узле. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Возвращает базовый URI текущего узла. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Возвращает значение, указывающее, реализует ли [XmlTextReader](./) методы чтения бинарного содержимого. |
| **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | Возвращает значение, указывающее, реализует ли [XmlTextReader](./) метод [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Возвращает значение, указывающее, может ли этот читатель разбирать и разрешать сущности. |
| **int32_t** [get_Depth](./get_depth/)() override | Возвращает глубину текущего узла в XML-документе. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Возвращает перечисление DtdProcessing. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Возвращает кодировку документа. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | Возвращает значение, определяющее, как читатель обрабатывает сущности. |
| **bool** [get_EOF](./get_eof/)() override | Возвращает значение, указывающее, находится ли читатель в конце потока. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | Возвращает значение, указывающее, имеет ли текущий узел какие-либо атрибуты. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Возвращает значение, указывающее, может ли текущий узел иметь [XmlTextReader::get_Value](./get_value/), отличный от [String::Empty](../../system/string/empty/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Возвращает значение, указывающее, является ли текущий узел атрибутом, сгенерированным из значения по умолчанию, определённого в DTD или схеме. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Возвращает значение, указывающее, является ли текущий узел пустым элементом (например, **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | Возвращает текущий номер строки. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | Возвращает текущую позицию в строке. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Возвращает локальное имя текущего узла. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Возвращает квалифицированное имя текущего узла. |
| **bool** [get_Namespaces](./get_namespaces/)() | Возвращает значение, указывающее, включена ли поддержка пространств имён. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Возвращает URI пространства имён (как определено в спецификации W3C Namespace) узла, на котором находится читатель. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Возвращает [XmlNameTable](../xmlnametable/), связанный с этой реализацией. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Возвращает тип текущего узла. |
| **bool** [get_Normalization](./get_normalization/)() | Возвращает значение, указывающее, следует ли нормализовать пробельные символы и значения атрибутов. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Возвращает префикс пространства имён, связанный с текущим узлом. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Возвращает значение, указывающее, разрешать ли обработку DTD. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | Возвращает символ кавычки, используемый для заключения значения узла-атрибута. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Возвращает состояние читателя. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | Возвращает информацию схемы, присвоенную текущему узлу в результате проверки схемы. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Возвращает объект [XmlReaderSettings](../xmlreadersettings/), используемый для создания этого экземпляра [XmlReader](../xmlreader/). |
| [String](../../system/string/) [get_Value](./get_value/)() override | Возвращает текстовое значение текущего узла. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Возвращает тип текущего узла. |
| [System::Xml::WhitespaceHandling](../whitespacehandling/) [get_WhitespaceHandling](./get_whitespacehandling/)() | Возвращает значение, определяющее, как обрабатываются пробелы. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Возвращает текущую область **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Возвращает текущую область **xml:space**. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Возвращает значение атрибута с указанным именем. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Возвращает значение атрибута с указанным локальным именем и URI пространства имён. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Возвращает значение атрибута с указанным индексом. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../xmlnamespacescope/)) override | Возвращает коллекцию, содержащую все текущие действующие пространства имён. |
| [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\> [GetRemainder](./getremainder/)() | Возвращает остаток буферизованного XML. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [HasLineInfo](./haslineinfo/)() override | Возвращает значение, указывающее, может ли класс возвращать информацию о строках. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | При переопределении в производном классе получает значение атрибута с указанным индексом. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | При переопределении в производном классе получает значение атрибута с указанным значением [XmlReader::get_Name](../xmlreader/get_name/). |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | При переопределении в производном классе получает значение атрибута с указанными значениями [XmlReader::get_LocalName](../xmlreader/get_localname/) и [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Возвращает значение, указывающее, является ли строковый аргумент допустимым XML-именем. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Возвращает значение, указывающее, является ли строковый аргумент допустимым токеном XML-имени. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Вызывает [XmlReader::MoveToContent](../xmlreader/movetocontent/) и проверяет, является ли текущий узел содержимого стартовым тегом или тегом пустого элемента. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Вызывает [XmlReader::MoveToContent](../xmlreader/movetocontent/) и проверяет, является ли текущий узел содержимого стартовым тегом или тегом пустого элемента и соответствует ли значение [XmlReader::get_Name](../xmlreader/get_name/) найденного элемента переданному аргументу. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Вызывает [XmlReader::MoveToContent](../xmlreader/movetocontent/) и проверяет, является ли текущий узел содержимого стартовым тегом или тегом пустого элемента и соответствуют ли значения [XmlReader::get_LocalName](../xmlreader/get_localname/) и [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) найденного элемента заданным строкам. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Разрешает префикс пространства имён в области текущего элемента. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Переходит к атрибуту с указанным именем. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Переходит к атрибуту с указанным локальным именем и URI пространства имён. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Переходит к атрибуту с указанным индексом. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Проверяет, является ли текущий узел контентным (текст без пробелов, **CDATA**, **Element**, **EndElement**, **EntityReference** или **EndEntity**). Если узел не является контентным, читатель переходит к следующему контентному узлу или к концу файла. Он пропускает узлы следующих типов: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** или **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Переходит к элементу, содержащему текущий узел-атрибут. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Переходит к первому атрибуту. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Переходит к следующему атрибуту. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. Не копирует ничего, на самом деле только инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. Не копирует ничего, на самом деле только инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| **bool** [Read](./read/)() override | Считывает следующий узел из потока. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Разбирает значение атрибута в один или несколько узлов **[Text](../../system.text/)**, **EntityReference** или **EndEntity**. |
| **int32_t** [ReadBase64](./readbase64/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Декодирует Base64 и возвращает декодированные байты. |
| **int32_t** [ReadBinHex](./readbinhex/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Декодирует **BinHex** и возвращает декодированные байты. |
| **int32_t** [ReadChars](./readchars/)(const [ArrayPtr](../../system/arrayptr/)\<char16_t\>\&, **int32_t**, **int32_t**) | Считывает текстовое содержимое элемента в буфер символов. Этот метод предназначен для последовательного чтения больших потоков встроенного текста. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Считывает содержимое как объект указанного типа. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Считывает содержимое и возвращает декодированные из **Base64** байты. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Считывает содержимое и возвращает декодированные из **BinHex** байты. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Считывает текстовое содержание в текущей позиции как [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Считывает текстовое содержание в текущей позиции как объект [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Считывает текстовое содержание в текущей позиции как объект [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Считывает текстовое содержание в текущей позиции как объект [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Считывает текстовое содержание в текущей позиции как число двойной точности с плавающей запятой. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Считывает текстовое содержание в текущей позиции как число одинарной точности с плавающей запятой. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Считывает текстовое содержание в текущей позиции как 32-битное целое со знаком. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Считывает текстовое содержание в текущей позиции как 64-битное целое со знаком. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Считывает текстовое содержание в текущей позиции как [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Считывает текстовое содержание в текущей позиции как объект [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Считывает содержимое элемента как запрошенный тип. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадает ли указанные локальное имя и URI пространства имён с текущим элементом, затем считывает содержимое элемента как указанный тип. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Считывает элемент и декодирует содержимое Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Считывает элемент и декодирует содержимое **BinHex**. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Считывает текущий элемент и возвращает содержимое как объект [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадает ли указанные локальное имя и URI пространства имён с текущим элементом, затем считывает текущий элемент и возвращает содержимое как объект [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Считывает текущий элемент и возвращает содержимое как объект [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадает ли указанные локальное имя и URI пространства имён с текущим элементом, затем считывает текущий элемент и возвращает содержимое как объект [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Считывает текущий элемент и возвращает содержимое как объект [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадает ли указанные локальное имя и URI пространства имён с текущим элементом, затем считывает текущий элемент и возвращает содержимое как объект [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Считывает текущий элемент и возвращает содержимое как число двойной точности с плавающей запятой. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадает ли указанные локальное имя и URI пространства имён с текущим элементом, затем считывает текущий элемент и возвращает содержимое как число двойной точности с плавающей запятой. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Считывает текущий элемент и возвращает содержимое как число одинарной точности с плавающей запятой. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадает ли указанные локальное имя и URI пространства имён с текущим элементом, затем считывает текущий элемент и возвращает содержимое как число одинарной точности с плавающей запятой. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Считывает текущий элемент и возвращает содержимое как 32-битное целое со знаком. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадает ли указанные локальное имя и URI пространства имён с текущим элементом, затем считывает текущий элемент и возвращает содержимое как 32-битное целое со знаком. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Считывает текущий элемент и возвращает содержимое как 64-битное целое со знаком. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадает ли указанные локальное имя и URI пространства имён с текущим элементом, затем считывает текущий элемент и возвращает содержимое как 64-битное целое со знаком. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Считывает текущий элемент и возвращает содержимое как [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадает ли указанные локальное имя и URI пространства имён с текущим элементом, затем считывает текущий элемент и возвращает содержимое как [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Считывает текущий элемент и возвращает содержимое как объект [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадает ли указанные локальное имя и URI пространства имён с текущим элементом, затем считывает текущий элемент и возвращает содержимое как [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Считывает элемент, содержащий только текст. Однако рекомендуется использовать метод [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), поскольку он предоставляет более простой способ обработки этой операции. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Проверяет, совпадает ли значение [XmlReader::get_Name](../xmlreader/get_name/) найденного элемента с заданной строкой перед чтением элемента, содержащего только текст. Однако рекомендуется использовать метод [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), поскольку он предоставляет более простой способ обработки этой операции. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадают ли значения [XmlReader::get_LocalName](../xmlreader/get_localname/) и [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) найденного элемента с заданными строками перед чтением элемента, содержащего только текст. Однако рекомендуется использовать метод [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), поскольку он предоставляет более простой способ обработки этой операции. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Проверяет, что текущий узел содержимого является конечным тегом, и перемещает читатель к следующему узлу. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | При переопределении в производном классе считывает всё содержимое, включая разметку, как строку. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | При переопределении в производном классе считывает содержимое, включая разметку, представляющее этот узел и все его дочерние элементы. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Проверяет, что текущий узел является элементом, и перемещает читатель к следующему узлу. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Проверяет, что текущий узел содержимого является элементом с заданным значением [XmlReader::get_Name](../xmlreader/get_name/) и перемещает читатель к следующему узлу. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, что текущий узел содержимого является элементом с заданными значениями [XmlReader::get_LocalName](../xmlreader/get_localname/) и [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) и перемещает читатель к следующему узлу. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Считывает содержимое элемента или текстового узла как строку. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Возвращает новый экземпляр [XmlReader](../xmlreader/), который можно использовать для чтения текущего узла и всех его потомков. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Перемещает [XmlReader](../xmlreader/) к следующему дочернему элементу с указанным квалифицированным именем. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Перемещает [XmlReader](../xmlreader/) к следующему дочернему элементу с указанным локальным именем и URI пространства имён. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Читает, пока не будет найден элемент с указанным квалифицированным именем. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Читает, пока не будет найден элемент с указанным локальным именем и URI пространства имён. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Перемещает [XmlReader](../xmlreader/) к следующему соседнему элементу с указанным квалифицированным именем. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Перемещает [XmlReader](../xmlreader/) к следующему соседнему элементу с указанным локальным именем и URI пространства имён. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Считывает большие потоки текста, встроенные в XML-документ. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [ResetState](./resetstate/)() | Сбрасывает состояние читателя до [ReadState::Initial](../readstate/). |
| void [ResolveEntity](./resolveentity/)() override | Разрешает ссылку сущности для узлов **EntityReference**. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Устанавливает перечисление DtdProcessing. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Устанавливает значение, определяющее, как читатель обрабатывает сущности. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Устанавливает значение, указывающее, включена ли поддержка пространств имён. |
| void [set_Normalization](./set_normalization/)(**bool**) | Устанавливает значение, указывающее, следует ли нормализовать пробельные символы и значения атрибутов. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Устанавливает значение, указывающее, разрешать ли обработку DTD. |
| void [set_WhitespaceHandling](./set_whitespacehandling/)([System::Xml::WhitespaceHandling](../whitespacehandling/)) | Устанавливает значение, определяющее, как обрабатываются пробелы. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Устанавливает [XmlResolver](../xmlresolver/), используемый для разрешения DTD-ссылок. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-ый шаблонный аргумент в виде слабого указателя (вместо общего). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [Skip](./skip/)() override | Пропускает дочерние узлы текущего узла. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным потоком. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным URL и потоком. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным потоком и [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным URL, потоком и [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным TextReader. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным URL и TextReader. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным TextReader и [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным URL, TextReader и [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным потоком, XmlNodeType и [XmlParserContext](../xmlparsercontext/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанной строкой, XmlNodeType и [XmlParserContext](../xmlparsercontext/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным файлом. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Инициализирует новый экземпляр класса [XmlTextReader](./) с указанным файлом и [XmlNameTable](../xmlnametable/). |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
## Типы

| Тип | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для умного указателя на экземпляр этого класса. |
## Примечания

Рекомендуется использовать вместо этого класс [XmlReader](../xmlreader/).

Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, поскольку это приведёт к ошибкам времени выполнения и/или сбоям проверок. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его функциям в качестве аргумента.

## Смотрите также

* Класс [XmlReader](../xmlreader/)
* Класс [IXmlLineInfo](../ixmllineinfo/)
* Класс [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Пространство имён [System::Xml](../)
* Библиотека [Aspose.Slides](../../)