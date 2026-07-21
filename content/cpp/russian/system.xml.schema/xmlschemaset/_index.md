---
title: XmlSchemaSet
second_title: Справочник API Aspose.Slides для C++
description: Содержит кеш схем языка определения XML Schema (XSD).
type: docs
weight: 781
url: /ru/system.xml.schema/xmlschemaset/
---
## XmlSchemaSet класс

Содержит кеш схем XML [Schema](../) (XSD).

```cpp
class XmlSchemaSet : public System::Object
```

## Методы

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)([String](../../system/string/), const [String](../../system/string/)\&) | Добавляет схему XML [Schema](../) (XSD) по указанному URL в [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)([String](../../system/string/), const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | Добавляет схему XML [Schema](../) (XSD), содержащуюся в [XmlReader](../../system.xml/xmlreader/), в [XmlSchemaSet](./). |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](./)\>\&) | Добавляет все схемы XML [Schema](../) (XSD) из указанного [XmlSchemaSet](./) в [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Добавляет указанный [XmlSchema](../xmlschema/) в [XmlSchemaSet](./). |
| void [Compile](./compile/)() | Компилирует добавленные в [XmlSchemaSet](./) схемы XML [Schema](../) (XSD) в одну логическую схему. |
| **bool** [Contains](./contains/)([String](../../system/string/)) | Указывает, находится ли в [XmlSchemaSet](./) схема XML [Schema](../) (XSD) с указанным URI целевого пространства имён. |
| **bool** [Contains](./contains/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Указывает, находится ли указанный объект [XmlSchema](../xmlschema/) XML [Schema](../) (XSD) в [XmlSchemaSet](./). |
| void [CopyTo](./copyto/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\&, **int32_t**) | Копирует все объекты [XmlSchema](../xmlschema/) из [XmlSchemaSet](./) в заданный массив, начиная с указанного индекса. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, при котором два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, при котором два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)\> [get_CompilationSettings](./get_compilationsettings/)() | Возвращает [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) для [XmlSchemaSet](./). |
| **int32_t** [get_Count](./get_count/)() | Возвращает количество логических схем XML [Schema](../) (XSD) в [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalAttributes](./get_globalattributes/)() | Возвращает все глобальные атрибуты во всех схемах XML [Schema](../) (XSD) в [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalElements](./get_globalelements/)() | Возвращает все глобальные элементы во всех схемах XML [Schema](../) (XSD) в [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalTypes](./get_globaltypes/)() | Возвращает все глобальные простые и сложные типы во всех схемах XML [Schema](../) (XSD) в [XmlSchemaSet](./). |
| **bool** [get_IsCompiled](./get_iscompiled/)() | Возвращает значение, указывающее, были ли скомпилированы схемы XML [Schema](../) (XSD) в [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | Возвращает значение [XmlNameTable](../../system.xml/xmlnametable/) по умолчанию, используемое [XmlSchemaSet](./) при загрузке новых схем XML [Schema](../) (XSD). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет выполнять хеширование пользовательских объектов. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывается напрямую или с использованием объекта-сторожа [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, а лишь инициализирует новый объект и позволяет создавать копии подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, а лишь инициализирует новый объект и позволяет создавать копии подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения со ссылкой nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Удаляет указанную схему XML [Schema](../) (XSD) из [XmlSchemaSet](./). |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| **bool** [RemoveRecursive](./removerecursive/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Удаляет указанную схему XML [Schema](../) (XSD) и все импортируемые ею схемы из [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Reprocess](./reprocess/)([SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>) | Повторно обрабатывает схему XML [Schema](../) (XSD), уже существующую в [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\> [Schemas](./schemas/)() | Возвращает коллекцию всех схем XML [Schema](../) (XSD) в [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\> [Schemas](./schemas/)([String](../../system/string/)) | Возвращает коллекцию всех схем XML [Schema](../) (XSD) в [XmlSchemaSet](./), принадлежащих указанному пространству имён. |
| void [set_CompilationSettings](./set_compilationsettings/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)\>\&) | Устанавливает [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) для [XmlSchemaSet](./). |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Устанавливает [XmlResolver](../../system.xml/xmlresolver/), используемый для разрешения пространств имён или мест, указанных в элементах include и import схемы. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывается напрямую или с использованием страж-объекта [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Добавляет обработчик событий для получения информации об ошибках проверки схемы XML [Schema](../) (XSD). |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Удаляет обработчик событий для получения информации об ошибках проверки схемы XML [Schema](../) (XSD). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
|  [XmlSchemaSet](./xmlschemaset/)() | Инициализирует новый экземпляр класса [XmlSchemaSet](./). |
|  [XmlSchemaSet](./xmlschemaset/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>\&) | Инициализирует новый экземпляр класса [XmlSchemaSet](./) с указанным [XmlNameTable](../../system.xml/xmlnametable/). |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |

## Примечания

Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. 

## См. также

* Класс [Object](../../system/object/)
* Пространство имён [System::Xml::Schema](../)
* Библиотека [Aspose.Slides](../../)