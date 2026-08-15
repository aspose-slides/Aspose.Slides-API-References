---
title: Task
second_title: Aspose.Slides for C++ API 參考
description: 表示一個可以被等待且可與其他任務組合的非同步操作。
type: docs
weight: 66
url: /zh-hant/system.threading.tasks/task/
---
## Task 類別

表示一個可以被等待且可與其他任務組合的非同步操作。

```cpp
class Task : public System::IDisposable
```
## 方法

| 方法 | 說明 |
| --- | --- |
| void [Activate](./activate/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | 在排程器上啟動任務以供執行。 |
| void [AddCompletionAction](./addcompletionaction/)(const [Action](../../system/action/)<>\&) | 在完成時加入要執行的延續動作。 |
| void [Cancel](./cancel/)() | 將任務標記為已取消並結束任務。 |
| void [Complete](./complete/)() | 將任務標記為已完成並結束任務。 |
| [Runtime::CompilerServices::ConfiguredTaskAwaitable](../../system.runtime.compilerservices/configuredtaskawaitable/) [ConfigureAwait](./configureawait/)(**bool**) const | 設定對此任務的 await 在上下文捕獲方面的行為。 |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | 建立在任務完成時執行的延續。 |
| [RTaskPtr](../../system/rtaskptr/)\<TResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/), TResult\>\&) | 建立在任務完成時執行的延續。 |
| void [Deactivate](./deactivate/)() | 停用此任務在其當前排程器上的執行（若有的話）。 |
| void [Dispose](./dispose/)() override | 釋放與任務相關的資源。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| void [Execute](./execute/)() | 執行任務的函式。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](./get_asyncstate/)() const | 取得與任務關聯的使用者自訂狀態物件。 |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](./get_completedtask/)() | 取得已完成的任務（單例）。 |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](./get_currentid/)() |  |
| [AggregateException](../../system/aggregateexception/) [get_Exception](./get_exception/)() const | 取得任務的 ID。 |
| **int32_t** [get_Id](./get_id/)() const |  |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | 取得任務是否因取消而完成。 |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | 取得任務是否已完成。 |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | 取得任務是否因未處理的例外而完成。 |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_Scheduler](./get_scheduler/)() const | 取得與此任務關聯的排程器。 |
| [TaskStatus](../taskstatus/) [get_Status](./get_status/)() const | 取得任務目前的狀態。 |
| [Runtime::CompilerServices::TaskAwaiter](../../system.runtime.compilerservices/taskawaiter/) [GetAwaiter](./getawaiter/)() const | 取得用於 Await 的此任務 awaiter。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [RunSynchronously](./runsynchronously/)() | 在當前執行緒上同步執行任務。 |
| void [RunSynchronously](./runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | 使用指定的排程器在同步方式執行任務。 |
| void [set_Function](./set_function/)(const [FunctionT](./functiont/)\&) | 設定要執行的內部函式。 |
| void [set_Scheduler](./set_scheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | 設定此任務關聯的排程器。 |
| void [set_Status](./set_status/)([TaskStatus](../taskstatus/)) | 設定任務狀態。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [Start](./start/)() | 使用預設排程器啟動任務執行。 |
| void [Start](./start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | 使用指定的排程器啟動任務執行。 |
|  [Task](./task/)(const [Action](../../system/action/)<>\&) | 以執行動作建立一個 [Task](./)。 |
|  [Task](./task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | 以動作與取消代幣建立一個 [Task](./)。 |
|  [Task](./task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 以有狀態的動作與狀態物件建立一個 [Task](./)。 |
|  [Task](./task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | 以有狀態的動作、狀態與取消代幣建立一個 [Task](./)。 |
|  [Task](./task/)() | 用於建立未初始化任務的內部建構子。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| void [Wait](./wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | 在支援取消的情況下等待任務完成。 |
| void [Wait](./wait/)() | 等待任務完成。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
|  [~Task](./~task/)() | 解構子。 |
## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [FunctionT](./functiont/) | 內部實作。不供使用者程式碼使用。 |
## 備註

提供與 .NET 中 [System.Threading.Tasks.Task](./) 類似的 C++ 實作，支援取消、延續以及 async/await 模式。 
## 另請參閱

* 類別 [IDisposable](../../system/idisposable/)
* 命名空間 [System::Threading::Tasks](../)
* 函式庫 [Aspose.Slides](../../)