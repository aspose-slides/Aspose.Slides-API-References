---
title: IAsyncResult
second_title: Справочник API Aspose.Slides для C++
description: "Представляет статус асинхронной операции. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 898
url: /ru/system/iasyncresult/
---
## IAsyncResult класс

Представляет статус асинхронной операции. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class IAsyncResult : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual [SharedPtr](../sharedptr/)\<[System::Object](../object/)\> [get_AsyncState](./get_asyncstate/)() | Возвращает объект, содержащий информацию об асинхронной операции. |
| virtual [SharedPtr](../sharedptr/)\<[System::Threading::WaitHandle](../../system.threading/waithandle/)\> [get_AsyncWaitHandle](./get_asyncwaithandle/)() | Возвращает экземпляр WaitHandle, который можно использовать для ожидания завершения асинхронной операции. |
| virtual **bool** [get_CompletedSynchronously](./get_completedsynchronously/)() | Возвращает значение, указывающее, завершилась ли асинхронная операция синхронно. |
| virtual **bool** [get_IsCompleted](./get_iscompleted/)() | Возвращает значение, указывающее, завершилась ли асинхронная операция. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../object/object/)([Object](../object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект значимого типа с nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Специализация [Object::ReferenceEquals](../object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (вместо общего). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Аналог метода C# [Object.ToString()](../object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Реализует конструкцию C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~IAsyncResult](./~iasyncresult/)() | Деструктор. |
| virtual  [~Object](../object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Типы

| Тип | Описание |
| --- | --- |
| [smart_ptr](./smart_ptr/) | Умный указатель на [IAsyncResult](./). |

## См. также

* Класс [Object](../object/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)