---
title: XmlReaderSettings
second_title: Aspose.Slides для C++ справочник API
description: "Определяет набор функций, поддерживаемых объектом XmlReader, созданным методом XmlReader::Create."
type: docs
weight: 443
url: /ru/system.xml/xmlreadersettings/
---
## XmlReaderSettings класс

Указывает набор функций, поддерживаемых объектом [XmlReader](../xmlreader/), созданным методом [XmlReader::Create](../xmlreader/create/).

```cpp
class XmlReaderSettings : public System::Object
```

## Методы

| Method | Description |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | Создаёт копию экземпляра [XmlReaderSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типажа значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, когда два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, когда два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Возвращает значение, указывающее, следует ли выполнять проверку символов. |
| **bool** [get_CloseInput](./get_closeinput/)() | Возвращает значение, указывающее, следует ли закрывать базовый поток или TextReader при закрытии считывателя. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Возвращает уровень соответствия, которому будет соответствовать [XmlReader](../xmlreader/). |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Возвращает значение, определяющее обработку DTD. |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | Возвращает значение, указывающее, следует ли игнорировать комментарии. |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | Возвращает значение, указывающее, следует ли игнорировать инструкции обработки. |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | Возвращает значение, указывающее, следует ли игнорировать незначимые пробельные символы. |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | Возвращает смещение номера строки объекта [XmlReader](../xmlreader/). |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | Возвращает смещение позиции строки объекта [XmlReader](../xmlreader/). |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | Возвращает значение, указывающее максимальное допустимое количество символов в документе, получаемое в результате раскрытия сущностей. |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | Возвращает значение, указывающее максимальное допустимое количество символов в XML-документе. Ноль (0) означает отсутствие ограничений размера XML-документа. Ненулевое значение задаёт максимальный размер в символах. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Возвращает [XmlNameTable](../xmlnametable/), используемый для атомарных сравнений строк. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Возвращает значение, указывающее, следует ли запрещать обработку определений типов документов (DTD). |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | Возвращает XmlSchemaSet, используемый при выполнении проверки схемы. |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | Возвращает значение, указывающее настройки проверки схемы. Этот параметр применяется к объектам [XmlReader](../xmlreader/), которые проверяют схемы (значение [XmlReaderSettings::get_ValidationType](./get_validationtype/) равно [ValidationType::Schema](../validationtype/)). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Возвращает значение, указывающее, будет ли [XmlReader](../xmlreader/) выполнять проверку или назначение типа при чтении. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# `is`. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку, аналогичную оператору C# `lock()`. Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет наследникам копировать конструкторы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет наследникам копировать конструкторы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типажа значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместно используемых ссылок на указанное значение. |
| void [Reset](./reset/)() | Сбрасывает члены класса настроек к их значениям по умолчанию. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Устанавливает значение, указывающее, следует ли выполнять проверку символов. |
| void [set_CloseInput](./set_closeinput/)(**bool**) | Устанавливает значение, указывающее, следует ли закрывать базовый поток или TextReader при закрытии считывателя. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Устанавливает уровень соответствия, которому будет соответствовать [XmlReader](../xmlreader/). |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Устанавливает значение, определяющее обработку DTD. |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | Устанавливает значение, указывающее, следует ли игнорировать комментарии. |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | Устанавливает значение, указывающее, следует ли игнорировать инструкции обработки. |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | Устанавливает значение, указывающее, следует ли игнорировать незначимые пробельные символы. |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | Устанавливает смещение номера строки объекта [XmlReader](../xmlreader/). |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | Устанавливает смещение позиции строки объекта [XmlReader](../xmlreader/). |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | Устанавливает значение, указывающее максимальное допустимое количество символов в документе, получаемое в результате раскрытия сущностей. |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | Устанавливает значение, указывающее максимальное допустимое количество символов в XML-документе. Ноль (0) означает отсутствие ограничений размера XML-документа. Ненулевое значение задаёт максимальный размер в символах. |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Устанавливает [XmlNameTable](../xmlnametable/), используемый для атомарных сравнений строк. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Устанавливает значение, указывающее, следует ли запрещать обработку определений типов документов (DTD). |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | Устанавливает XmlSchemaSet, используемый при выполнении проверки схемы. |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | Устанавливает значение, указывающее настройки проверки схемы. Этот параметр применяется к объектам [XmlReader](../xmlreader/), которые проверяют схемы (значение [XmlReaderSettings::get_ValidationType](./get_validationtype/) равно [ValidationType::Schema](../validationtype/)). |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Устанавливает значение, указывающее, будет ли [XmlReader](../xmlreader/) выполнять проверку или назначение типа при чтении. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Устанавливает [XmlResolver](../xmlresolver/), используемый для доступа к внешним документам. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместно используемых ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместно используемых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместно используемых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку, аналогичную оператору C# `lock()`. Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Добавляет обработчик события, возникающий при ошибках проверки валидности считывателя. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Удаляет обработчик события, возникающий при ошибках проверки валидности считывателя. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
|  [XmlReaderSettings](./xmlreadersettings/)() | Инициализирует новый экземпляр класса [XmlReaderSettings](./). |
| virtual  [~Object](../../system/object/~object/)() | Удаляет объект. Освобождает все внутренние структуры данных. |

## Typedef'ы

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним shared-указателя на экземпляр этого класса. |

## Замечания

Объекты этого класса следует создавать только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## Смотрите также

* Класс [Object](../../system/object/)
* Пространство имён [System::Xml](../)
* Библиотека [Aspose.Slides](../../)