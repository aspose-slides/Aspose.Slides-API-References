---
title: Thread
second_title: Aspose.Slides for C++ API 参考
description: "Thread 实现。此类的对象应仅使用 System::MakeObject() 函数进行分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 209
url: /zh/system.threading/thread/
---
## Thread 类

[Thread](./) 实现。此类的对象应仅使用 [System::MakeObject()](../../system/makeobject/) 函数进行分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class Thread : public System::Object
```

## 方法

| Method | Description |
| --- | --- |
| void [Abort](./abort/)() | 中止线程。未实现。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅用于内部目的。 |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentCulture](./get_currentculture/)() | 获取线程的文化。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Thread](./)\> [get_CurrentThread](./get_currentthread/)() | 获取描述当前线程的对象。 |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentUICulture](./get_currentuiculture/)() | 获取线程使用的用户界面文化。 |
| **bool** [get_IsAlive](./get_isalive/)() | 检查线程是否存活。 |
| **bool** [get_IsBackground](./get_isbackground/)() | 检查线程是否为后台线程。 |
| **bool** [get_IsThreadPoolThread](./get_isthreadpoolthread/)() | 检查线程是否属于线程池。 |
| int [get_ManagedThreadId](./get_managedthreadid/)() const | 获取线程的标识符。可以从操作系统获取，但如果操作系统线程标识符超过 int 限制，线程的 ID 可能会冲突。 |
| [System::String](../../system/string/) [get_Name](./get_name/)() | 获取线程名称。 |
| [ThreadState](../threadstate/) [get_ThreadState](./get_threadstate/)() | 获取线程状态。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| static int [GetCurrentThreadId](./getcurrentthreadid/)() | 获取当前线程的标识符。 |
| int [GetHashCode](./gethashcode/)() const override |  |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| void [Interrupt](./interrupt/)() | 中断线程。未实现。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示由 targetType 描述的类型的实例。相当于 C# 的 'is' 运算符。 |
| void [Join](./join/)() | 加入托管线程。如有必要，执行无限等待。 |
| **bool** [Join](./join/)(int) | 加入托管线程。执行有限等待。 |
| **bool** [Join](./join/)([TimeSpan](../../system/timespan/)) | 加入托管线程。执行有限等待。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
| static void [MemoryBarrier](./memorybarrier/)() | 同步内存访问。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的复制构造。 |
| [Thread](./)\& [operator=](./operator_equal/)(const [Thread](./)\&) | 从不同线程复制 TLS 数据。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 按引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，针对 string 与 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，针对字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [set_CurrentCulture](./set_currentculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 设置线程文化。 |
| void [set_CurrentUICulture](./set_currentuiculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 设置线程使用的用户界面文化。 |
| void [set_IsBackground](./set_isbackground/)(**bool**) | 将线程设置为后台或前台。 |
| void [set_Name](./set_name/)(const [System::String](../../system/string/)\&) | 设置线程名称。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| static void [Sleep](./sleep/)(int) | 在指定超时时间内停止当前线程。 |
| static void [Sleep](./sleep/)([TimeSpan](../../system/timespan/)) | 在指定超时时间内停止当前线程。 |
| static void [SpinWait](./spinwait/)(int) | 等待特定次数的循环迭代。 |
| void [Start](./start/)() | 使用空参数对象启动线程。 |
| void [Start](./start/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | 启动线程。 |
|  [Thread](./thread/)() | 构造函数。 |
|  [Thread](./thread/)([ThreadStart](../threadstart/)) | 构造函数。 |
|  [Thread](./thread/)([ParameterizedThreadStart](../parameterizedthreadstart/)) | 构造函数。 |
|  [Thread](./thread/)([Thread](./)\&) | 复制构造函数。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| static **bool** [Yield](./yield/)() | 让出线程。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
| virtual  [~Thread](./~thread/)() | 析构函数。 |

## 备注

```cpp
#include "system/threading/thread.h"
#include "system/smart_ptr.h"

int main()
{
  auto thread = System::MakeObject<System::Threading::Thread>([]()
  {
    std::cout << "Child thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;
    System::Threading::Thread::Sleep(200);
  });

  std::cout << "Main thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;

  thread->Start();
  thread->Join();

  return 0;
}
/*
此代码示例产生以下输出：
主线程 ID: 2
子线程 ID: 1
*/
```

## 另请参见

* 类 [Object](../../system/object/)
* 命名空间 [System::Threading](../)
* 库 [Aspose.Slides](../../)