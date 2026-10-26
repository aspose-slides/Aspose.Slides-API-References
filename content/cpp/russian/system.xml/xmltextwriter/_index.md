---
title: XmlTextWriter
second_title: Справочник API Aspose.Slides для C++
description: Представляет писатель, который обеспечивает быстрый, некеширующий, только-вперёд способ генерации потоков или файлов, содержащих данные XML, соответствующие рекомендациям W3C Extensible Markup Language (XML) 1.0 и Namespaces in XML.
type: docs
weight: 521
url: /ru/system.xml/xmltextwriter/
---
## XmlTextWriter класс

Представляет писатель, который обеспечивает быстрый, некеширующий, только-вперёд способ генерации потоков или файлов, содержащих данные XML, соответствующие рекомендациям W3C Extensible Markup Language (XML) 1.0 и Namespaces in XML.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## Методы

| Метод | Описание |
| --- | --- |
| void [Close](./close/)() override | Закрывает этот поток и базовый поток. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | Создаёт новый экземпляр [XmlWriter](../xmlwriter/) с использованием указанного имени файла. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Создаёт новый экземпляр [XmlWriter](../xmlwriter/) с использованием имени файла и объекта [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Создаёт новый экземпляр [XmlWriter](../xmlwriter/) с использованием указанного потока. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Создаёт новый экземпляр [XmlWriter](../xmlwriter/) с использованием потока и объекта [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Создаёт новый экземпляр [XmlWriter](../xmlwriter/) с использованием указанного TextWriter. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Создаёт новый экземпляр [XmlWriter](../xmlwriter/) с использованием TextWriter и объектов [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Создаёт новый экземпляр [XmlWriter](../xmlwriter/) с использованием указанного [Text::StringBuilder](../../system.text/stringbuilder/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Создаёт новый экземпляр [XmlWriter](../xmlwriter/) с использованием объектов [Text::StringBuilder](../../system.text/stringbuilder/) и [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | Создаёт новый экземпляр [XmlWriter](../xmlwriter/) с использованием указанного объекта [XmlWriter](../xmlwriter/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Создаёт новый экземпляр [XmlWriter](../xmlwriter/) с использованием указанных объектов [XmlWriter](../xmlwriter/) и [XmlWriterSettings](../xmlwritersettings/). |
| void [Dispose](../xmlwriter/dispose/)() override | Освобождает все ресурсы, используемые текущим экземпляром класса [XmlWriter](../xmlwriter/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типа значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| void [Flush](./flush/)() override | Сбрасывает всё, что находится в буфере, в базовые потоки, а также сбрасывает базовый поток. |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | Возвращает объект базового потока. |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | Указывает, как форматируется вывод. |
| **int32_t** [get_Indentation](./get_indentation/)() | Возвращает количество IndentChars, записываемых для каждого уровня иерархии, когда [XmlTextWriter::set_Formatting](./set_formatting/) установлен в [Formatting::Indented](../formatting/). |
| char16_t [get_IndentChar](./get_indentchar/)() | Возвращает символ, используемый для отступов, когда [XmlTextWriter::set_Formatting](./set_formatting/) установлен в [Formatting::Indented](../formatting/). |
| **bool** [get_Namespaces](./get_namespaces/)() | Возвращает значение, указывающее, следует ли поддерживать пространства имён. |
| char16_t [get_QuoteChar](./get_quotechar/)() | Возвращает символ, используемый для заключения значений атрибутов в кавычки. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | Возвращает объект [XmlWriterSettings](../xmlwritersettings/), используемый для создания этого экземпляра [XmlWriter](../xmlwriter/). |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | Возвращает состояние писателя. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Возвращает текущую область действия **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Возвращает объект XmlSpace, представляющий текущую область действия **xml:space**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | Возвращает ближайший префикс, определённый в текущей области действия пространства имён для указанного URI пространства имён. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | Указывает, как форматируется вывод. |
| void [set_Indentation](./set_indentation/)(**int32_t**) | Устанавливает количество IndentChars, записываемых для каждого уровня иерархии, когда [XmlTextWriter::set_Formatting](./set_formatting/) установлен в [Formatting::Indented](../formatting/). |
| void [set_IndentChar](./set_indentchar/)(char16_t) | Устанавливает символ, используемый для отступов, когда [XmlTextWriter::set_Formatting](./set_formatting/) установлен в [Formatting::Indented](../formatting/). |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Устанавливает значение, указывающее, следует ли поддерживать пространства имён. |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | Устанавливает символ, используемый для заключения значений атрибутов в кавычки. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | При переопределении в производном классе записывает все атрибуты, найденные в текущей позиции в [XmlReader](../xmlreader/). |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | При переопределении в производном классе записывает атрибут с указанным локальным именем, URI пространства имён и значением. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | При переопределении в производном классе записывает атрибут с указанным локальным именем и значением. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | При переопределении в производном классе записывает атрибут с указанным префиксом, локальным именем, URI пространства имён и значением. |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Кодирует указанные бинарные байты в base64 и записывает полученный текст. |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Кодирует указанные бинарные байты в binhex и записывает полученный текст. |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | Записывает блок **...**, содержащий указанный текст. |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | Принудительно генерирует символьную сущность для указанного значения Unicode-символа. |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Записывает текст по одному буферу за раз. |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | Записывает комментарий ****, содержащий указанный текст. |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Записывает объявление DOCTYPE с указанным именем и необязательными атрибутами. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Записывает элемент с указанным локальным именем и значением. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Записывает элемент с указанным локальным именем, URI пространства имён и значением. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Записывает элемент с указанным префиксом, локальным именем, URI пространства имён и значением. |
| void [WriteEndAttribute](./writeendattribute/)() override | Закрывает предыдущий вызов [XmlTextWriter::WriteStartAttribute](./writestartattribute/). |
| void [WriteEndDocument](./writeenddocument/)() override | Закрывает любые открытые элементы или атрибуты и переводит писатель в состояние Start. |
| void [WriteEndElement](./writeendelement/)() override | Закрывает один элемент и снимает соответствующую область пространства имён. |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | Записывает ссылку на сущность в виде **&name**;. |
| void [WriteFullEndElement](./writefullendelement/)() override | Закрывает один элемент и снимает соответствующую область пространства имён. |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | Записывает указанное имя, гарантируя, что оно является валидным согласно [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | Записывает указанное имя, гарантируя, что оно является валидным **NmToken** согласно [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | При переопределении в производном классе копирует всё из читателя в писатель и перемещает читатель к началу следующего сестринского узла. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Копирует всё из объекта XPathNavigator в писатель. Позиция XPathNavigator остаётся неизменной. |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | Записывает инструкцию обработки с пробелом между именем и текстом следующим образом: **<?name text?>**. |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Записывает имя с пространством имён. Этот метод ищет префикс, находящийся в области действия для данного пространства имён. |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Записывает необработанную разметку вручную из буфера символов. |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | Записывает необработанную разметку вручную из строки. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Записывает начало атрибута. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Записывает начало атрибута с указанным локальным именем и URI пространства имён. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | Записывает начало атрибута с указанным локальным именем. |
| void [WriteStartDocument](./writestartdocument/)() override | Записывает объявление XML с версией "1.0". |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | Записывает объявление XML с версией "1.0" и атрибутом standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Записывает указанный начальный тег и связывает его с указанным пространством имён и префиксом. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | При переопределении в производном классе записывает указанный начальный тег и связывает его с указанным пространством имён. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | При переопределении в производном классе записывает начальный тег с указанным локальным именем. |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | Записывает данный текстовый контент. |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | Генерирует и записывает символьную сущность суррогатной пары. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Записывает значение объекта. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | Записывает значение [String](../../system/string/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | Записывает значение [Boolean](../../system/boolean/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | Записывает значение [DateTime](../../system/datetime/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Записывает значение [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | Записывает значение [Double](../../system/double/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | Записывает число одинарной точности с плавающей запятой. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | Записывает значение [Decimal](../../system/decimal/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | Записывает значение [Int32](../../system/int32/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | Записывает значение [Int64](../../system/int64/). |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | Записывает указанный пробел. |
| [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Создаёт экземпляр класса [XmlTextWriter](./) с использованием указанного потока и кодировки. |
| [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Создаёт экземпляр класса [XmlTextWriter](./) с использованием указанного файла. |
| [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Создаёт экземпляр класса [XmlTextWriter](./) с использованием указанного TextWriter. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Типы

| Тип | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для умного указателя на экземпляр этого класса. |

## Примечания

Рекомендуется использовать класс [XmlWriter](../xmlwriter/) вместо него. 

Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его функциям в качестве аргумента. 

## См. также

* Класс [XmlWriter](../xmlwriter/)
* Пространство имён [System::Xml](../)
* Библиотека [Aspose.Slides](../../)