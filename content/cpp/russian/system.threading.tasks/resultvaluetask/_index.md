---
title: ResultValueTask
second_title: Справочник API Aspose.Slides для C++
description: Представляет гибридный тип, похожий на задачу, который может оборачивать либо прямое значение результата, либо объект ResultTask<T>.
type: docs
weight: 53
url: /ru/system.threading.tasks/resultvaluetask/
---
## Класс ResultValueTask

Представляет гибридный тип, похожий на задачу, который может оборачивать либо прямое значение результата, либо объект ResultTask<T>.

```cpp
template<typename T>class ResultValueTask : public System::IEquatable<ResultValueTask<T>>,
                                            public System::Details::BoxableObjectBase
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип результата, производимого задачей. |
## Методы

| Метод | Описание |
| --- | --- |
| [RTaskPtr](../../system/rtaskptr/)\<T\> [AsTask](./astask/)() const | Преобразует этот [ResultValueTask](./) в shared pointer к ResultTask<T>. |
| [Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable](../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | Настраивает awaiter для этой задачи. |
| **bool** [Equals](./equals/)([ResultValueTask](./)) override | Определяет, равен ли данный экземпляр другому экземпляру [ResultValueTask](./). |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Определяет, равен ли данный экземпляр другому объекту. |
| virtual **bool** [Equals](../../system/iequatable/equals/)(T) | Определяет, равны ли текущий и указанный объекты. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равно ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равно ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | Возвращает значение, указывающее, завершилась задача из-за отмены. |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | Возвращает значение, указывающее, завершилась ли задача. |
| **bool** [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | Возвращает значение, указывающее, успешно завершилась задача. |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | Возвращает значение, указывающее, задача завершилась из-за необработанного исключения. |
| T [get_Result](./get_result/)() | Возвращает результат завершённой задачи. |
| [Runtime::CompilerServices::ResultValueTaskAwaiter](../../system.runtime.compilerservices/resultvaluetaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | Возвращает awaiter для этой задачи, поддерживающий выражения await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Возвращает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Возвращает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку, аналог C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет создавать копии в подклассах. |
| **bool** [operator!=](./operator_not_equal/)(const [ResultValueTask](./)\&) const | Оператор неравенства для [ResultValueTask](./). |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет создавать копии в подклассах. |
| **bool** [operator==](./operator_equal_equal/)(const [ResultValueTask](./)\&) const | Оператор равенства для [ResultValueTask](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на заданное значение. |
| [ResultValueTask](./resultvaluetask/)() | Создаёт пустой, неинициализированный [ResultValueTask](./). |
| [ResultValueTask](./resultvaluetask/)(const T\&) | Создаёт завершённый [ResultValueTask](./) с указанным результатом. |
| [ResultValueTask](./resultvaluetask/)(const [RTaskPtr](../../system/rtaskptr/)\<T\>\&) | Создаёт [ResultValueTask](./) из shared pointer к ResultTask<T>. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона как weak-указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Возвращает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку, аналог C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик weak-ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик weak-ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
## Примечания

[ResultValueTask](./) объединяет преимущества [ValueTask](../valuetask/) (сокращённые выделения памяти для синхронных результатов) с возможностью оборачивать существующие объекты ResultTask<T>. Он предоставляет интерфейс с поддержкой await и различные методы инспекции статуса задачи. 
## См. также

* Класс [IEquatable](../../system/iequatable/)
* Пространство имён [System::Threading::Tasks](../)
* Библиотека [Aspose.Slides](../../)