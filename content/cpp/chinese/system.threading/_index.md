---
title: "System::Threading"
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 1002
url: /zh/system.threading/
---
## 类

| 类 | 描述 |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | 事件用于通知等待的线程，自动重置。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [CancellationToken](./cancellationtoken/) | 传播应取消操作的通知。此类提供一种在线程之间进行协作取消的机制，使一个线程能够通知其他线程取消操作。 |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | 表示取消令牌回调的注册。 |
| [CancellationTokenSource](./cancellationtokensource/) | 一个可以触发取消通知的取消令牌源。 |
| [Details_SemaphoreFullException](./details_semaphorefullexception/) |  |
| [Details_SynchronizationLockException](./details_synchronizationlockexception/) |  |
| [Details_ThreadAbortException](./details_threadabortexception/) |  |
| [Details_ThreadInterruptedException](./details_threadinterruptedexception/) |  |
| [Details_ThreadStateException](./details_threadstateexception/) |  |
| [EventWaitHandle](./eventwaithandle/) | 可发送给等待线程的事件。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Interlocked](./interlocked/) | 提供线程安全操作的 API。这是一个没有实例服务的静态类型。您绝不应以任何方式创建其实例。 |
| [ManualResetEvent](./manualresetevent/) | 用于通知等待线程且不会自动重置的事件。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Monitor](./monitor/) | 类 [Monitor](./monitor/) 提供一种同步对象访问的机制。 |
| [Mutex](./mutex/) | [Mutex](./mutex/) 实现。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Semaphore](./semaphore/) | [Semaphore](./semaphore/) 实现。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [SynchronizationContext](./synchronizationcontext/) | 提供在各种同步操作中传播同步上下文的基本功能。 |
| [Thread](./thread/) | [Thread](./thread/) 实现。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [ThreadPool](./threadpool/) | [Thread](./thread/) 池 API，允许将作业推入队列，由工作线程池读取。这是一个没有实例服务的静态类型。您绝不应以任何方式创建其实例。 |
| [ThreadPoolImpl](./threadpoolimpl/) | [Thread](./thread/) 池内部数据。这是一个由访问函数进行内存管理的单例类型。您不应直接创建其实例。 |
| [Timer](./timer/) | [Timer](./timer/) 类，在延迟后在单独的线程中执行作业项。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [TimerQueue](./timerqueue/) | 处理 [Timer](./timer/) 对象的队列。这只是一个实现。[Timer](./timer/) 对象会自行注册，无需您手动注册即可使用——请改用 [Timer](./timer/) 类 API。它是一个由访问函数进行内存管理的单例类型。您不应直接创建其实例。 |
| [WaitHandle](./waithandle/) | 等待原语基类。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |

## 结构体

| 结构体 | 描述 |
| --- | --- |
| [Timeout](./timeout/) | [Threading](./) 超时特殊值。这是一个没有实例服务的静态类型。您绝不应以任何方式创建其实例。 |

## 枚举

| 枚举 | 描述 |
| --- | --- |
| [ApartmentState](./apartmentstate/) | 设置线程的公寓状态。 |
| [EventResetMode](./eventresetmode/) | 指示事件状态的重置方式。 |
| [ThreadState](./threadstate/) | 线程的状态。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [ThreadStateException](./threadstateexception/) |  |
| [SemaphoreFullException](./semaphorefullexception/) |  |
| [SynchronizationLockException](./synchronizationlockexception/) |  |
| [ThreadAbortException](./threadabortexception/) |  |
| [ThreadInterruptedException](./threadinterruptedexception/) |  |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | [Thread](./thread/) 函数，具有单个参数。 |
| [ThreadStart](./threadstart/) | [Thread](./thread/) 函数，无参数。 |
| [WaitCallback](./waitcallback/) | 回调项，一旦有空位即执行。 |
| [TimerCallback](./timercallback/) | 由计时器调用的回调函数。 |
| [wait_handle_t](./wait_handle_t/) | 句柄类型。 |