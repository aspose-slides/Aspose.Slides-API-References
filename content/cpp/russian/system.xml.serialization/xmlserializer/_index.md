---
title: XmlSerializer
second_title: Справочник API Aspose.Slides для C++
description: "Выполняет сериализацию и десериализацию объектов в XML-документы и из них. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи в функции в качестве аргумента."
type: docs
weight: 66
url: /ru/system.xml.serialization/xmlserializer/
---
## XmlSerializer класс

Выполняет сериализацию и десериализацию объектов в XML-документы и из них. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи в функции в качестве аргумента.

```cpp
class XmlSerializer : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [CanDeserialize](./candeserialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Проверяет, находится ли конкретный читатель в десериализуемом состоянии. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Deserialize](./deserialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | Десериализует XML-документ в объект. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Deserialize](./deserialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>) | Десериализует XML-документ в объект. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Deserialize](./deserialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Десериализует XML-документ в объект. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Deserialize](./deserialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>, [String](../../system/string/)) | Десериализует XML-документ в объект. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Возвращает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Возвращает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# `is`. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# `lock()`. Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения с `nullptr`. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и `nullptr`. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Сериализует документ в XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Сериализует документ в XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Сериализует документ в XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>) | Сериализует документ в XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>) | Сериализует документ в XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>) | Сериализует документ в XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>, [String](../../system/string/)) | Сериализует документ в XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>, [String](../../system/string/), [String](../../system/string/)) | Сериализует документ в XML. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Возвращает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Инкрементирует счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Декрементирует и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# `typeof([System.Object](../../system/object/))`. |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# `lock()`. Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Инкрементирует счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Декрементирует счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Поля

| Поле | Описание |
| --- | --- |
| static [EncodingNamespace](./encodingnamespace/) | Имя пространства имён кодировки. |
| static [WsdlNamespace](./wsdlnamespace/) | Имя пространства имён WSDL. |
| static [WsdlTypesNamespace](./wsdltypesnamespace/) | Имя пространства имён типов WSDL. |

## См. также

* Класс [Object](../../system/object/)
* Пространство имён [System::Xml::Serialization](../)
* Библиотека [Aspose.Slides](../../)