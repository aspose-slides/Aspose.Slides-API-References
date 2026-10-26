---
title: Details_AggregateException
second_title: Aspose.Slides для C++ справочник API
description: Представляет исключение, которое содержит несколько вложенных исключений.
type: docs
weight: 300
url: /ru/system/details_aggregateexception/
---
## Details_AggregateException класс

Представляет исключение, которое содержит несколько вложенных исключений.

```cpp
class Details_AggregateException : public System::Details_Exception
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значений в стиле C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [AggregateException](../aggregateexception/) [Flatten](./flatten/)() | Разворачивает агрегирующее исключение, распаковывая все вложенные AggregateExceptions в одноуровневый список. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Возвращает словарь с пользовательскими данными исключения. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Возвращает 32-битное целочисленное значение, представляющее код HRESULT, связанный с исключением, представленным текущим объектом. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Возвращает ссылку на объект, представляющий вложенное исключение. |
| **int32_t** [get_InnerExceptionCount](./get_innerexceptioncount/)() | Получает количество вложенных исключений, содержащихся в этом агрегирующем исключении. |
| [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[Exception](../exception/)\>\> [get_InnerExceptions](./get_innerexceptions/)() | Получает только для чтения коллекцию вложенных исключений. |
| const [ArrayPtr](../arrayptr/)\<[Exception](../exception/)\>\& [get_InternalInnerExceptions](./get_internalinnerexceptions/)() | Возвращает внутренний массив вложенных исключений. |
| [String](../string/) [get_Message](./get_message/)() const override | Переопределяет базовое сообщение, включающее агрегированную информацию обо всех вложенных исключениях. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Возвращает строку, содержащую трассировку стека. |
| [Exception](../exception/) [GetBaseException](./getbaseexception/)() const override | Возвращает исходное исключение, рекурсивно распаковывая вложенные исключения. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../object/gettype/). |
| void [Handle](./handle/)(const [Func](../func/)\<[Exception](../exception/), **bool**\>\&) | Вызывает функцию-обработчик для каждого вложенного исключения и повторно генерирует любые необработанные исключения. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../object/object/)([Object](../object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Специализация [Object::ReferenceEquals](../object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Устанавливает HRESULT, закодированное числовое значение, назначаемое конкретному исключению. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабую указательную ссылку (вместо shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Возвращает строковое представление исключения, включая все вложенные исключения. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Реализует конструкцию C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Реализует метод [what()](../details_exception/what/), вызываемый классом [ExceptionWrapper](../exceptionwrapper/). Несмотря на то, что этот класс не наследуется от std::exception, производные классы могут использовать защищённые/приватные члены для реализации своей логики. Перемещение реализации этого метода в [ExceptionWrapper](../exceptionwrapper/) может нарушить эту логику. |
| virtual  [~Object](../object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Примечания

Этот класс обычно используется для объединения нескольких исключений, происходящих одновременно, например в сценариях параллельной обработки или асинхронного выполнения задач. Он позволяет пользователям исследовать, разворачивать или избирательно обрабатывать содержащиеся исключения. 

## См. также

* Класс [Details_Exception](../details_exception/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)