---
title: XmlSchemaGroupRef
second_title: Aspose.Slides для C++ справочник API
description: Представляет элемент group с атрибутом ref из XML Schema, как указано World Wide Web Consortium (W3C). Этот класс используется в сложных типах, которые ссылаются на группу, определённую на уровне схемы.
type: docs
weight: 456
url: /ru/system.xml.schema/xmlschemagroupref/
---
## XmlSchemaGroupRef класс

Представляет элемент **group** с атрибутом **ref** из XML [Schema](../), как указано Консорциумом World Wide [Web](../../system.web/) (W3C). Этот класс используется в сложных типах, которые ссылаются на **group**, определённый на уровне **schema**.

```cpp
class XmlSchemaGroupRef : public System::Xml::Schema::XmlSchemaParticle
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типа значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Возвращает свойство **annotation**. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Возвращает строковый идентификатор. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Возвращает номер строки в файле, к которому относится элемент **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Возвращает позицию строки в файле, к которому относится элемент **schema**. |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | Возвращает максимальное количество появлений частицы. |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | Возвращает число в виде строкового значения. Максимальное количество появлений частицы. |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | Возвращает минимальное количество появлений частицы. |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | Возвращает число в виде строкового значения. Минимальное количество появлений частицы. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Возвращает XmlSerializerNamespaces, используемые с этим объектом схемы. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Возвращает родительский объект для этого [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaGroupBase](../xmlschemagroupbase/)\> [get_Particle](./get_particle/)() | Возвращает один из классов [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) или [XmlSchemaSequence](../xmlschemasequence/), который содержит посткомпиляционную интерпретацию значения **Particle**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | Возвращает имя группы, определённой в этой схеме (или в другой схеме, указанной указанным пространством имён). |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Возвращает местоположение источника файла, загрузившего схему. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Возвращает квалифицированные атрибуты, которые не принадлежат целевому пространству имён текущей схемы. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типа значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Устанавливает свойство **annotation**. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Устанавливает строковый идентификатор. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Устанавливает номер строки в файле, к которому относится элемент **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Устанавливает позицию строки в файле, к которому относится элемент **schema**. |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | Устанавливает максимальное количество появлений частицы. |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | Устанавливает число в виде строкового значения. Максимальное количество появлений частицы. |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | Устанавливает минимальное количество появлений частицы. |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | Устанавливает число в виде строкового значения. Минимальное количество появлений частицы. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Устанавливает XmlSerializerNamespaces, используемые с этим объектом схемы. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Устанавливает родительский объект для этого [XmlSchemaObject](../xmlschemaobject/). |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Устанавливает имя группы, определённой в этой схеме (или в другой схеме, указанной указанным пространством имён). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Устанавливает местоположение источника файла, загрузившего схему. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Устанавливает квалифицированные атрибуты, которые не принадлежат целевому пространству имён текущей схемы. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-ый шаблонный аргумент как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
|  [XmlSchemaGroupRef](./xmlschemagroupref/)() | Инициализирует новый экземпляр класса [XmlSchemaGroupRef](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Инициализирует новый экземпляр класса [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | Инициализирует новый экземпляр класса [XmlSchemaParticle](../xmlschemaparticle/). |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Типы

| Тип | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |

## Примечания

Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. 

## См. также

* Класс [XmlSchemaParticle](../xmlschemaparticle/)
* Пространство имён [System::Xml::Schema](../)
* Библиотека [Aspose.Slides](../../)