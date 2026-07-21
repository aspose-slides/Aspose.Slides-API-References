---
title: XmlSchemaSimpleType
second_title: Aspose.Slides для C++ справка API
description: Представляет элемент simpleType для простого содержимого из XML Schema, как указано World Wide Web Consortium (W3C). Этот класс определяет простой тип. Простые типы могут задавать информацию и ограничения для значений атрибутов или элементов, содержащих только текст.
type: docs
weight: 833
url: /ru/system.xml.schema/xmlschemasimpletype/
---
## XmlSchemaSimpleType класс

Represents the **simpleType** element for simple content from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class defines a simple type. Simple types can specify information and constraints for the value of attributes or elements with text-only content.

```cpp
class XmlSchemaSimpleType : public System::Xml::Schema::XmlSchemaType
```

## Методы

| Мет

од | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типовых значений в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Возвращает свойство **annotation**. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](../xmlschematype/get_baseschematype/)() | Возвращает тип объекта после компиляции или встроенный тип данных XML [Schema](../) Definition Language (XSD), элемент simpleType или complexType. Это значение инфосета после компиляции схемы. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_BaseXmlSchemaType](../xmlschematype/get_basexmlschematype/)() | Возвращает значение после компиляции для базового типа этой схемы. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleTypeContent](../xmlschemasimpletypecontent/)\> [get_Content](./get_content/)() | Возвращает один из [XmlSchemaSimpleTypeUnion](../xmlschemasimpletypeunion/), [XmlSchemaSimpleTypeList](../xmlschemasimpletypelist/) или [XmlSchemaSimpleTypeRestriction](../xmlschemasimpletyperestriction/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](../xmlschematype/get_datatype/)() | Возвращает значение после компиляции для типа данных сложного типа. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](../xmlschematype/get_derivedby/)() | Возвращает информацию после компиляции о том, как этот элемент был получен из своего базового типа. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](../xmlschematype/get_final/)() | Возвращает окончательный атрибут вывода типа, указывающий, допускаются ли дальнейшие выводы. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](../xmlschematype/get_finalresolved/)() | Возвращает интерпретацию [XmlSchemaType::get_Final](../xmlschematype/get_final/) после компиляции. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Возвращает строковый идентификатор. |
| virtual **bool** [get_IsMixed](../xmlschematype/get_ismixed/)() | Возвращает значение, указывающее, имеет ли этот тип смешанную модель содержимого. Этот вызов допустим только для сложного типа. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Возвращает номер строки в файле, к которому относится элемент **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Возвращает позицию символа в строке в файле, к которому относится элемент **schema**. |
| [String](../../system/string/) [get_Name](../xmlschematype/get_name/)() | Возвращает имя типа. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Возвращает XmlSerializerNamespaces, используемые с этим объектом схемы. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Возвращает родительский объект для этого [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](../xmlschematype/get_qualifiedname/)() | Возвращает квалифицированное имя типа, построенное из атрибута **Name** этого типа. Это значение после компиляции схемы. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Возвращает расположение источника файла, который загрузил схему. |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](../xmlschematype/get_typecode/)() | Возвращает XmlTypeCode типа. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Возвращает квалифицированные атрибуты, которые не принадлежат целевому пространству имен текущей схемы. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | Возвращает [XmlSchemaComplexType](../xmlschemacomplextype/), представляющий встроенный сложный тип указанного сложного типа. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Возвращает [XmlSchemaComplexType](../xmlschemacomplextype/), представляющий встроенный сложный тип, указанный квалифицированным именем. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](./)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Возвращает [XmlSchemaSimpleType](./), представляющий встроенный простой тип, указанный квалифицированным именем. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](./)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | Возвращает [XmlSchemaSimpleType](./), представляющий встроенный простой тип указанного простого типа. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| static **bool** [IsDerivedFrom](../xmlschematype/isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Возвращает значение, указывающее, выводится ли указанный тип схемы из указанного базового типа схемы. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте непосредственно или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копирующее построение подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копирующее построение подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типового значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Устанавливает свойство **annotation**. |
| void [set_Content](./set_content/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleTypeContent](../xmlschemasimpletypecontent/)\>\&) | Устанавливает один из [XmlSchemaSimpleTypeUnion](../xmlschemasimpletypeunion/), [XmlSchemaSimpleTypeList](../xmlschemasimpletypelist/) или [XmlSchemaSimpleTypeRestriction](../xmlschemasimpletyperestriction/). |
| void [set_Final](../xmlschematype/set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Устанавливает окончательный атрибут вывода типа, указывающий, допускаются ли дальнейшие выводы. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Устанавливает строковый идентификатор. |
| virtual void [set_IsMixed](../xmlschematype/set_ismixed/)(**bool**) | Устанавливает значение, указывающее, имеет ли этот тип смешанную модель содержимого. Этот вызов допустим только для сложного типа. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Устанавливает номер строки в файле, к которому относится элемент **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Устанавливает позицию символа в строке в файле, к которому относится элемент **schema**. |
| void [set_Name](../xmlschematype/set_name/)(const [String](../../system/string/)\&) | Устанавливает имя типа. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Устанавливает XmlSerializerNamespaces, используемые с этим объектом схемы. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Устанавливает родительский объект для этого [XmlSchemaObject](../xmlschemaobject/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Устанавливает расположение источника файла, который загрузил схему. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Устанавливает квалифицированные атрибуты, которые не принадлежат целевому пространству имен текущей схемы. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент в виде слабого указателя (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте непосредственно или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Инициализирует новый экземпляр класса [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaSimpleType](./xmlschemasimpletype/)() | Инициализирует новый экземпляр класса [XmlSchemaSimpleType](./). |
|  [XmlSchemaType](../xmlschematype/xmlschematype/)() | Инициализирует новый экземпляр класса [XmlSchemaType](../xmlschematype/). |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Типedef

| Типedef | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним указателя shared pointer на экземпляр этого класса. |

## Примечания

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## См. также

* Класс [XmlSchemaType](../xmlschematype/)
* Пространство имён [System::Xml::Schema](../)
* Библиотека [Aspose.Slides](../../)