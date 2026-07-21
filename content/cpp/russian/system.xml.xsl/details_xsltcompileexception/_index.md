---
title: Details_XsltCompileException
second_title: Справочник API Aspose.Slides для C++
description: Исключение, которое выбрасывается методом Load, когда в XSLT-таблице стилей обнаружена ошибка.
type: docs
weight: 1
url: /ru/system.xml.xsl/details_xsltcompileexception/
---
## Details_XsltCompileException класс

Исключение, которое генерируется методом **Load**, когда в XSLT-таблице стилей обнаруживается ошибка.

```cpp
class Details_XsltCompileException : public System::Xml::Xsl::Details_XsltException
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типажа значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних нужд. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Возвращает словарь с пользовательскими данными исключения. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Возвращает 32-битное целочисленное значение, представляющее код HRESULT, связанный с исключением, представленным текущим объектом. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Возвращает ссылку на объект, представляющий вложенное исключение. |
| virtual **int32_t** [get_LineNumber](../details_xsltexception/get_linenumber/)() | Возвращает номер строки, указывающий, где в таблице стилей произошла ошибка. |
| virtual **int32_t** [get_LinePosition](../details_xsltexception/get_lineposition/)() | Возвращает позицию в строке, указывающую, где в таблице стилей произошла ошибка. |
| [String](../../system/string/) [get_Message](../details_xsltexception/get_message/)() const override | Возвращает отформатированное сообщение об ошибке, описывающее текущее исключение. |
| virtual [String](../../system/string/) [get_SourceUri](../details_xsltexception/get_sourceuri/)() | Возвращает путь к расположению таблицы стилей. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Возвращает строку, содержащую трассировку стека. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Возвращает копию объекта Exception, представляющую самое внутреннее исключение. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_systemexception/gettype/)() const override | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [Is](../../system/details_systemexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывается напрямую или использует объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает ссылкой объект типажа значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Устанавливает HRESULT — кодовое числовое значение, присваиваемое конкретному исключению. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Инкрементирует счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Декрементирует и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Возвращает строковое представление текущего объекта. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_systemexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывается напрямую или использует объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Инкрементирует счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Декрементирует счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual const char * [what](../../system/details_exception/what/)() const | Реализует метод [what()](../../system/details_exception/what/), вызываемый классом [ExceptionWrapper](../../system/exceptionwrapper/). Несмотря на то, что этот класс не наследуется от std::exception, производные классы могут использовать защищённые/приватные члены для реализации своей логики. Перемещение реализации метода в [ExceptionWrapper](../../system/exceptionwrapper/) может нарушить эту логику. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Типы

| Тип | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для умного указателя на экземпляр этого класса. |

## См. также

* Класс [Details_XsltException](../details_xsltexception/)
* Пространство имён [System::Xml::Xsl](../)
* Библиотека [Aspose.Slides](../../)