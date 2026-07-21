---
title: XmlSchemaInference
second_title: Aspose.Slides для C++ справочник API
description: Выводит схему XML Schema Definition Language (XSD) из XML-документа. Класс XmlSchemaInference не может быть наследован.
type: docs
weight: 508
url: /ru/system.xml.schema/xmlschemainference/
---
## XmlSchemaInference класс

Infers an XML [Schema](../) Definition Language (XSD) schema from an XML document. The [XmlSchemaInference](./) class cannot be inherited.

```cpp
class XmlSchemaInference : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типовых (value) типов в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [XmlSchemaInference::InferenceOption](./inferenceoption/) [get_Occurrence](./get_occurrence/)() | Возвращает значение [XmlSchemaInference::InferenceOption](./inferenceoption/), которое влияет на объявления вхождений схемы, выводимые из XML-документа. |
| [XmlSchemaInference::InferenceOption](./inferenceoption/) [get_TypeInference](./get_typeinference/)() | Возвращает значение [XmlSchemaInference::InferenceOption](./inferenceoption/), которое влияет на вывод типов из XML-документа. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, ассоциированную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](../xmlschemaset/)\> [InferSchema](./inferschema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | Выводит схему XML [Schema](../) Definition Language (XSD) из XML-документа, содержащегося в указанном объекте [XmlReader](../../system.xml/xmlreader/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](../xmlschemaset/)\> [InferSchema](./inferschema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](../xmlschemaset/)\>) | Выводит схему XML [Schema](../) Definition Language (XSD) из XML-документа, содержащегося в указанном объекте [XmlReader](../../system.xml/xmlreader/), и уточняет полученную схему, используя существующую схему в указанном объекте [XmlSchemaSet](../xmlschemaset/) с тем же целевым пространством имен. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, а просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, а просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типового (value) типа с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает общий счётчик ссылок на указанное значение. |
| void [set_Occurrence](./set_occurrence/)([XmlSchemaInference::InferenceOption](./inferenceoption/)) | Устанавливает значение [XmlSchemaInference::InferenceOption](./inferenceoption/), которое влияет на объявления вхождений схемы, выводимые из XML-документа. |
| void [set_TypeInference](./set_typeinference/)([XmlSchemaInference::InferenceOption](./inferenceoption/)) | Устанавливает значение [XmlSchemaInference::InferenceOption](./inferenceoption/), которое влияет на вывод типов из XML-документа. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение общего счётчика ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает общий счётчик ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает общий счётчик ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
|  [XmlSchemaInference](./xmlschemainference/)() | Инициализирует новый экземпляр класса [XmlSchemaInference](./). |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Перечисления

| Перечисление | Описание |
| --- | --- |
| [InferenceOption](./inferenceoption/) | Влияет на информацию о вхождениях и типах, выводимую классом [XmlSchemaInference](./) для элементов и атрибутов в XML-документе. |

## Типы

| Тип | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared-указателя на экземпляр этого класса. |

## Замечания

Экземпляры этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям проверок. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. 

## См. также

* Класс [Object](../../system/object/)
* Пространство имен [System::Xml::Schema](../)
* Библиотека [Aspose.Slides](../../)