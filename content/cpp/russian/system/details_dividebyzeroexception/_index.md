---
title: Details_DivideByZeroException
second_title: Aspose.Slides для C++ справочник API
description: "DivideByZeroException выбрасывается, когда в арифметической операции пытаются выполнить деление на 0. Никогда не создавайте экземпляры этого класса вручную. Вместо этого используйте класс DivideByZeroException. Никогда не оборачивайте экземпляры класса DivideByZeroException в System::SmartPtr."
type: docs
weight: 404
url: /ru/system/details_dividebyzeroexception/
---
## Details_DivideByZeroException класс

DivideByZeroException вызывается, когда в арифметической операции пытаются выполнить деление на 0. Никогда не создавайте экземпляры этого класса вручную. Используйте класс DivideByZeroException. Никогда не оборачивайте экземпляры класса DivideByZeroException в [System::SmartPtr](../smartptr/).

```cpp
class Details_DivideByZeroException : public System::Details_ArithmeticException
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равно ни одному значению, включая NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равно ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Возвращает словарь с пользовательскими данными исключения. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Возвращает 32-битное целочисленное значение, которое является кодом HRESULT, связанным с исключением, представленным текущим объектом. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Возвращает ссылку на объект, представляющий внутреннее исключение. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Возвращает строку, содержащую описание ошибки. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Возвращает строку, содержащую трассировку стека. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Возвращает копию объекта Exception, представляющего самое внутреннее исключение. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../object/object/)([Object](../object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект значимого типа с nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Специализация [Object::ReferenceEquals](../object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Уменьшает счетчик общих ссылок на указанное значение. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Устанавливает HRESULT — кодовое числовое значение, присваиваемое конкретному исключению. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона в слабый указатель (а не в shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../object/sharedcount/)() const | Получает текущее значение счетчика общих ссылок. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Увеличивает счетчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Уменьшает и возвращает значение счетчика общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Возвращает строковое представление текущего объекта. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Реализует метод [what()](../details_exception/what/), который вызывается классом [ExceptionWrapper](../exceptionwrapper/). Несмотря на то, что этот класс не наследуется от std::exception, производные классы могут использовать защищённые/приватные члены для реализации своей логики. Перемещение реализации этого метода в [ExceptionWrapper](../exceptionwrapper/) может нарушить эту логику. |
| virtual  [~Object](../object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Примечания

OutOfMemoryException выбрасывается, когда приложению не хватает памяти. Никогда не создавайте экземпляры этого класса вручную. Используйте класс OutOfMemoryException. Никогда не оборачивайте экземпляры класса OutOfMemoryException в [System::SmartPtr](../smartptr/).

## Смотрите также

* Класс [Details_ArithmeticException](../details_arithmeticexception/)
* Пространство имен [System](../)
* Библиотека [Aspose.Slides](../../)