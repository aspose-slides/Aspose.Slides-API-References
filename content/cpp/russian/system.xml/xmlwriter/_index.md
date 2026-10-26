---
title: XmlWriter
second_title: Aspose.Slides для C++ справочник API
description: Представляет писатель, предоставляющий быстрый, некешированный, только вперёд способ генерации потоков или файлов, содержащих XML-данные.
type: docs
weight: 573
url: /ru/system.xml/xmlwriter/
---
## XmlWriter класс

Представляет писатель, предоставляющий быстрый, некешированный, только вперёд способ генерации потоков или файлов, содержащих XML-данные.

```cpp
class XmlWriter : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual void [Close](./close/)() | При переопределении в производном классе закрывает этот поток и базовый поток. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Создаёт новый экземпляр [XmlWriter](./) с использованием указанного имени файла. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Создаёт новый экземпляр [XmlWriter](./) с использованием имени файла и объекта [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Создаёт новый экземпляр [XmlWriter](./) с использованием указанного потока. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Создаёт новый экземпляр [XmlWriter](./) с использованием потока и объекта [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Создаёт новый экземпляр [XmlWriter](./) с использованием указанного TextWriter. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Создаёт новый экземпляр [XmlWriter](./) с использованием TextWriter и объектов [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Создаёт новый экземпляр [XmlWriter](./) с использованием указанного [Text::StringBuilder](../../system.text/stringbuilder/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Создаёт новый экземпляр [XmlWriter](./) с использованием объектов [Text::StringBuilder](../../system.text/stringbuilder/) и [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | Создаёт новый экземпляр [XmlWriter](./) с использованием указанного объекта [XmlWriter](./). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Создаёт новый экземпляр [XmlWriter](./) с использованием указанных объектов [XmlWriter](./) и [XmlWriterSettings](../xmlwritersettings/). |
| void [Dispose](./dispose/)() override | Освобождает все ресурсы, используемые текущим экземпляром класса [XmlWriter](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних нужд. |
| virtual void [Flush](./flush/)() | При переопределении в производном классе сбрасывает содержимое буфера в базовые потоки и также сбрасывает базовый поток. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | Возвращает объект [XmlWriterSettings](../xmlwritersettings/), используемый для создания этого экземпляра [XmlWriter](./). |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | При переопределении в производном классе получает состояние писателя. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | При переопределении в производном классе получает текущую область **xml:lang**. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | При переопределении в производном классе получает XmlSpace, представляющий текущую область **xml:space**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | При переопределении в производном классе возвращает ближайший префикс, определённый в текущей области пространства имён для URI пространства имён. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект значимого типа с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона в weak-указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик weak-ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик weak-ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | При переопределении в производном классе записывает все атрибуты, найденные в текущей позиции в [XmlReader](../xmlreader/). |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | При переопределении в производном классе записывает атрибут с указанным локальным именем, URI пространства имён и значением. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | При переопределении в производном классе записывает атрибут с указанным локальным именем и значением. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | При переопределении в производном классе записывает атрибут с указанным префиксом, локальным именем, URI пространства имён и значением. |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | При переопределении в производном классе кодирует указанные бинарные байты в Base64 и записывает полученный текст. |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | При переопределении в производном классе кодирует указанные бинарные байты в **BinHex** и записывает полученный текст. |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | При переопределении в производном классе записывает блок **...**, содержащий указанный текст. |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | При переопределении в производном классе принудительно генерирует символьную сущность для указанного значения Unicode-символа. |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | При переопределении в производном классе пишет текст буфер за буфером. |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | При переопределении в производном классе записывает комментарий ****, содержащий указанный текст. |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | При переопределении в производном классе записывает объявление DOCTYPE с указанным именем и необязательными атрибутами. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Записывает элемент с указанным локальным именем и значением. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Записывает элемент с указанным локальным именем, URI пространства имён и значением. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Записывает элемент с указанным префиксом, локальным именем, URI пространства имён и значением. |
| virtual void [WriteEndAttribute](./writeendattribute/)() | При переопределении в производном классе закрывает предыдущий вызов XmlWriter::WriteStartAttribute(String,String). |
| virtual void [WriteEndDocument](./writeenddocument/)() | При переопределении в производном классе закрывает любые открытые элементы или атрибуты и переводит писатель в состояние Start. |
| virtual void [WriteEndElement](./writeendelement/)() | При переопределении в производном классе закрывает один элемент и удаляет соответствующую область пространства имён. |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | При переопределении в производном классе записывает ссылку на сущность как **&name**;. |
| virtual void [WriteFullEndElement](./writefullendelement/)() | При переопределении в производном классе закрывает один элемент и удаляет соответствующую область пространства имён. |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | При переопределении в производном классе записывает указанное имя, гарантируя его валидность согласно рекомендациям W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | При переопределении в производном классе записывает указанное имя, гарантируя его валидность как NmToken согласно рекомендациям W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | При переопределении в производном классе копирует всё из reader в writer и перемещает reader к началу следующего sibling. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Копирует всё из объекта XPathNavigator в писатель. Позиция XPathNavigator остаётся неизменной. |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | При переопределении в производном классе записывает инструкцию обработки с пробелом между именем и текстом следующим образом: **<?name text?>**. |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | При переопределении в производном классе записывает имя с учётом пространства имён. Этот метод ищет префикс, находящийся в области для данного пространства имён. |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | При переопределении в производном классе вручную записывает необработанную разметку из буфера символов. |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | При переопределении в производном классе вручную записывает необработанную разметку из строки. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Записывает начало атрибута с указанным локальным именем и URI пространства имён. |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | При переопределении в производном классе записывает начало атрибута с указанным префиксом, локальным именем и URI пространства имён. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | Записывает начало атрибута с указанным локальным именем. |
| virtual void [WriteStartDocument](./writestartdocument/)() | При переопределении в производном классе записывает объявление XML с версией "1.0". |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | При переопределении в производном классе записывает объявление XML с версией "1.0" и атрибутом standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | При переопределении в производном классе записывает указанный начальный тег и связывает его с заданным пространством имён. |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | При переопределении в производном классе записывает указанный начальный тег и связывает его с заданным пространством имён и префиксом. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | Записывает начальный тег с указанным локальным именем. |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | Записывает заданный текстовый контент. |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | Генерирует и записывает сущность суррогатных символов для пары суррогатных символов. |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Записывает значение объекта. |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | Записывает значение [String](../../system/string/). |
| virtual void [WriteValue](./writevalue/)(**bool**) | Записывает значение [Boolean](../../system/boolean/). |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | Записывает значение [DateTime](../../system/datetime/). |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Записывает значение [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](./writevalue/)(**double**) | Записывает значение [Double](../../system/double/). |
| virtual void [WriteValue](./writevalue/)(**float**) | Записывает число с одинарной точностью (float). |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | Записывает значение [Decimal](../../system/decimal/). |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | Записывает значение [Int32](../../system/int32/). |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | Записывает значение [Int64](../../system/int64/). |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | При переопределении в производном классе записывает заданный пробельный символ. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Типы

| Тип | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |

## Смотрите также

* Класс [IDisposable](../../system/idisposable/)
* Пространство имён [System::Xml](../)
* Библиотека [Aspose.Slides](../../)