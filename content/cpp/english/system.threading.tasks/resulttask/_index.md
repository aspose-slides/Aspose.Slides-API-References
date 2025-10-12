---
title: ResultTask
second_title: Aspose.Slides for C++ API Reference
description: A Task specialization that returns a result value upon completion.
type: docs
weight: 1
url: /system.threading.tasks/resulttask/
---
## ResultTask class


A [Task](../task/) specialization that returns a result value upon completion.

```cpp
template<typename T>class ResultTask : public System::Threading::Tasks::Task
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of the result value returned by the task |
## Methods

| Method | Description |
| --- | --- |
| void [Activate](../task/activate/)([TaskScheduler](../taskscheduler/) *) | Activates the task for execution on a scheduler. |
| void [AddContinuation](../task/addcontinuation/)(const [Action](../../system/action/)<>\&) | Adds a continuation action to be executed upon completion. |
| void [Complete](../task/complete/)() | Marks the task as completed and finishes task. |
| [Runtime::CompilerServices::ConfiguredResultTaskAwaitable](../../system.runtime.compilerservices/configuredresulttaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | Configures how awaits on this result task should behave regarding context capture. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>\>\&) | Creates a continuation that executes when the result task completes. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](../task/continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | Creates a continuation that executes when the task completes. |
| void [Dispose](../task/dispose/)() override | Releases resources associated with the task. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| void [Execute](../task/execute/)() | Executes the task's function. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](../task/get_asyncstate/)() const | Gets the user-defined state object associated with the task. |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](../task/get_completedtask/)() | Gets a completed task (singleton) |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](../task/get_currentid/)() |  |
| **int32_t** [get_Id](../task/get_id/)() const | Gets the ID for task. |
| **bool** [get_IsCanceled](../task/get_iscanceled/)() const | Gets whether the task completed due to cancellation. |
| **bool** [get_IsCompleted](../task/get_iscompleted/)() const | Gets whether the task has completed. |
| **bool** [get_IsFaulted](../task/get_isfaulted/)() const | Gets whether the task completed due to an unhandled exception. |
| T [get_Result](./get_result/)() const | Gets the result of the asynchronous operation. |
| [TaskScheduler](../taskscheduler/) * [get_Scheduler](../task/get_scheduler/)() const | Gets the scheduler associated with this task. |
| [TaskStatus](../taskstatus/) [get_Status](../task/get_status/)() const | Gets the current status of the task. |
| [Runtime::CompilerServices::ResultTaskAwaiter](../../system.runtime.compilerservices/resulttaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | Gets an awaiter for this result task for use with Await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
|  [ResultTask](./resulttask/)(const [Func](../../system/func/)\<T\>\&) | Constructs a [ResultTask](./) with a function that returns a value. |
|  [ResultTask](./resulttask/)() | Internal implementation. Not for user code. |
|  [ResultTask](./resulttask/)(const T\&) | Internal constructor for creating result tasks with specified result. |
| void [RunSynchronously](../task/runsynchronously/)() | Runs the task synchronously on the current thread. |
| void [RunSynchronously](../task/runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Runs the task synchronously using the specified scheduler. |
| void [set_Function](../task/set_function/)(const [FunctionT](../task/functiont/)\&) | Sets the internal function to execute. |
| void [set_Result](./set_result/)(const T\&) | Sets the result value for the task. |
| void [set_Scheduler](../task/set_scheduler/)([TaskScheduler](../taskscheduler/) *) | Sets the scheduler associated with this task. |
| void [set_Status](../task/set_status/)([TaskStatus](../taskstatus/)) | Sets the task status. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [Start](../task/start/)() | Starts the task execution using the default scheduler. |
| void [Start](../task/start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Starts the task execution using the specified scheduler. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&) | Constructs a [Task](../task/) with an action to execute. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Constructs a [Task](../task/) with an action and cancellation token. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Constructs a [Task](../task/) with a stateful action and state object. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Constructs a [Task](../task/) with stateful action, state, and cancellation token. |
|  [Task](../task/task/)() | Internal constructor for creating uninitialized tasks. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| void [Wait](../task/wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) const | Waits for the task to complete with cancellation support. |
| void [Wait](../task/wait/)() const | Waits for the task to complete. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
|  [~Task](../task/~task/)() | Destructor. |
## Remarks



Represents an asynchronous operation that produces a result, similar to System.Threading.Tasks.Task<TResult> in .NET 
## See Also

* Class [Task](../task/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)