---
title: XmlSchemaInfo
second_title: Справочник API Aspose.Slides для C++
description: Представляет пост-схемный набор информации проверенного XML-узла.
type: docs
weight: 521
url: /ru/system.xml.schema/xmlschemainfo/
---
## XmlSchemaInfo класс

Представляет пост-схемный набор информации проверенного XML-узла.

```cpp
class XmlSchemaInfo : public System::Xml::Schema::IXmlSchemaInfo
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типовых значений в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [XmlSchemaContentType](../xmlschemacontenttype/) [get_ContentType](./get_contenttype/)() | Возвращает объект XmlSchemaContentType, соответствующий типу содержимого этого проверенного XML-узла. |
| **bool** [get_IsDefault](./get_isdefault/)() override | Возвращает значение, указывающее, был ли этот проверенный XML-узел установлен как результат применения значения по умолчанию во время проверки схемы XML [Schema](../) Definition Language (XSD). |
| **bool** [get_IsNil](./get_isnil/)() override | Возвращает значение, указывающее, является ли значение этого проверенного XML-узла **nil**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [get_MemberType](./get_membertype/)() override | Возвращает динамический тип схемы для этого проверенного XML-узла. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAttribute](../xmlschemaattribute/)\> [get_SchemaAttribute](./get_schemaattribute/)() override | Возвращает скомпилированный объект [XmlSchemaAttribute](../xmlschemaattribute/), соответствующий этому проверенному XML-узлу. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaElement](../xmlschemaelement/)\> [get_SchemaElement](./get_schemaelement/)() override | Возвращает скомпилированный объект [XmlSchemaElement](../xmlschemaelement/), соответствующий этому проверенному XML-узлу. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_SchemaType](./get_schematype/)() override | Возвращает статический тип схемы XML [Schema](../) Definition Language (XSD) для этого проверенного XML-узла. |
| [XmlSchemaValidity](../xmlschemavalidity/) [get_Validity](./get_validity/)() override | Возвращает значение XmlSchemaValidity этого проверенного XML-узла. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типового значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_ContentType](./set_contenttype/)([XmlSchemaContentType](../xmlschemacontenttype/)) | Устанавливает объект XmlSchemaContentType, соответствующий типу содержимого этого проверенного XML-узла. |
| void [set_IsDefault](./set_isdefault/)(**bool**) | Устанавливает значение, указывающее, был ли этот проверенный XML-узел установлен как результат применения значения по умолчанию во время проверки схемы XML [Schema](../) Definition Language (XSD). |
| void [set_IsNil](./set_isnil/)(**bool**) | Устанавливает значение, указывающее, является ли значение этого проверенного XML-узла **nil**. |
| void [set_MemberType](./set_membertype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\>\&) | Устанавливает динамический тип схемы для этого проверенного XML-узла. |
| void [set_SchemaAttribute](./set_schemaattribute/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAttribute](../xmlschemaattribute/)\>\&) | Устанавливает скомпилированный объект [XmlSchemaAttribute](../xmlschemaattribute/), соответствующий этому проверенному XML-узлу. |
| void [set_SchemaElement](./set_schemaelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaElement](../xmlschemaelement/)\>\&) | Устанавливает скомпилированный объект [XmlSchemaElement](../xmlschemaelement/), соответствующий этому проверенному XML-узлу. |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&) | Устанавливает статический тип схемы XML [Schema](../) Definition Language (XSD) для этого проверенного XML-узла. |
| void [set_Validity](./set_validity/)([XmlSchemaValidity](../xmlschemavalidity/)) | Устанавливает значение XmlSchemaValidity этого проверенного XML-узла. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
|  [XmlSchemaInfo](./xmlschemainfo/)() | Инициализирует новый экземпляр класса [XmlSchemaInfo](./). |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Typedefs

| Typedef | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |

## Примечания

Экземпляры этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте объекты этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. 

## См. также

* Класс [IXmlSchemaInfo](../ixmlschemainfo/)
* Пространство имён [System::Xml::Schema](../)
* Библиотека [Aspose.Slides](../../)