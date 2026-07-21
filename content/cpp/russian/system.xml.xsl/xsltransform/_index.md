---
title: XslTransform
second_title: Справка API Aspose.Slides для C++
description: Преобразует XML-данные, используя таблицу стилей Extensible Stylesheet Language for Transformations (XSLT).
type: docs
weight: 105
url: /ru/system.xml.xsl/xsltransform/
---
## XslTransform класс

Transforms XML data using an Extensible Stylesheet Language for Transformations (XSLT) style sheet.

```cpp
class XslTransform : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типового значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | Загружает таблицу стилей XSLT, содержащуюся в [XmlReader](../../system.xml/xmlreader/). |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Загружает таблицу стилей XSLT, содержащуюся в [XmlReader](../../system.xml/xmlreader/). |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&) | Загружает таблицу стилей XSLT, содержащуюся в IXPathNavigable. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Загружает таблицу стилей XSLT, содержащуюся в IXPathNavigable. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>\&) | Загружает таблицу стилей XSLT, содержащуюся в XPathNavigator. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Загружает таблицу стилей XSLT, содержащуюся в XPathNavigator. |
| void [Load](./load/)(const [String](../../system/string/)\&) | Загружает таблицу стилей XSLT, указанную URL. |
| void [Load](./load/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Загружает таблицу стилей XSLT, указанную URL. |
| void [Lock](../../system/object/lock/)() | Реализует поведение оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типового значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Устанавливает [XmlResolver](../../system.xml/xmlresolver/) используемый для разрешения внешних ресурсов, когда вызывается метод [XslTransform::Transform](./transform/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Преобразует XML-данные в XPathNavigator, используя указанные **args**, и выводит результат в [XmlReader](../../system.xml/xmlreader/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&) | Преобразует XML-данные в XPathNavigator, используя указанные **args**, и выводит результат в [XmlReader](../../system.xml/xmlreader/). |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Преобразует XML-данные в XPathNavigator, используя указанные args, и выводит результат в [XmlWriter](../../system.xml/xmlwriter/). |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | Преобразует XML-данные в XPathNavigator, используя указанные args, и выводит результат в [XmlWriter](../../system.xml/xmlwriter/). |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Преобразует XML-данные в XPathNavigator, используя указанные **args**, и выводит результат в Stream. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Преобразует XML-данные в XPathNavigator, используя указанные **args**, и выводит результат в Stream. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Преобразует XML-данные в XPathNavigator, используя указанные **args**, и выводит результат в TextWriter. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Преобразует XML-данные в XPathNavigator, используя указанные **args**, и выводит результат в TextWriter. |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Преобразует XML-данные в IXPathNavigable, используя указанные **args**, и выводит результат в [XmlReader](../../system.xml/xmlreader/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&) | Преобразует XML-данные в IXPathNavigable, используя указанные **args**, и выводит результат в [XmlReader](../../system.xml/xmlreader/). |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Преобразует XML-данные в IXPathNavigable, используя указанные **args**, и выводит результат в TextWriter. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Преобразует XML-данные в IXPathNavigable, используя указанные **args**, и выводит результат в TextWriter. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Преобразует XML-данные в IXPathNavigable, используя указанные **args**, и выводит результат в Stream. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Преобразует XML-данные в IXPathNavigable, используя указанные **args**, и выводит результат в Stream. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Преобразует XML-данные в IXPathNavigable, используя указанные **args**, и выводит результат в [XmlWriter](../../system.xml/xmlwriter/). |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | Преобразует XML-данные в IXPathNavigable, используя указанные **args**, и выводит результат в [XmlWriter](../../system.xml/xmlwriter/). |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Преобразует XML-данные из входного файла и выводит результат в выходной файл. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Преобразует XML-данные из входного файла и выводит результат в выходной файл. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
|  [XslTransform](./xsltransform/)() | Инициализирует новый экземпляр класса [XslTransform](./). |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Typedefs

| Typedef | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared-pointer к экземпляру этого класса. |

## Примечания

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## См. также

* Класс [Object](../../system/object/)
* Пространство имён [System::Xml::Xsl](../)
* Library [Aspose.Slides](../../)