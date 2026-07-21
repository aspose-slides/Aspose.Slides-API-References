---
title: XmlSchemaElement
second_title: Справочник API Aspose.Slides для C++
description: Представляет элемент из XML Schema, как указано World Wide Web Consortium (W3C). Этот класс является базовым классом для всех типов частиц и используется для описания элемента в XML-документе.
type: docs
weight: 365
url: /ru/system.xml.schema/xmlschemaelement/
---
## XmlSchemaElement класс

Представляет **элемент** из XML [Schema](../), как указано консорциумом World Wide [Web](../../system.web/) (W3C). Этот класс является базовым классом для всех типов частиц и используется для описания элемента в документе XML.

```cpp
class XmlSchemaElement : public System::Xml::Schema::XmlSchemaParticle
```
## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типового значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Возвращает свойство **annotation**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | Возвращает производный **Block**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | Возвращает посткомпиляционную интерпретацию значения **Block**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Constraints](./get_constraints/)() | Возвращает коллекцию ограничений для элемента. |
| [String](../../system/string/) [get_DefaultValue](./get_defaultvalue/)() | Возвращает значение по умолчанию элемента, если его содержимое — простой тип или содержимое элемента — **textOnly**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_ElementSchemaType](./get_elementschematype/)() | Возвращает объект [XmlSchemaType](../xmlschematype/), представляющий тип элемента на основе значений [XmlSchemaElement::get_SchemaType](./get_schematype/) или [XmlSchemaElement::get_SchemaTypeName](./get_schematypename/). |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ElementType](./get_elementtype/)() | Возвращает объект на основе [XmlSchemaElement](./) или [XmlSchemaElement](./) элемента, содержащий посткомпиляционную интерпретацию значения **ElementType**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | Возвращает значение **Final**, указывающее, что дальнейшие производные недопустимы. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | Возвращает посткомпиляционную интерпретацию значения **Final**. |
| [String](../../system/string/) [get_FixedValue](./get_fixedvalue/)() | Возвращает фиксированное значение. |
| [XmlSchemaForm](../xmlschemaform/) [get_Form](./get_form/)() | Возвращает форму элемента. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Возвращает строковый идентификатор. |
| **bool** [get_IsAbstract](./get_isabstract/)() | Возвращает информацию, указывающую, может ли элемент использоваться в экземпляре документа. |
| **bool** [get_IsNillable](./get_isnillable/)() | Возвращает информацию, указывающую, может ли **xsi:nil** встречаться в данных экземпляра. Указывает, можно ли явно присвоить элементу значение nil. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Возвращает номер строки в файле, к которому относится элемент **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Возвращает позицию в строке файла, к которому относится элемент **schema**. |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | Возвращает максимальное количество повторений частицы. |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | Возвращает число в виде строкового значения. Максимальное количество повторений частицы. |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | Возвращает минимальное количество повторений частицы. |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | Возвращает число в виде строкового значения. Минимальное количество повторений частицы. |
| [String](../../system/string/) [get_Name](./get_name/)() | Возвращает имя элемента. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Возвращает XmlSerializerNamespaces, которые следует использовать с этим объектом схемы. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Возвращает родителя данного [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | Возвращает фактическое квалифицированное имя для данного элемента. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | Возвращает ссылочное имя элемента, объявленного в этой схеме (или в другой схеме, указанной указанным пространством имен). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_SchemaType](./get_schematype/)() | Возвращает тип элемента. Это может быть сложный тип или простой тип. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SchemaTypeName](./get_schematypename/)() | Возвращает имя встроенного типа данных, определенного в этой схеме или в другой схеме, указанной указанным пространством имен. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Возвращает исходное расположение файла, загрузившего схему. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SubstitutionGroup](./get_substitutiongroup/)() | Возвращает имя элемента, который заменяется этим элементом. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Возвращает квалифицированные атрибуты, не принадлежащие целевому пространству имен текущей схемы. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает ссылкой объект типового значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик общих ссылок на указанное значение. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Устанавливает свойство **annotation**. |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Устанавливает производный **Block**. |
| void [set_DefaultValue](./set_defaultvalue/)(const [String](../../system/string/)\&) | Устанавливает значение по умолчанию элемента, если его содержимое — простой тип или содержимое элемента — **textOnly**. |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Устанавливает значение **Final**, указывая, что дальнейшие производные недопустимы. |
| void [set_FixedValue](./set_fixedvalue/)(const [String](../../system/string/)\&) | Устанавливает фиксированное значение. |
| void [set_Form](./set_form/)([XmlSchemaForm](../xmlschemaform/)) | Устанавливает форму элемента. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Устанавливает строковый идентификатор. |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | Устанавливает информацию, указывающую, может ли элемент использоваться в экземпляре документа. |
| void [set_IsNillable](./set_isnillable/)(**bool**) | Устанавливает информацию, указывающую, может ли **xsi:nil** встречаться в данных экземпляра. Указывает, может ли элементу явно присвоить значение nil. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Устанавливает номер строки в файле, к которому относится элемент **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Устанавливает позицию в строке файла, к которому относится элемент **schema**. |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | Устанавливает максимальное количество повторений частицы. |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | Устанавливает число в виде строкового значения. Максимальное количество повторений частицы. |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | Устанавливает минимальное количество повторений частицы. |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | Устанавливает число в виде строкового значения. Минимальное количество повторений частицы. |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | Устанавливает имя элемента. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Устанавливает XmlSerializerNamespaces, которые следует использовать с этим объектом схемы. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Устанавливает родителя данного [XmlSchemaObject](../xmlschemaobject/). |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Устанавливает ссылочное имя элемента, объявленного в этой схеме (или в другой схеме, указанной указанным пространством имен). |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&) | Устанавливает тип элемента. Это может быть сложный тип или простой тип. |
| void [set_SchemaTypeName](./set_schematypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Устанавливает имя встроенного типа данных, определенного в этой схеме или в другой схеме, указанной указанным пространством имен. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Устанавливает исходное расположение файла, загрузившего схему. |
| void [set_SubstitutionGroup](./set_substitutiongroup/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Устанавливает имя элемента, который заменяется этим элементом. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Устанавливает квалифицированные атрибуты, не принадлежащие целевому пространству имен текущей схемы. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-ый аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счетчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счетчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счетчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
|  [XmlSchemaElement](./xmlschemaelement/)() | Инициализирует новый экземпляр класса [XmlSchemaElement](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Инициализирует новый экземпляр класса [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | Инициализирует новый экземпляр класса [XmlSchemaParticle](../xmlschemaparticle/). |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
## Типы

| Тип | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Замечания

Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его функциям в качестве аргумента. 

## Смотри также

* Класс [XmlSchemaParticle](../xmlschemaparticle/)
* Пространство имён [System::Xml::Schema](../)
* Библиотека [Aspose.Slides](../../)