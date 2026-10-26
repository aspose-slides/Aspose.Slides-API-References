---
title: "System::Threading"
second_title: Aspose.Slides for C++ API 參考
description: 
type: docs
weight: 1002
url: /zh-hant/system.threading/
---
## 類別

| 類別 | 描述 |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | 事件，用於通知等待執行緒自動重設。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。 |
| [CancellationToken](./cancellationtoken/) | 傳播應取消操作的通知。此類別提供在線程之間合作取消的機制，允許一個執行緒通知其他執行緒應取消某個操作。 |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | 表示取消代幣回呼的註冊。 |
| [CancellationTokenSource](./cancellationtokensource/) | 可用於觸發取消通知的取消代幣來源。 |
| [Details_SemaphoreFullException](./details_semaphorefullexception/) |  |
| [Details_SynchronizationLockException](./details_synchronizationlockexception/) |  |
| [Details_ThreadAbortException](./details_threadabortexception/) |  |
| [Details_ThreadInterruptedException](./details_threadinterruptedexception/) |  |
| [Details_ThreadStateException](./details_threadstateexception/) |  |
| [EventWaitHandle](./eventwaithandle/) | 可發送給等待執行緒的事件。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。 |
| [Interlocked](./interlocked/) | 提供執行緒安全操作的 API。這是一個沒有實例服務的靜態類型。絕不應以任何方式建立其實例。 |
| [ManualResetEvent](./manualresetevent/) | 事件，用於通知等待執行緒且不會自動重設。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。 |
| [Monitor](./monitor/) | 類別 [Monitor](./monitor/) 提供同步存取物件的機制。 |
| [Mutex](./mutex/) | [Mutex](./mutex/) 實作。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。 |
| [Semaphore](./semaphore/) | [Semaphore](./semaphore/) 實作。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。 |
| [SynchronizationContext](./synchronizationcontext/) | 提供在各種同步操作中傳遞同步上下文的基本功能。 |
| [Thread](./thread/) | [Thread](./thread/) 實作。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。 |
| [ThreadPool](./threadpool/) | [Thread](./thread/) 池 API，允許將工作推入佇列，供工作執行緒池讀取。這是一個沒有實例服務的靜態類型。絕不應以任何方式建立其實例。 |
| [ThreadPoolImpl](./threadpoolimpl/) | [Thread](./thread/) 池內部資料。這是一個由存取函式管理記憶體的單例類型。絕不應直接建立其實例。 |
| [Timer](./timer/) | [Timer](./timer/) 類別會在延遲後於獨立執行緒中執行工作項目。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。 |
| [TimerQueue](./timerqueue/) | 處理 [Timer](./timer/) 物件的佇列。這僅是一個實作。[Timer](./timer/) 物件會自行註冊於此，使用時不必自行註冊—改用 [Timer](./timer/) 類別 API。這是一個由存取函式管理記憶體的單例類型。絕不應直接建立其實例。 |
| [WaitHandle](./waithandle/) | 等待原始基底類別。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。 |

## 結構

| 結構 | 描述 |
| --- | --- |
| [Timeout](./timeout/) | [Threading](./) 超時特殊值。這是一個沒有實例服務的靜態類型。絕不應以任何方式建立其實例。 |

## 列舉

| 列舉 | 描述 |
| --- | --- |
| [ApartmentState](./apartmentstate/) | 設定執行緒的公寓狀態。 |
| [EventResetMode](./eventresetmode/) | 指示事件狀態的重設方式。 |
| [ThreadState](./threadstate/) | 執行緒的狀態。 |

## 型別別名

| 型別別名 | 描述 |
| --- | --- |
| [ThreadStateException](./threadstateexception/) |  |
| [SemaphoreFullException](./semaphorefullexception/) |  |
| [SynchronizationLockException](./synchronizationlockexception/) |  |
| [ThreadAbortException](./threadabortexception/) |  |
| [ThreadInterruptedException](./threadinterruptedexception/) |  |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | [Thread](./thread/) 僅有單一參數的函式。 |
| [ThreadStart](./threadstart/) | [Thread](./thread/) 不帶參數的函式。 |
| [WaitCallback](./waitcallback/) | 在有可用位置時執行的回呼項目。 |
| [TimerCallback](./timercallback/) | 由計時器呼叫的回呼函式。 |
| [wait_handle_t](./wait_handle_t/) | 處理常式類型。 |