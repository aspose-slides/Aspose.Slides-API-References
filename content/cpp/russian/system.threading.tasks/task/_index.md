---
title: Task
second_title: Справочник API Aspose.Slides для C++
description: Представляет асинхронную операцию, которую можно ожидать и комбинировать с другими задачами.
type: docs
weight: 66
url: /ru/system.threading.tasks/task/
---
## Класс Task

Represents an asynchronous operation that can be awaited and composed with other tasks.

```cpp
class Task : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| void [Activate](./activate/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Активирует задачу для выполнения планировщиком. |
| void [AddCompletionAction](./addcompletionaction/)(const [Action](../../system/action/)<>\&) | Добавляет действие продолжения, которое будет выполнено после завершения. |
| void [Cancel](./cancel/)() | Помечает задачу как отменённую и завершает её. |
| void [Complete](./complete/)() | Помечает задачу как выполненную и завершает её. |
| [Runtime::CompilerServices::ConfiguredTaskAwaitable](../../system.runtime.compilerservices/configuredtaskawaitable/) [ConfigureAwait](./configureawait/)(**bool**) const | Настраивает поведение ожиданий этой задачи относительно захвата контекста. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | Создаёт продолжение, которое выполняется при завершении задачи. |
| [RTaskPtr](../../system/rtaskptr/)\<TResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/), TResult\>\&) | Создаёт продолжение, которое выполняется при завершении задачи. |
| void [Deactivate](./deactivate/)() | Деактивирует задачу для выполнения на её текущем планировщике, если он есть. |
| void [Dispose](./dispose/)() override | Освобождает ресурсы, связанные с задачей. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| void [Execute](./execute/)() | Выполняет функцию задачи. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](./get_asyncstate/)() const | Возвращает пользовательский объект состояния, связанный с задачей. |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](./get_completedtask/)() | Возвращает выполненную задачу (singleton). |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](./get_currentid/)() |  |
| [AggregateException](../../system/aggregateexception/) [get_Exception](./get_exception/)() const | Возвращает идентификатор задачи. |
| **int32_t** [get_Id](./get_id/)() const |  |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | Возвращает, завершилась ли задача из-за отмены. |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | Возвращает, завершена ли задача. |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | Возвращает, завершилась ли задача из-за необработанного исключения. |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_Scheduler](./get_scheduler/)() const | Возвращает планировщик, связанный с этой задачей. |
| [TaskStatus](../taskstatus/) [get_Status](./get_status/)() const | Возвращает текущий статус задачи. |
| [Runtime::CompilerServices::TaskAwaiter](../../system.runtime.compilerservices/taskawaiter/) [GetAwaiter](./getawaiter/)() const | Возвращает awaiter для этой задачи для использования с Await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Возвращает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Возвращает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывается напрямую или с объектом-стражем [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типa значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [RunSynchronously](./runsynchronously/)() | Запускает задачу синхронно в текущем потоке. |
| void [RunSynchronously](./runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Запускает задачу синхронно, используя указанный планировщик. |
| void [set_Function](./set_function/)(const [FunctionT](./functiont/)\&) | Устанавливает внутреннюю функцию для выполнения. |
| void [set_Scheduler](./set_scheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Устанавливает планировщик, связанный с этой задачей. |
| void [set_Status](./set_status/)([TaskStatus](../taskstatus/)) | Устанавливает статус задачи. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Возвращает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [Start](./start/)() | Запускает выполнение задачи, используя планировщик по умолчанию. |
| void [Start](./start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Запускает выполнение задачи, используя указанный планировщик. |
|  [Task](./task/)(const [Action](../../system/action/)<>\&) | Создаёт [Task](./) с действием для выполнения. |
|  [Task](./task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Создаёт [Task](./) с действием и токеном отмены. |
|  [Task](./task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Создаёт [Task](./) с действием с состоянием и объектом состояния. |
|  [Task](./task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Создаёт [Task](./) с действием с состоянием, состоянием и токеном отмены. |
|  [Task](./task/)() | Внутренний конструктор для создания неинициализированных задач. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывается напрямую или с объектом-стражем [LockContext](../../system/lockcontext/). |
| void [Wait](./wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Ожидает завершения задачи с поддержкой отмены. |
| void [Wait](./wait/)() | Ожидает завершения задачи. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
|  [~Task](./~task/)() | Деструктор. |

## Типedefы

| Типedef | Описание |
| --- | --- |
| [FunctionT](./functiont/) | Внутренняя реализация. Не предназначено для пользовательского кода. |

## Примечания

Provides a C++ implementation similar to [System.Threading.Tasks.Task](./) in .NET, supporting cancellation, continuations, and async/await patterns 

## См. также

* Класс [IDisposable](../../system/idisposable/)
* Пространство имён [System::Threading::Tasks](../)
* Библиотека [Aspose.Slides](../../)