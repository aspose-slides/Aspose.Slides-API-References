---
title: XmlReader
second_title: Aspose.Slides для C++ API Reference
description: Представляет читатель, обеспечивающий быстрый, некешируемый, последовательный доступ к XML-данным.
type: docs
weight: 430
url: /ru/system.xml/xmlreader/
---
## XmlReader класс

Represents a reader that provides fast, noncached, forward-only access to XML data.

```cpp
class XmlReader : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual void [Close](./close/)() | При переопределении в производном классе изменяет [XmlReader::get_ReadState](./get_readstate/) на [ReadState::Closed](../readstate/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Создает новый экземпляр [XmlReader](./) с указанным URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Создает новый экземпляр [XmlReader](./), используя указанный URI и настройки. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Создает новый экземпляр [XmlReader](./), используя указанный URI, настройки и контекстную информацию для разбора. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Создает новый экземпляр [XmlReader](./), используя указанный поток с настройками по умолчанию. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Создает новый экземпляр [XmlReader](./) с указанным потоком и настройками. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Создает новый экземпляр [XmlReader](./), используя указанный поток, базовый URI и настройки. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Создает новый экземпляр [XmlReader](./), используя указанный поток, настройки и контекстную информацию для разбора. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Создает новый экземпляр [XmlReader](./), используя указанный текстовый читатель. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Создает новый экземпляр [XmlReader](./), используя указанный текстовый читатель и настройки. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Создает новый экземпляр [XmlReader](./), используя указанный текстовый читатель, настройки и базовый URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Создает новый экземпляр [XmlReader](./), используя указанный текстовый читатель, настройки и контекстную информацию для разбора. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Создает новый экземпляр [XmlReader](./), используя указанный XML-читатель и настройки. |
| void [Dispose](./dispose/)() override | Освобождает все ресурсы, используемые текущим экземпляром класса [XmlReader](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual **int32_t** [get_AttributeCount](./get_attributecount/)() | При переопределении в производном классе возвращает количество атрибутов в текущем узле. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | При переопределении в производном классе возвращает базовый URI текущего узла. |
| virtual **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() | Возвращает значение, указывающее, реализует ли [XmlReader](./) методы чтения двоичного содержимого. |
| virtual **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() | Возвращает значение, указывающее, реализует ли [XmlReader](./) метод [XmlReader::ReadValueChunk](./readvaluechunk/). |
| virtual **bool** [get_CanResolveEntity](./get_canresolveentity/)() | Возвращает значение, указывающее, может ли данный читатель разбирать и разрешать сущности. |
| virtual **int32_t** [get_Depth](./get_depth/)() | При переопределении в производном классе возвращает глубину текущего узла в XML-документе. |
| virtual **bool** [get_EOF](./get_eof/)() | При переопределении в производном классе возвращает значение, указывающее, находится ли читатель в конце потока. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Возвращает значение, указывающее, имеет ли текущий узел какие-либо атрибуты. |
| virtual **bool** [get_HasValue](./get_hasvalue/)() | При переопределении в производном классе возвращает значение, указывающее, может ли текущий узел иметь значение [XmlReader::get_Value](./get_value/). |
| virtual **bool** [get_IsDefault](./get_isdefault/)() | При переопределении в производном классе возвращает значение, указывающее, является ли текущий узел атрибутом, сгенерированным из значения по умолчанию, определённого в DTD или схеме. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | При переопределении в производном классе возвращает значение, указывающее, является ли текущий узел пустым элементом (например, **<MyElement/>**). |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | При переопределении в производном классе возвращает локальное имя текущего узла. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | При переопределении в производном классе возвращает квалифицированное имя текущего узла. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | При переопределении в производном классе возвращает URI пространства имён (как определено в спецификации W3C Namespace) узла, на котором находится читатель. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | При переопределении в производном классе возвращает [XmlNameTable](../xmlnametable/), связанный с этой реализацией. |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() | При переопределении в производном классе возвращает тип текущего узла. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | При переопределении в производном классе возвращает префикс пространства имён, связанный с текущим узлом. |
| virtual char16_t [get_QuoteChar](./get_quotechar/)() | При переопределении в производном классе возвращает символ кавычки, используемый для ограничения значения узла-атрибута. |
| virtual [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() | При переопределении в производном классе возвращает состояние читателя. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Возвращает информацию схемы, присвоенную текущему узлу в результате валидации схемы. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](./get_settings/)() | Возвращает объект [XmlReaderSettings](../xmlreadersettings/), используемый для создания этого экземпляра [XmlReader](./). |
| virtual [String](../../system/string/) [get_Value](./get_value/)() | При переопределении в производном классе возвращает текстовое значение текущего узла. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() | Возвращает тип текущего узла. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | При переопределении в производном классе возвращает текущую область **xml:lang**. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | При переопределении в производном классе возвращает текущую область **xml:space**. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | При переопределении в производном классе возвращает значение атрибута с указанным значением [XmlReader::get_Name](./get_name/). |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | При переопределении в производном классе возвращает значение атрибута с указанными значениями [XmlReader::get_LocalName](./get_localname/) и [XmlReader::get_NamespaceURI](./get_namespaceuri/). |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) | При переопределении в производном классе возвращает значение атрибута с указанным индексом. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [String](../../system/string/) [idx_get](./idx_get/)(**int32_t**) | При переопределении в производном классе возвращает значение атрибута с указанным индексом. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | При переопределении в производном классе возвращает значение атрибута с указанным значением [XmlReader::get_Name](./get_name/). |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/), [String](../../system/string/)) | При переопределении в производном классе возвращает значение атрибута с указанными значениями [XmlReader::get_LocalName](./get_localname/) и [XmlReader::get_NamespaceURI](./get_namespaceuri/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| static **bool** [IsName](./isname/)(const [String](../../system/string/)\&) | Возвращает значение, указывающее, является ли строковый аргумент допустимым XML-именем. |
| static **bool** [IsNameToken](./isnametoken/)(const [String](../../system/string/)\&) | Возвращает значение, указывающее, является ли строковый аргумент допустимым токеном XML-имени. |
| virtual **bool** [IsStartElement](./isstartelement/)() | Вызывает [XmlReader::MoveToContent](./movetocontent/) и проверяет, является ли текущий контентный узел стартовым тегом или пустым элементом. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/)) | Вызывает [XmlReader::MoveToContent](./movetocontent/) и проверяет, является ли текущий контентный узел стартовым тегом или пустым элементом, а также совпадает ли значение [XmlReader::get_Name](./get_name/) найденного элемента с переданным аргументом. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Вызывает [XmlReader::MoveToContent](./movetocontent/) и проверяет, является ли текущий контентный узел стартовым тегом или пустым элементом, а также совпадают ли значения [XmlReader::get_LocalName](./get_localname/) и [XmlReader::get_NamespaceURI](./get_namespaceuri/) найденного элемента с данными строками. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) | При переопределении в производном классе разрешает префикс пространства имён в области текущего элемента. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) | При переопределении в производном классе переходит к атрибуту с указанным значением [XmlReader::get_Name](./get_name/). |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | При переопределении в производном классе переходит к атрибуту с указанными значениями [XmlReader::get_LocalName](./get_localname/) и [XmlReader::get_NamespaceURI](./get_namespaceuri/). |
| virtual void [MoveToAttribute](./movetoattribute/)(**int32_t**) | При переопределении в производном классе переходит к атрибуту с указанным индексом. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](./movetocontent/)() | Проверяет, является ли текущий узел контентным (не пробельным текстом, **CDATA**, **Element**, **EndElement**, **EntityReference** или **EndEntity**). Если узел не является контентным, читатель пропускает его до следующего контентного узла или конца файла. Он пропускает узлы следующих типов: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** или **SignificantWhitespace**. |
| virtual **bool** [MoveToElement](./movetoelement/)() | При переопределении в производном классе переходит к элементу, содержащему текущий узел атрибута. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | При переопределении в производном классе переходит к первому атрибуту. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | При переопределении в производном классе переходит к следующему атрибуту. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| virtual **bool** [Read](./read/)() | При переопределении в производном классе читает следующий узел из потока. |
| virtual **bool** [ReadAttributeValue](./readattributevalue/)() | При переопределении в производном классе разбирает значение атрибута в один или несколько узлов **[Text](../../system.text/)**, **EntityReference** или **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](./readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Читает содержимое как объект указанного типа. |
| virtual **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Читает содержимое и возвращает двоичные байты, расшифрованные из Base64. |
| virtual **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Читает содержимое и возвращает двоичные байты, расшифрованные из **BinHex**. |
| virtual **bool** [ReadContentAsBoolean](./readcontentasboolean/)() | Считывает текстовое содержимое в текущей позиции как [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](./readcontentasdatetime/)() | Считывает текстовое содержимое в текущей позиции как объект [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](./readcontentasdatetimeoffset/)() | Считывает текстовое содержимое в текущей позиции как объект [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](./readcontentasdecimal/)() | Считывает текстовое содержимое в текущей позиции как объект [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](./readcontentasdouble/)() | Считывает текстовое содержимое в текущей позиции как число двойной точности. |
| virtual **float** [ReadContentAsFloat](./readcontentasfloat/)() | Считывает текстовое содержимое в текущей позиции как число одинарной точности. |
| virtual **int32_t** [ReadContentAsInt](./readcontentasint/)() | Считывает текстовое содержимое в текущей позиции как 32-разрядное знаковое целое. |
| virtual **int64_t** [ReadContentAsLong](./readcontentaslong/)() | Считывает текстовое содержимое в текущей позиции как 64-разрядное знаковое целое. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](./readcontentasobject/)() | Считывает текстовое содержимое в текущей позиции как [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](./readcontentasstring/)() | Считывает текстовое содержимое в текущей позиции как объект [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Считывает содержимое элемента как запрошенный тип. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадают ли указанные локальное имя и URI пространства имён с текущим элементом, затем считывает содержимое элемента как запрошенный тип. |
| virtual **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Считывает элемент и декодирует содержимое **Base64**. |
| virtual **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Считывает элемент и декодирует содержимое **BinHex**. |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)() | Считывает текущий элемент и возвращает содержимое как объект [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадают ли указанные локальное имя и URI пространства имён с текущим элементом, затем считывает текущий элемент и возвращает содержимое как объект [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)() | Считывает текущий элемент и возвращает содержимое как объект [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадают ли указанные локальное имя и URI пространства имён с текущим элементом, затем считывает текущий элемент и возвращает содержимое как объект [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)() | Считывает текущий элемент и возвращает содержимое как объект [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадают ли указанные локальное имя и URI пространства имён с текущим элементом, затем считывает текущий элемент и возвращает содержимое как объект [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)() | Считывает текущий элемент и возвращает содержимое как число двойной точности. |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадают ли указанные локальное имя и URI пространства имён с текущим элементом, затем считывает текущий элемент и возвращает содержимое как число двойной точности. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)() | Считывает текущий элемент и возвращает содержимое как число одинарной точности. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадают ли указанные локальное имя и URI пространства имён с текущим элементом, затем считывает текущий элемент и возвращает содержимое как число одинарной точности. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)() | Считывает текущий элемент и возвращает содержимое как 32-разрядное знаковое целое. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадают ли указанные локальное имя и URI пространства имён с текущим элементом, затем считывает текущий элемент и возвращает содержимое как 32-разрядное знаковое целое. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)() | Считывает текущий элемент и возвращает содержимое как 64-разрядное знаковое целое. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадают ли указанные локальное имя и URI пространства имён с текущим элементом, затем считывает текущий элемент и возвращает содержимое как 64-разрядное знаковое целое. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)() | Считывает текущий элемент и возвращает содержимое как [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадают ли указанные локальное имя и URI пространства имён с текущим элементом, затем считывает текущий элемент и возвращает содержимое как [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)() | Считывает текущий элемент и возвращает содержимое как объект [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадают ли указанные локальное имя и URI пространства имён с текущим элементом, затем считывает текущий элемент и возвращает содержимое как объект [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)() | Считывает элемент, содержащий только текст. Однако рекомендуется использовать метод [XmlReader::ReadElementContentAsString](./readelementcontentasstring/), поскольку он обеспечивает более простой способ выполнения этой операции. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/)) | Проверяет, совпадает ли значение [XmlReader::get_Name](./get_name/) найденного элемента с заданной строкой перед считыванием элемента, содержащего только текст. Однако рекомендуется использовать метод [XmlReader::ReadElementContentAsString](./readelementcontentasstring/), поскольку он обеспечивает более простой способ выполнения этой операции. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, совпадают ли значения [XmlReader::get_LocalName](./get_localname/) и [XmlReader::get_NamespaceURI](./get_namespaceuri/) найденного элемента с заданными строками перед считыванием элемента, содержащего только текст. Однако рекомендуется использовать метод [XmlReader::ReadElementContentAsString](./readelementcontentasstring/), поскольку он обеспечивает более простой способ выполнения этой операции. |
| virtual void [ReadEndElement](./readendelement/)() | Проверяет, что текущий контентный узел является закрывающим тегом, и продвигает читатель к следующему узлу. |
| virtual [String](../../system/string/) [ReadInnerXml](./readinnerxml/)() | При переопределении в производном классе считывает всё содержимое, включая разметку, как строку. |
| virtual [String](../../system/string/) [ReadOuterXml](./readouterxml/)() | При переопределении в производном классе считывает содержимое, включая разметку, представляющее этот узел и всех его детей. |
| virtual void [ReadStartElement](./readstartelement/)() | Проверяет, что текущий узел является элементом, и продвигает читатель к следующему узлу. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/)) | Проверяет, что текущий контентный узел является элементом с заданным значением [XmlReader::get_Name](./get_name/), и продвигает читатель к следующему узлу. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Проверяет, что текущий контентный узел является элементом с заданными значениями [XmlReader::get_LocalName](./get_localname/) и [XmlReader::get_NamespaceURI](./get_namespaceuri/), и продвигает читатель к следующему узлу. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | При переопределении в производном классе считывает содержимое элемента или текстового узла как строку. Однако рекомендуется использовать метод [XmlReader::ReadElementContentAsString](./readelementcontentasstring/), поскольку он обеспечивает более простой способ выполнения этой операции. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [ReadSubtree](./readsubtree/)() | Возвращает новый экземпляр [XmlReader](./), который можно использовать для чтения текущего узла и всех его потомков. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/)) | Перемещает [XmlReader](./) к следующему потомковому элементу с указанным квалифицированным именем. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Перемещает [XmlReader](./) к следующему потомковому элементу с указанным локальным именем и URI пространства имён. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/)) | Читает до тех пор, пока не найден элемент с указанным квалифицированным именем. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Читает до тех пор, пока не найден элемент с указанным локальным именем и URI пространства имён. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/)) | Перемещает [XmlReader](./) к следующему соседнему элементу с указанным квалифицированным именем. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Перемещает [XmlReader](./) к следующему соседнему элементу с указанным локальным именем и URI пространства имён. |
| virtual **int32_t** [ReadValueChunk](./readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Считывает большие потоки текста, встроенного в XML-документ. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| virtual void [ResolveEntity](./resolveentity/)() | При переопределении в производном классе разрешает ссылку сущности для узлов **EntityReference**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual void [Skip](./skip/)() | Пропускает дочерние узлы текущего узла. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Типы

| Тип | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для умного указателя на экземпляр этого класса. |

## См. также

* Класс [IDisposable](../../system/idisposable/)
* Пространство имён [System::Xml](../)
* Библиотека [Aspose.Slides](../../)