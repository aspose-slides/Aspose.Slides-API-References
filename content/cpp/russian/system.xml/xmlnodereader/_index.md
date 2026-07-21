---
title: XmlNodeReader
second_title: Aspose.Slides для C++ — справочник API
description: Представляет читатель, обеспечивающий быстрый, некешированный доступ только в прямом направлении к XML-данным в XmlNode.
type: docs
weight: 365
url: /ru/system.xml/xmlnodereader/
---
## XmlNodeReader класс

Представляет читатель, который обеспечивает быстрый, некешированный, только прямой доступ к XML-данным в [XmlNode](../xmlnode/).

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## Методы

| Метод | Описание |
| --- | --- |
| void [Close](./close/)() override | Изменяет [XmlNodeReader::get_ReadState](./get_readstate/) на [ReadState::Closed](../readstate/). |
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
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типом значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равно никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равно никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Возвращает количество атрибутов на текущем узле. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Возвращает базовый URI текущего узла. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Возвращает значение, указывающее, реализует ли [XmlNodeReader](./) методы чтения бинарного содержимого. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | Возвращает значение, указывающее, реализует ли [XmlReader](../xmlreader/) метод [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Возвращает значение, указывающее, может ли этот читатель разбирать и разрешать сущности. |
| **int32_t** [get_Depth](./get_depth/)() override | Возвращает глубину текущего узла в XML-документе. |
| **bool** [get_EOF](./get_eof/)() override | Возвращает значение, указывающее, находится ли читатель в конце потока. |
| **bool** [get_HasAttributes](./get_hasattributes/)() override | Возвращает значение, указывающее, имеет ли текущий узел какие-либо атрибуты. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Возвращает значение, указывающее, может ли текущий узел иметь значение [XmlNodeReader::get_Value](./get_value/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Возвращает значение, указывающее, является ли текущий узел атрибутом, созданным из значения по умолчанию, определенного в DTD или схеме. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Возвращает значение, указывающее, является ли текущий узел пустым элементом (например, **<MyElement/>**). |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Возвращает локальное имя текущего узла. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Возвращает квалифицированное имя текущего узла. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Возвращает URI пространства имен (как определено в спецификации W3C Namespace) узла, на котором находится читатель. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Возвращает [XmlNameTable](../xmlnametable/), связанный с этой реализацией. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Возвращает тип текущего узла. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Возвращает префикс пространства имен, связанный с текущим узлом. |
| virtual char16_t [get_QuoteChar](../xmlreader/get_quotechar/)() | При переопределении в производном классе возвращает символ кавычки, используемый для заключения значения узла-атрибута. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Возвращает состояние читателя. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | Возвращает информацию схемы, назначенную текущему узлу. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Возвращает объект [XmlReaderSettings](../xmlreadersettings/), используемый для создания этого экземпляра [XmlReader](../xmlreader/). |
| [String](../../system/string/) [get_Value](./get_value/)() override | Возвращает текстовое значение текущего узла. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Возвращает тип текущего узла. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Возвращает текущий диапазон **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Возвращает текущий диапазон **xml:space**. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Возвращает значение атрибута с указанным именем. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Возвращает значение атрибута с указанным локальным именем и URI пространства имен. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Возвращает значение атрибута с указанным индексом. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хэшировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | При переопределении в производном классе получает значение атрибута с указанным индексом. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | При переопределении в производном классе получает значение атрибута с указанным значением [XmlReader::get_Name](../xmlreader/get_name/). |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | При переопределении в производном классе получает значение атрибута с указанными значениями [XmlReader::get_LocalName](../xmlreader/get_localname/) и [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Возвращает значение, указывающее, является ли строковый аргумент допустимым именем XML. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Возвращает значение, указывающее, является ли строковый аргумент допустимым токеном имени XML. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Выполняет вызов [XmlReader::MoveToContent](../xmlreader/movetocontent/) и проверяет, является ли текущий узел содержимого начальной меткой или меткой пустого элемента. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Выполняет вызов [XmlReader::MoveToContent](../xmlreader/movetocontent/) и проверяет, является ли текущий узел содержимого начальной меткой или меткой пустого элемента и совпадает ли значение [XmlReader::get_Name](../xmlreader/get_name/) найденного элемента с переданным аргументом. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Выполняет вызов [XmlReader::MoveToContent](../xmlreader/movetocontent/) и проверяет, является ли текущий узел содержимого начальной меткой или меткой пустого элемента и совпадают ли значения [XmlReader::get_LocalName](../xmlreader/get_localname/) и [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) найденного элемента с указанными строками. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Разрешает префикс пространства имен в области действия текущего элемента. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Переходит к атрибуту с указанным именем. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Переходит к атрибуту с указанным локальным именем и URI пространства имен. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Переходит к атрибуту с указанным индексом. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Проверяет, является ли текущий узел содержимым (текст без пробелов, **CDATA**, **Element**, **EndElement**, **EntityReference** или **EndEntity**). Если узел не является узлом содержимого, читатель пропускает до следующего узла содержимого или до конца файла. Он пропускает узлы следующих типов: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** или **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Переходит к элементу, содержащему текущий узел атрибута. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Переходит к первому атрибуту. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Переходит к следующему атрибуту. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| **bool** [Read](./read/)() override | Читает следующий узел из потока. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Разбирает значение атрибута в один или несколько узлов **[Text](../../system.text/)**, **EntityReference** или **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Читает содержимое как объект указанного типа. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Читает содержимое и возвращает двоичные байты, декодированные из Base64. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Читает содержимое и возвращает двоичные байты, декодированные из BinHex. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Считывает текстовое содержимое в текущей позиции как [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Считывает текстовое содержимое в текущей позиции как объект [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Считывает текстовое содержимое в текущей позиции как объект [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Считывает текстовое содержимое в текущей позиции как объект [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Считывает текстовое содержимое в текущей позиции как число двойной точности с плавающей точкой. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Считывает текстовое содержимое в текущей позиции как число одинарной точности с плавающей точкой. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Считывает текстовое содержимое в текущей позиции как 32-битное знаковое целое. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Считывает текстовое содержимое в текущей позиции как 64-битное знаковое целое. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Считывает текстовое содержимое в текущей позиции как [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Считывает текстовое содержимое в текущей позиции как объект [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Считывает содержимое элемента как запрошенный тип. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадает ли указанные локальное имя и URI пространства имен с текущим элементом, затем считывает содержимое элемента как запрошенный тип. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Считывает элемент и декодирует содержимое Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Считывает элемент и декодирует содержимое BinHex. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Считывает текущий элемент и возвращает содержимое как объект [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадает ли указанные локальное имя и URI пространства имен с текущим элементом, затем считывает текущий элемент и возвращает содержимое как объект [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Считывает текущий элемент и возвращает содержимое как объект [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадает ли указанные локальное имя и URI пространства имен с текущим элементом, затем считывает текущий элемент и возвращает содержимое как объект [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Считывает текущий элемент и возвращает содержимое как объект [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадает ли указанные локальное имя и URI пространства имен с текущим элементом, затем считывает текущий элемент и возвращает содержимое как объект [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Считывает текущий элемент и возвращает содержимое как число двойной точности с плавающей точкой. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадает ли указанные локальное имя и URI пространства имен с текущим элементом, затем считывает текущий элемент и возвращает содержимое как число двойной точности с плавающей точкой. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Считывает текущий элемент и возвращает содержимое как число одинарной точности с плавающей точкой. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадает ли указанные локальное имя и URI пространства имен с текущим элементом, затем считывает текущий элемент и возвращает содержимое как число одинарной точности с плавающей точкой. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Считывает текущий элемент и возвращает содержимое как 32-битное знаковое целое. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадает ли указанные локальное имя и URI пространства имен с текущим элементом, затем считывает текущий элемент и возвращает содержимое как 32-битное знаковое целое. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Считывает текущий элемент и возвращает содержимое как 64-битное знаковое целое. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадает ли указанные локальное имя и URI пространства имен с текущим элементом, затем считывает текущий элемент и возвращает содержимое как 64-битное знаковое целое. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Считывает текущий элемент и возвращает содержимое как [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадает ли указанные локальное имя и URI пространства имен с текущим элементом, затем считывает текущий элемент и возвращает содержимое как [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Считывает текущий элемент и возвращает содержимое как объект [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадает ли указанные локальное имя и URI пространства имен с текущим элементом, затем считывает текущий элемент и возвращает содержимое как объект [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Считывает элемент, содержащий только текст. Однако рекомендуется использовать метод [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), так как он предоставляет более простой способ выполнения этой операции. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Проверяет, совпадает ли значение [XmlReader::get_Name](../xmlreader/get_name/) найденного элемента с заданной строкой перед чтением элемента, содержащего только текст. Однако рекомендуется использовать метод [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), так как он предоставляет более простой способ выполнения этой операции. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадают ли значения [XmlReader::get_LocalName](../xmlreader/get_localname/) и [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) найденного элемента с заданными строками перед чтением элемента, содержащего только текст. Однако рекомендуется использовать метод [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), так как он предоставляет более простой способ выполнения этой операции. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Проверяет, является ли текущий узел содержимого конечной меткой, и продвигает читатель к следующему узлу. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | При переопределении в производном классе считывает всё содержимое, включая разметку, как строку. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | При переопределении в производном классе считывает содержимое, включая разметку, представляющее этот узел и всех его детей. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Проверяет, является ли текущий узел элементом, и продвигает читатель к следующему узлу. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Проверяет, является ли текущий узел содержимого элементом с заданным значением [XmlReader::get_Name](../xmlreader/get_name/), и продвигает читатель к следующему узлу. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, является ли текущий узел содержимого элементом со значениями [XmlReader::get_LocalName](../xmlreader/get_localname/) и [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/), и продвигает читатель к следующему узлу. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Считывает содержимое элемента или текстового узла как строку. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Возвращает новый экземпляр [XmlReader](../xmlreader/), который может быть использован для чтения текущего узла и всех его потомков. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Продвигает [XmlReader](../xmlreader/) к следующему дочернему элементу с указанным квалифицированным именем. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Продвигает [XmlReader](../xmlreader/) к следующему дочернему элементу с указанным локальным именем и URI пространства имен. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Читает до тех пор, пока не будет найден элемент с указанным квалифицированным именем. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Читает до тех пор, пока не будет найден элемент с указанным локальным именем и URI пространства имен. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Продвигает [XmlReader](../xmlreader/) к следующему соседнему элементу с указанным квалифицированным именем. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Продвигает [XmlReader](../xmlreader/) к следующему соседнему элементу с указанным локальным именем и URI пространства имен. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Считывает большие потоки текста, встроенные в XML-документ. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типом значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик общих ссылок на указанное значение. |
| void [ResolveEntity](./resolveentity/)() override | Разрешает ссылку сущности для узлов **EntityReference**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счетчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счетчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счетчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [Skip](./skip/)() override | Пропускает дочерние узлы текущего узла. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
|  [XmlNodeReader](./xmlnodereader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | Создает экземпляр класса [XmlNodeReader](./) с использованием указанного [XmlNode](../xmlnode/). |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Типы

| Тип | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для разделяемого указателя на экземпляр этого класса. |

## Примечания

Объекты этого класса следует создавать только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. 

## Смотрите также

* Класс [XmlReader](../xmlreader/)
* Класс [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Пространство имён [System::Xml](../)
* Библиотека [Aspose.Slides](../../)