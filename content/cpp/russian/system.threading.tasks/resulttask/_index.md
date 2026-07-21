---
title: ResultTask
second_title: Aspose.Slides для C++ справочник API
description: Специализация Task, возвращающая значение результата после завершения.
type: docs
weight: 40
url: /ru/system.threading.tasks/resulttask/
---
## ResultTask класс

A [Task](../task/) specialization that returns a result value upon completion.

```cpp
template<typename T>class ResultTask : public System::Threading::Tasks::Task
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | The type of the result value returned by the task |

## Методы

| Метод | Описание |
| --- | --- |
| void [Activate](../task/activate/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Активирует задачу для выполнения на планировщике. |
| void [AddCompletionAction](../task/addcompletionaction/)(const [Action](../../system/action/)<>\&) | Добавляет действие продолжения, которое будет выполнено после завершения. |
| void [Cancel](../task/cancel/)() | Помечает задачу как отменённую и завершает её. |
| void [Complete](./complete/)(const T\&) | Устанавливает значение результата задачи и завершает её. |
| void [Complete](../task/complete/)() | Помечает задачу как завершённую и завершает её. |
| [Runtime::CompilerServices::ConfiguredResultTaskAwaitable](../../system.runtime.compilerservices/configuredresulttaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | Настраивает поведение ожиданий этого результата задачи относительно захвата контекста. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>\>\&) | Создаёт продолжение, которое выполняется при завершении задачи результата. |
| [RTaskPtr](../../system/rtaskptr/)\<TNewResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>, TNewResult\>\&) | Создаёт продолжение, которое выполняется при завершении задачи результата. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | Создаёт продолжение, которое выполняется при завершении задачи. |
| [RTaskPtr](../../system/rtaskptr/)\<TResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/), TResult\>\&) | Создаёт продолжение, которое выполняется при завершении задачи. |
| void [Deactivate](../task/deactivate/)() | Деактивирует задачу для выполнения на её текущем планировщике, если таковой имеется. |
| void [Dispose](../task/dispose/)() override | Освобождает ресурсы, связанные с задачей. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| void [Execute](../task/execute/)() | Выполняет функцию задачи. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](../task/get_asyncstate/)() const | Получает пользовательский объект состояния, связанный с задачей. |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](../task/get_completedtask/)() | Получает завершённую задачу (singleton) |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](../task/get_currentid/)() |  |
| [AggregateException](../../system/aggregateexception/) [get_Exception](../task/get_exception/)() const | Получает идентификатор задачи. |
| **int32_t** [get_Id](../task/get_id/)() const |  |
| **bool** [get_IsCanceled](../task/get_iscanceled/)() const | Определяет, завершилась ли задача из-за отмены. |
| **bool** [get_IsCompleted](../task/get_iscompleted/)() const | Определяет, завершена ли задача. |
| **bool** [get_IsFaulted](../task/get_isfaulted/)() const | Определяет, завершилась ли задача из-за необработанного исключения. |
| T [get_Result](./get_result/)() | Получает результат асинхронной операции. |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_Scheduler](../task/get_scheduler/)() const | Получает планировщик, связанный с этой задачей. |
| [TaskStatus](../taskstatus/) [get_Status](../task/get_status/)() const | Получает текущий статус задачи. |
| [Runtime::CompilerServices::ResultTaskAwaiter](../../system.runtime.compilerservices/resulttaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | Получает awaiter для этой задачи результата для использования с Await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
|  [ResultTask](./resulttask/)(const [Func](../../system/func/)\<T\>\&) | Создаёт [ResultTask](./) с функцией, возвращающей значение. |
|  [ResultTask](./resulttask/)() | Внутренняя реализация. Не предназначена для пользовательского кода. |
|  [ResultTask](./resulttask/)(const T\&) | Внутренний конструктор для создания задач результата с указанным результатом. |
| void [RunSynchronously](../task/runsynchronously/)() | Запускает задачу синхронно в текущем потоке. |
| void [RunSynchronously](../task/runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Запускает задачу синхронно, используя указанный планировщик. |
| void [set_Function](../task/set_function/)(const [FunctionT](../task/functiont/)\&) | Устанавливает внутреннюю функцию для выполнения. |
| void [set_Result](./set_result/)(const T\&) | Устанавливает значение результата задачи. |
| void [set_Scheduler](../task/set_scheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Устанавливает планировщик, связанный с этой задачей. |
| void [set_Status](../task/set_status/)([TaskStatus](../taskstatus/)) | Устанавливает статус задачи. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [Start](../task/start/)() | Запускает выполнение задачи, используя планировщик по умолчанию. |
| void [Start](../task/start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Запускает выполнение задачи, используя указанный планировщик. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&) | Создаёт [Task](../task/) с действием для выполнения. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Создаёт [Task](../task/) с действием и токеном отмены. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Создаёт [Task](../task/) с состоянием и объектом состояния. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Создаёт [Task](../task/) с состоянием, объектом состояния и токеном отмены. |
|  [Task](../task/task/)() | Внутренний конструктор для создания неинициализированных задач. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| void [Wait](../task/wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Ожидает завершения задачи с поддержкой отмены. |
| void [Wait](../task/wait/)() | Ожидает завершения задачи. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
|  [~Task](../task/~task/)() | Деструктор. |

## Примечания

Represents an asynchronous operation that produces a result, similar to System.Threading.Tasks.Task<TResult> in .NET 

## См. также

* Класс [Task](../task/)
* Пространство имён [System::Threading::Tasks](../)
* Библиотека [Aspose.Slides](../../)