---
title: System
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 274
url: /zh/system/
---
## 类

| 类 | 描述 |
| --- | --- |
| [Activator](./activator/) | 包含创建对象类型的方法。 |
| [Array](./array/) | 表示数组数据结构的类。此类的对象只能使用 [System::MakeArray()](./makearray/) 和 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [ArrayBase](./arraybase/) | [System.Array](./array/) 类（所有数组的抽象基类）的占位符，可根据需求填充功能。 |
| [ArraySegment](./arraysegment/) | 表示一维数组段的类型。此类型应在栈上分配，并通过值或引用传递给函数。不要使用 [System::SmartPtr](./smartptr/) 类管理此类型的对象。 |
| [Attribute](./attribute/) | 自定义属性的基类。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [BitConverter](./bitconverter/) | 包含将字节序列转换为值类型及其逆向转换的方法。此为静态类型，没有实例服务。切勿以任何方式创建其实例。 |
| [Boolean](./boolean/) | 保存 [System.Boolean](./boolean/).[Net](../system.net/) 类型静态成员的类。 |
| [BoxedEnum](./boxedenum/) | 表示装箱的枚举值。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [BoxedValue](./boxedvalue/) | 表示装箱的值。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [BoxedValue< ValueTuple< Args... > >](./boxedvalue_tmpl_valuetuple_tmpl_args_dots__end_tmpl__end_tmpl/) | 值元组的装箱版本。 |
| [BoxedValueBase](./boxedvaluebase/) | 定义接口并实现派生类（表示装箱值）的若干基础方法的基类。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Buffer](./buffer/) | 包含操作原始字节数组的方法。此为静态类型，没有实例服务。切勿以任何方式创建其实例。 |
| [Byte](./byte/) | 包含操作无符号 8 位整数的方法。 |
| [Char](./char/) | 提供对以 UTF-16 代码单元表示的字符进行操作的方法。此为静态类型，没有实例服务。切勿以任何方式创建其实例。 |
| [Comparison](./comparison/) | 表示比较同一类型两个对象的指针类型。此类型应在栈上分配，并通过值或引用传递给函数。不要使用 [System::SmartPtr](./smartptr/) 类管理此类型的对象。 |
| [Console](./console/) | 提供向标准输出流写入数据的方法。此为静态类型，没有实例服务。切勿以任何方式创建其实例。 |
| [ConsoleOutput](./consoleoutput/) | 表示标准输出流的类。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [DateTime](./datetime/) | 表示时间连续体上特定日期时间值的类型。此类型应在栈上分配，并通过值或引用传递给函数。不要使用 [System::SmartPtr](./smartptr/) 类管理此类型的对象。 |
| [DateTimeOffset](./datetimeoffset/) | 包含相对于协调世界时 (UTC) 的日期和时间。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [DBNull](./dbnull/) | 表示不存在的值。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Decimal](./decimal/) | 表示十进制数的类型。此类型应在栈上分配，并通过值或引用传递给函数。不要使用 [System::SmartPtr](./smartptr/) 类管理此类型的对象。 |
| [DefaultBoxedValue](./defaultboxedvalue/) | [BoxedValue](./boxedvalue/) 类实现。允许在不复制公共代码的情况下声明 BoxingValue 特化。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Delegate< ReturnType(ArgumentTypes...)>](./delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/) | 表示指向函数、方法或函数对象的指针。此类型应在栈上分配，并通过值或引用传递给函数。不要使用 [System::SmartPtr](./smartptr/) 类管理此类型的对象。 |
| [Details_AggregateException](./details_aggregateexception/) | 表示包含多个内部异常的异常。 |
| [Details_ApplicationException](./details_applicationexception/) | 表示应用程序（而非系统）异常的基类。请勿手动创建此类实例，请改用 ApplicationException 类。不要将 ApplicationException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_ArgumentException](./details_argumentexception/) | 当调用的方法接收到无效参数时抛出 ArgumentException。请勿手动创建此类实例，请改用 ArgumentException 类。不要将 ArgumentException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_ArgumentNullException](./details_argumentnullexception/) |  |
| [Details_ArgumentOutOfRangeException](./details_argumentoutofrangeexception/) | 当调用的方法接收到超出预期范围的参数时抛出 ArgumentOutOfRangeException。请勿手动创建此类实例，请改用 ArgumentOutOfRangeException 类。不要将 ArgumentOutOfRangeException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_ArithmeticException](./details_arithmeticexception/) | 当在执行算术、转换或强制转换操作时出现错误时抛出 ArithmeticException。请勿手动创建此类实例，请改用 ArithmeticException 类。不要将 ArithmeticException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_BadImageFormatException](./details_badimageformatexception/) | 当动态链接库 (DLL) 或可执行程序的文件映像无效时抛出此异常。请勿手动创建此类实例，请改用 BadImageFormatException 类。不要将 BadImageFormatException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_DataMisalignedException](./details_datamisalignedexception/) |  |
| [Details_DivideByZeroException](./details_dividebyzeroexception/) | 当在算术运算中尝试除以 0 时抛出 DivideByZeroException。请勿手动创建此类实例，请改用 DivideByZeroException 类。不要将 DivideByZeroException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_Exception](./details_exception/) | 表示异常。请勿手动创建此类实例，请改用 Exception 类。不要将 Exception 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_ExceptionWithErrorCode](./details_exceptionwitherrorcode/) | 带错误代码的异常的模板类。 |
| [Details_ExceptionWithFilename](./details_exceptionwithfilename/) | 带文件名的异常的模板类。 |
| [Details_ExecutionEngineException](./details_executionengineexception/) | ExecutionEngineException 仅为兼容性保留。 |
| [Details_FormatException](./details_formatexception/) | 当方法参数的格式无效时抛出 FormatException。请勿手动创建此类实例，请改用 FormatException 类。不要将 FormatException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_IndexOutOfRangeException](./details_indexoutofrangeexception/) | 当使用超出集合边界的索引访问元素时抛出 IndexOutOfRangeException。请勿手动创建此类实例，请改用 IndexOutOfRangeException 类。不要将 IndexOutOfRangeException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_InvalidCastException](./details_invalidcastexception/) | 当执行无效的显式转换时抛出 InvalidCastException。请勿手动创建此类实例，请改用 InvalidCastException 类。不要将 InvalidCastException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_InvalidOperationException](./details_invalidoperationexception/) | 当在状态与调用不一致的对象上调用方法时抛出 InvalidOperationException。请勿手动创建此类实例，请改用 InvalidOperationException 类。不要将 InvalidOperationException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_InvalidProgramException](./details_invalidprogramexception/) | InvalidProgramException 仅为兼容性保留。请勿手动创建此类实例，请改用 InvalidProgramException 类。不要将 InvalidProgramException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_InvalidTimeZoneException](./details_invalidtimezoneexception/) | 当时区信息无效时抛出 InvalidTimeZoneException。请勿手动创建此类实例，请改用 InvalidTimeZoneException 类。不要将 InvalidTimeZoneException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_MemberAccessException](./details_memberaccessexception/) | 当访问不存在的类成员或无权限访问成员时抛出 MemberAccessException。请勿手动创建此类实例，请改用 MemberAccessException 类。不要将 MemberAccessException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_MethodAccessException](./details_methodaccessexception/) | 当访问不存在的方法或无权限访问方法时抛出 MethodAccessException。请勿手动创建此类实例，请改用 MethodAccessException 类。不要将 MethodAccessException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_NotImplementedException](./details_notimplementedexception/) | 当调用未实现的方法（存根）时抛出 NotImplementedException。请勿手动创建此类实例，请改用 NotImplementedException 类。不要将 NotImplementedException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_NotSupportedException](./details_notsupportedexception/) | 当调用不受支持的方法或对流执行不支持的操作时抛出 NotSupportedException。请勿手动创建此类实例，请改用 NotSupportedException 类。不要将 NotSupportedException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_NullReferenceException](./details_nullreferenceexception/) | 当尝试对空引用进行解引用时抛出 NullReferenceException。请勿手动创建此类实例，请改用 NullReferenceException 类。不要将 NullReferenceException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_ObjectDisposedException](./details_objectdisposedexception/) | 当在已释放的对象上调用方法时抛出 ObjectDisposedException。请勿手动创建此类实例，请改用 ObjectDisposedException 类。不要将 ObjectDisposedException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_OperationCanceledException](./details_operationcanceledexception/) | 当线程在操作被取消时抛出 OperationCanceledException。请勿手动创建此类实例，请改用 OperationCanceledException 类。不要将 OperationCanceledException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_OutOfMemoryException](./details_outofmemoryexception/) |  |
| [Details_OverflowException](./details_overflowexception/) | 当操作导致溢出时抛出 OverflowException。请勿手动创建此类实例，请改用 OverflowException 类。不要将 OverflowException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_PlatformNotSupportedException](./details_platformnotsupportedexception/) | 当功能在特定平台上不可运行时抛出 PlatformNotSupportedException。请勿手动创建此类实例，请改用 PlatformNotSupportedException 类。不要将 PlatformNotSupportedException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_RankException](./details_rankexception/) | 当向方法传递维度数与预期不同的数组时抛出 RankException。请勿手动创建此类实例，请改用 RankException 类。不要将 RankException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_StackOverflowException](./details_stackoverflowexception/) | 当线程的执行栈溢出时抛出 StackOverflowException。请勿手动创建此类实例，请改用 StackOverflowException 类。不要将 StackOverflowException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_SystemException](./details_systemexception/) | 表示系统（而非应用程序）异常的基类。请勿手动创建此类实例，请改用 SystemException 类。不要将 SystemException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_TimeoutException](./details_timeoutexception/) | 当为进程或操作分配的时间已到期时抛出 TimeoutException。请勿手动创建此类实例，请改用 TimeoutException 类。不要将 TimeoutException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_TimeZoneNotFoundException](./details_timezonenotfoundexception/) | 当未找到时区信息时抛出 TimeZoneNotFoundException。请勿手动创建此类实例，请改用 TimeZoneNotFoundException 类。不要将 TimeZoneNotFoundException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_TypeInitializationException](./details_typeinitializationexception/) |  |
| [Details_UnauthorizedAccessException](./details_unauthorizedaccessexception/) | 当因 I/O 错误或安全错误导致操作系统拒绝访问时抛出 UnauthorizedAccessException。请勿手动创建此类实例，请改用 UnauthorizedAccessException 类。不要将 UnauthorizedAccessException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Details_UriFormatException](./details_uriformatexception/) | 当 URI 格式无效时抛出 UriFormatException。请勿手动创建此类实例，请改用 UriFormatException 类。不要将 UriFormatException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [DynamicWeakPtr](./dynamicweakptr/) | 追踪存储对象模板参数指针模式并在每次赋值后更新的智能指针类。此类型用于管理其他对象的删除。应在栈上分配，并通过值或 const 引用传递给函数。 |
| [EnumValues](./enumvalues/) | 提供枚举类型 **E** 的枚举常量的元信息。 |
| [EnumValuesBase](./enumvaluesbase/) | 表示枚举类型元信息的基类。 |
| [EventArgs](./eventargs/) | 为在触发事件时传递给订阅者的上下文的基类。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [ExceptionWrapper](./exceptionwrapper/) | 表示从 Exception 类派生的异常包装器的模板。 |
| [FlagsAttribute](./flagsattribute/) | 表示枚举可以视为位字段（即集合）。 |
| [Func](./func/) | 函数委托。此类型应在栈上分配，并通过值或引用传递给函数。不要使用 [System::SmartPtr](./smartptr/) 类管理此类型的对象。 |
| [GC](./gc/) | 代表一个模拟的垃圾回收器，实际上什么也不做。此为静态类型，没有实例服务。切勿以任何方式创建其实例。 |
| [Guid](./guid/) | 表示全局唯一标识符 (GUID)。此类型应在栈上分配，并通过值或引用传递给函数。不要使用 [System::SmartPtr](./smartptr/) 类管理此类型的对象。 |
| [IAsyncResult](./iasyncresult/) | 表示异步操作的状态。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [ICloneable](./icloneable/) | 定义启用对象克隆（创建对象副本）的方法。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [IComparable](./icomparable/) | 定义比较两个对象的方法。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [IConvertible](./iconvertible/) | 定义将实现该接口或值类型的值转换为等效 CLR 类型的方法。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [ICustomFormatter](./icustomformatter/) | 定义对指定对象的值进行自定义格式化的字符串表示的方法。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [IDisposable](./idisposable/) | 定义释放当前对象拥有的资源的方法。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [IEquatable](./iequatable/) | 定义判断两个对象相等的方法。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [IFormatProvider](./iformatprovider/) | 定义提供格式信息的方法。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [IFormattable](./iformattable/) | 定义使用指定格式字符串和格式提供程序格式化当前对象值的方法。 |
| [Int16](./int16/) | 包含操作 16 位整数的方法。 |
| [Int32](./int32/) | 包含操作 32 位整数的方法。 |
| [Int64](./int64/) | 包含操作 64 位整数的方法。 |
| [LockContext](./lockcontext/) | 实现 C# lock() 语句的守卫对象。 |
| [MarshalByRefObject](./marshalbyrefobject/) | 提供跨应用程序域边界访问对象的功能（用于启用远程的应用）。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [MulticastDelegate< ReturnType(ArgumentTypes...)>](./multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/) | 表示委托集合的类型。此类型应在栈上分配，并通过值或引用传递给函数。不要使用 [System::SmartPtr](./smartptr/) 类管理此类型的对象。 |
| [Nullable](./nullable/) | 前向声明。 |
| [NullableUtils](./nullableutils/) | 表示 C# [System.Nullable](./nullable/)（无类型参数）的静态类。因 C++ 不支持类模板重载，无法使用原名。支持可赋值 null 的值类型。此类不可继承。 |
| [Object](./object/) | 允许在 C# 中使用 [System.Object](./object/) 类的可用方法的基类。所有在已翻译环境中使用的非平凡类都应继承它。 |
| [ObjectExt](./objectext/) | 提供模拟 C# [Object](./object/) 方法（针对非对象 C++ 类型，如字符串、数字等）的静态方法。此为静态类型，没有实例服务。切勿以任何方式创建其实例。 |
| [ObjectType](./objecttype/) | 提供实现对象类型获取器的静态方法。此为静态类型，没有实例服务。切勿以任何方式创建其实例。 |
| [OperatingSystem](./operatingsystem/) | 表示特定操作系统并提供其相关信息的类。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Random](./random/) | 表示伪随机数生成器的类。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [ReadOnlySpan](./readonlyspan/) | 在 [Span](./span/) 类内部使用的前向引用。 |
| [ScopedCulture](./scopedculture/) | 表示在作用域内使用的文化信息。 |
| [SmartPtr](./smartptr/) | 用于包装在堆上分配的类型的指针类。用于管理继承 [Object](./object/) 的类的内存。此指针类型遵循侵入式指针语义。引用计数要么存储在 [Object](./object/) 本身，要么存储在与 [Object](./object/) 实例紧密关联的计数结构中。无论创建方式如何，所有 [SmartPtr](./smartptr/) 实例都形成单一所有权组，这与 std::shared_ptr 的行为不同。将原始指针转换为 [SmartPtr](./smartptr/) 是安全的，因为还有其他 [SmartPtr](./smartptr/) 实例持有对同一对象的共享引用。[SmartPtr](./smartptr/) 类实例可以是共享指针或弱指针两种状态之一。要保持对象存活，需要保证其共享引用计数为正。共享指针和弱指针都可用于访问指向的对象（调用方法、读取或写入字段等），但弱指针不参与共享指针的引用计数。当最后一个 “shared” [SmartPtr](./smartptr/) 指针被销毁时，[Object](./object/) 将被删除。因此，请确保在没有其他共享 [SmartPtr](./smartptr/) 指针存在时（例如对象构造或析构期间）不要发生此情况。使用 System::Object::ThisProtector 监护对象（在 C++ 代码中）或 CppCTORSelfReference / CppSelfReference 属性（在 C# 代码中）来修复此问题。类似地，使用 [System::WeakPtr](./weakptr/) 指针类或 [System::SmartPtrMode::Weak](./smartptrmode/) 指针模式（在 C++ 代码中）或 CppWeakPtr 属性（在 C# 代码中）来打破循环引用。如果两个或更多对象相互引用共享指针，它们将永远不会被删除。若需要在运行时切换指针类型（弱或共享），请使用 [System::SmartPtr<T>::set_Mode()](./smartptr/set_mode/) 方法或 [System::DynamicWeakPtr](./dynamicweakptr/) 类。[SmartPtr](./smartptr/) 类不包含任何虚函数。仅在实现自定义内存管理策略时才应继承它。此类型是用于管理其他对象删除的指针。应在栈上分配，并通过值或 const 引用传递给函数。 |
| [SmartPtrInfo](./smartptrinfo/) | 用于在不知最终类型的情况下测试和修改 [SmartPtr](./smartptr/) 内容的服务类。用于垃圾回收和循环引用检测等。可以视作 “指向指针”。我们不能使用 [SmartPtr](./smartptr/) 的基类型，因为它没有任何；因此使用此 “info” 类。 |
| [Span](./span/) | 表示类似 C++20 std::span 的连续任意内存区域。 |
| [String](./string/) | [String](./string/) 类在整个库中使用。是 C# [System.String](./string/) 在代码翻译中的替代品。出于优化原因，不被视为 [Object](./object/) 子类。此类型应在栈上分配，并通过值或引用传递给函数。不要使用 [System::SmartPtr](./smartptr/) 类管理此类型的对象。 |
| [StringComparer](./stringcomparer/) | 使用不同比较模式比较字符串。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [StringHashCompiletime](./stringhashcompiletime/) | 生成 c-string 哈希值的辅助类。 |
| [TimeSpan](./timespan/) | 表示时间间隔的类型。此类型应在栈上分配，并通过值或引用传递给函数。不要使用 [System::SmartPtr](./smartptr/) 类管理此类型的对象。 |
| [TimeZone](./timezone/) | 表示时区的类型。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [TimeZoneInfo](./timezoneinfo/) | 表示特定时区信息的描述。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Tuple](./tuple/) | 表示元组数据结构的类。最大元素数量为 8。 |
| [TupleFactory](./tuplefactory/) | 提供创建元组对象的静态方法。 |
| [TypeInfo](./typeinfo/) | 表示特定类型并提供其信息的类。 |
| [Uri](./uri/) | 统一资源标识符（URI）。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [UriBuilder](./uribuilder/) | 提供构造和修改通用资源标识符（URI）的方法。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [UriParser](./uriparser/) | 用于解析新 URI 方案的类。此类的对象只能使用 [System::MakeObject()](./makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](./smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [UriShim](./urishim/) | 服务类。 |
| [ValueTuple](./valuetuple/) | 表示 [ValueTuple](./valuetuple/) 数据结构的类。 |
| [ValueType](./valuetype/) | 为具有 [Object](./object/) 继承的值类型提供基类，以性能为考虑进行截断。此类型应在栈上分配，并通过值或引用传递给函数。不要使用 [System::SmartPtr](./smartptr/) 类管理此类型的对象。 |
| [Version](./version/) | 表示版本号。此类型应在栈上分配，并通过值或引用传递给函数。不要使用 [System::SmartPtr](./smartptr/) 类管理此类型的对象。 |
| [Void](./void/) |  |
| [WeakPtr](./weakptr/) | [System::SmartPtr](./smartptr/) 的子类，在构造时自动设置为弱模式。请注意，此类不能保证其实例在整个生命周期中始终保持弱模式，因为 [set_Mode()](./smartptr/set_mode/) 仍然可访问。此类型是用于管理其他对象删除的指针。应在栈上分配，并通过值或 const 引用传递给函数。 |
| [WeakReference< T >](./weakreference_tmpl_t__end_tmpl/) | 表示弱引用，引用对象的同时仍允许该对象被删除。 |
| [WeakReference<>](./weakreference_tmpl_end_tmpl/) | 表示弱引用，引用对象的同时仍允许该对象被删除。 |
## 结构体

| 结构体 | 描述 |
| --- | --- |
| [CastResult](./castresult/) | 用于推断 cast 结果的模板技巧。 |
| [CollectionAssertHelper](./collectionasserthelper/) | 用于集合相关操作的帮助 API。 |
| [Convert](./convert/) | 包含执行一种类型到另一种类型值转换的方法的结构体。此类型应在栈上分配，并通过值或引用传递给函数。不要使用 [System::SmartPtr](./smartptr/) 类管理此类型的对象。 |
| [Double](./double/) | 包含操作双精度浮点数的方法。 |
| [Enum](./enum/) | 提供对枚举类型值执行某些操作的方法。此为静态类型，没有实例服务。切勿以任何方式创建其实例。 |
| [EnumGetNameHelper](./enumgetnamehelper/) | 提供获取枚举常量字符串名称功能的帮助类。 |
| [EnumParseHelper](./enumparsehelper/) | 提供将枚举常量的字符串表示转换为等价枚举值功能的帮助类。 |
| [Environment](./environment/) | [Environment](./environment/) 服务。此为静态类型，没有实例服务。切勿以任何方式创建其实例。 |
| [HolderInitializer](./holderinitializer/) | 用于获取对象实例的持久引用（无论是左值还是右值）。要获得此类引用，请使用 `HoldIfTemporary` 方法，其有三种重载。两者接受右值并返回对其的引用。第三个接受左值，制作指针副本后返回对该副本的引用。此外，类还有 `Hold` 方法，可无条件持有传入值（用于复制局部栈变量或其子引用）。 |
| [HolderInitializer< T, false >](./holderinitializer_tmpl_t__false__end_tmpl/) | [HolderInitializer](./holderinitializer/) 对 T 为值类型时的特化。使用场景允许返回对临时对象的引用，因为实例会被调用者复制。因此，此特化仅作存根，不执行任何操作。 |
| [IsBoxable](./isboxable/) | 检查指定类型是否支持装箱的模板谓词。 |
| [IsExceptionWrapper](./isexceptionwrapper/) | 判断指定类型是否为 Exception 类或其子类的模板谓词。 |
| [IsNullable](./isnullable/) | 判断模板参数 T 是否为 [Nullable](./nullable/) 或其子类的模板谓词。 |
| [IsSmartPtr](./issmartptr/) | 检查类型是否为 [SmartPtr](./smartptr/) 类特化的特征类。 |
| [IsStringByteSequence](./isstringbytesequence/) | 检查类型是否为字符序列的模板技巧。 |
| [IsStringLiteral](./isstringliteral/) | 检查类型是否为字符串字面量的模板技巧。 |
| [IsStringPointer](./isstringpointer/) | 检查类型是否为指向字符字符串的指针的模板技巧。 |
| [IsWeakPtr](./isweakptr/) | 检查特定类是否为 [System::WeakPtr](./weakptr/) 特化的特征类。不检查实例是否实际处于弱模式。 |
| [MakeConstRef](./makeconstref/) | 当类型为 [String](./string/) 或 SmartPtr<> 时，将泛型类型转换为 “const 引用”。 |
| [Math](./math/) | 包含数学函数。此为静态类型，没有实例服务。切勿以任何方式创建其实例。 |
| [MathF](./mathf/) | 包含单精度浮点数的数学函数。此为静态类型，没有实例服务。切勿以任何方式创建其实例。 |
| [MethodArgumentTuple< R(*)(Args...)>](./methodargumenttuple_tmpl_r_lbrace__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/) | 定义用于存储方法参数的元组。 |
| [MethodArgumentTuple< R(C::*)(Args...) const >](./methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__const__end_tmpl/) | 定义用于存储方法参数的元组。 |
| [MethodArgumentTuple< R(C::*)(Args...)>](./methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/) | 定义用于存储方法参数的元组。 |
| [MulticastDelegateTypeInfo](./multicastdelegatetypeinfo/) | 表示指向包含 MulticastDelegate 类信息的 [TypeInfo](./typeinfo/) 对象的指针。 |
| [RemoveShared](./removeshared/) | 用于从参数类型中移除 SharedPtr/WeakPtr 的特征结构体。 |
| [SByte](./sbyte/) | 包含操作 8 位整数的方法。 |
| [ScopeGuard](./scopeguard/) | 在对象超出作用域时运行特定函数对象的服务类。 |
| [Single](./single/) | 包含操作单精度浮点数的方法。 |
| [TestCompare](./testcompare/) | 提供比较集合的接口的服务结构体。 |
| [TestTools](./testtools/) | 提供检查不同类型和函数的一组有用方法。 |
| [TestToolsExt](./testtoolsext/) | 用于测试翻译的通用函数。 |
| [TypeInfoPtr](./typeinfoptr/) | 包装指向 [TypeInfo](./typeinfo/) 类实例的指针的类。此类型应在栈上分配，并通过值或引用传递给函数。不要使用 [System::SmartPtr](./smartptr/) 类管理此类型的对象。 |
| [UInt16](./uint16/) | 包含操作无符号 16 位整数的方法。 |
| [UInt32](./uint32/) | 包含操作无符号 32 位整数的方法。 |
| [UInt64](./uint64/) | 包含操作无符号 64 位整数的方法。 |
| [ValueTupleTypeInfo](./valuetupletypeinfo/) | 表示指向包含 [TypeInfo](./typeinfo/) 对象信息的 [ValueTuple](./valuetuple/) 类的指针。 |
| [WeakPtrFromTypeParameter](./weakptrfromtypeparameter/) | 将参数类型转换为弱指针的特征结构体（如果它本身是指针类型）。 |
## 函数

| 函数 | 描述 |
| --- | --- |
| [ArrayPtr](./arrayptr/)\<T\> [MakeArray](./makearray/)(std::initializer_list\<T\>) | 工厂函数，构造新 [Array](./array/) 对象，用指定的初始化列表中的元素填充它，并返回指向 [Array](./array/) 对象的智能指针。 |
| [ArrayPtr](./arrayptr/)\<T\> [MakeArray](./makearray/)(Args\&&...) | 工厂函数，构造新 [Array](./array/) 对象，并将指定参数传递给其构造函数。 |
| std::enable_if\<std::is_integral\<Integral\>::value, [ArrayPtr](./arrayptr/)\<T\>\>::type [MakeArray](./makearray/)(Integral, Args\&&...) | 工厂函数，构造新 [Array](./array/) 对象，并将指定参数传递给其构造函数。 |
| **bool** [operator==](./operator_equal_equal/)([ArraySegment](./arraysegment/)\<T\>, [ArraySegment](./arraysegment/)\<T\>) |  |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 判断指定 [Nullable](./nullable/) 对象是否等于 null。 |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 通过对这两个值应用 [operator==()](./operator_equal_equal/)，判断指定值是否等于指定 [Nullable](./nullable/) 对象表示的值。 |
| **bool** [operator==](./operator_equal_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const [SmartPtr](./smartptr/)\<Y\>\&) | 对两个智能指针进行相等比较。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [SmartPtr](./smartptr/)\<X\> const\&) | 检查智能指针是否为 null。 |
| std::enable_if\<std::is_base_of\<[Object](./object/), Y\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const Y *) | 将智能指针与普通 (C) 指针进行相等比较。 |
| std::enable_if\<std::is_base_of\<[Object](./object/), X\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const X *, const [SmartPtr](./smartptr/)\<Y\>\&) | 将智能指针与普通 (C) 指针进行相等比较。 |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\!std::is_pointer\<T\>::value\&&\!std::is_array\<T\>::value\&&detail::has_method_is_null\<T\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(T const\&, std::nullptr_t) | 检查值类型对象（翻译的 C# 结构体等）是否为 null。 |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\!std::is_pointer\<T\>::value\&&\!std::is_array\<T\>::value\&&detail::has_method_is_null\<T\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(std::nullptr_t, T const\&) | 检查值类型对象（翻译的 C# 结构体等）是否为 null。 |
| **bool** [operator==](./operator_equal_equal/)(Chars\&, const [String](./string/)\&) | [String](./string/) 比较。 |
| **bool** [operator==](./operator_equal_equal/)(T\&, const [String](./string/)\&) | [String](./string/) 比较。 |
| **bool** [operator==](./operator_equal_equal/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, const [String](./string/)\&) | [Object](./object/) 与字符串比较。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [String](./string/)\&) | 检查字符串是否为 null。 |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| **bool** [operator==](./operator_equal_equal/)(const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&, const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&) | 判断当前对象和指定对象表示的 URI 是否相等。 |
| **bool** [operator!=](./operator_not_equal/)([ArraySegment](./arraysegment/)\<T\>, [ArraySegment](./arraysegment/)\<T\>) |  |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 判断指定 [Nullable](./nullable/) 对象是否不等于 null。 |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 通过对这两个值应用 [operator!=()](./operator_not_equal/)，判断指定值是否不等于指定 [Nullable](./nullable/) 对象表示的值。 |
| **bool** [operator!=](./operator_not_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const [SmartPtr](./smartptr/)\<Y\>\&) | 对两个智能指针进行非相等比较。 |
| **bool** [operator!=](./operator_not_equal/)([SmartPtr](./smartptr/)\<X\> const\&, std::nullptr_t) | 检查智能指针是否不为 null。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [SmartPtr](./smartptr/)\<X\> const\&) | 检查智能指针是否不为 null。 |
| std::enable_if\<std::is_base_of\<[Object](./object/), Y\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const Y *) | 将智能指针与普通 (C) 指针进行不等比较。 |
| std::enable_if\<std::is_base_of\<[Object](./object/), X\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const X *, const [SmartPtr](./smartptr/)\<Y\>\&) | 将智能指针与普通 (C) 指针进行相等比较。 |
| **bool** [operator!=](./operator_not_equal/)(Chars\&, const [String](./string/)\&) | [String](./string/) 比较。 |
| **bool** [operator!=](./operator_not_equal/)(T\&, const [String](./string/)\&) | [String](./string/) 比较。 |
| **bool** [operator!=](./operator_not_equal/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, const [String](./string/)\&) | [Object](./object/) 与字符串比较。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [String](./string/)\&) | 检查字符串是否为 null。 |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| **bool** [operator!=](./operator_not_equal/)(const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&, const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&) | 判断当前对象和指定对象表示的 URI 是否不相等。 |
| static **bool** [IsEnumMetaInfoDefined](./isenummetainfodefined/)(T) |  |
| static **bool** [IsEnumMetaInfoDefined](./isenummetainfodefined/)(T) |  |
| static [System::String](./string/) [EnumGetName](./enumgetname/)(T) |  |
| static [System::String](./string/) [EnumGetName](./enumgetname/)(T) |  |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator<](./operator_less/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 始终返回 false。 |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 通过对这两个值应用 [operator<()](./operator_less/)，判断指定值是否小于指定 [Nullable](./nullable/) 对象表示的值。 |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 始终返回 false。 |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 通过对这两个值应用 [operator<=()](./operator_less_equal/)，判断指定值是否小于等于指定 [Nullable](./nullable/) 对象表示的值。 |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator>](./operator_greater/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 始终返回 false。 |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 通过对这两个值应用 [operator>()](./operator_greater/)，判断指定值是否大于指定 [Nullable](./nullable/) 对象表示的值。 |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 始终返回 false。 |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 通过对这两个值应用 [operator>=()](./operator_greater_equal/)，判断指定值是否大于等于指定 [Nullable](./nullable/) 对象表示的值。 |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| void [PrintTo](./printto/)([DateTime](./datetime/), std::ostream *) | 将值打印到 ostream。主要用于调试。 |
| void [PrintTo](./printto/)([DateTimeOffset](./datetimeoffset/), std::ostream *) | 将值打印到 ostream。主要用于调试。 |
| void [PrintTo](./printto/)(const [Decimal](./decimal/)\&, ::std::ostream *) | 将指定对象表示的值写入指定输出流。 |
| void [PrintTo](./printto/)(const [Details_Exception](./details_exception/)\&, std::ostream *) | 将值打印到 ostream。主要用于调试。 |
| void [PrintTo](./printto/)(const [ExceptionWrapper](./exceptionwrapper/)\<T\>\&, std::ostream *) | 将值打印到 ostream。主要用于调试。 |
| void [PrintTo](./printto/)(const [Guid](./guid/)\&, std::ostream *) | 将值打印到 ostream。主要用于调试。 |
| void [PrintTo](./printto/)(const [Nullable](./nullable/)\<T\>\&, std::ostream *) | 将值打印到 ostream。主要用于调试。 |
| void [PrintTo](./printto/)(const [System::Object](./object/)\&, std::ostream *) | 将值打印到 ostream。主要用于调试。 |
| std::enable_if_t\<detail::has_print_to_function\<T\>::value, void\> [PrintTo](./printto/)(const [SmartPtr](./smartptr/)\<T\>\&, std::ostream *) | 将值打印到 ostream。主要用于调试。 |
| std::enable_if_t<\!detail::has_print_to_function\<T\>::value, void\> [PrintTo](./printto/)(const [SmartPtr](./smartptr/)\<T\>\&, std::ostream *) | 将值打印到 ostream。主要用于调试。 |
| void [PrintTo](./printto/)(const [System::String](./string/)\&, std::ostream *) | 将字符串打印到 ostream。主要用于调试。 |
| void [PrintTo](./printto/)([TimeSpan](./timespan/), std::ostream *) | 将值打印到 ostream。主要用于调试。 |
| void [PrintTo](./printto/)(const [WeakPtr](./weakptr/)\<T\>\&, std::ostream *) | 将值打印到 ostream。主要用于调试。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [DateTime](./datetime/)) | 使用 UTF-8 编码将数据插入流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [DateTime](./datetime/)) | 将数据插入宽字符流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [DateTimeOffset](./datetimeoffset/)) | 使用 UTF-8 编码将数据插入流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [DateTimeOffset](./datetimeoffset/)) | 将数据插入宽字符流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Decimal](./decimal/)\&) | 使用 UTF-8 编码将数据插入流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Decimal](./decimal/)\&) | 将数据插入宽字符流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Exception](./exception/)\&) | 使用 UTF-8 编码将数据插入流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Exception](./exception/)\&) | 将数据插入宽字符流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Guid](./guid/)\&) | 使用 UTF-8 编码将数据插入流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Guid](./guid/)\&) | 将数据插入宽字符流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Nullable](./nullable/)\<T\>\&) | 使用 UTF-8 编码将数据插入流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Nullable](./nullable/)\<T\>\&) | 将数据插入宽字符流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [System::Object](./object/)\&) | 使用 UTF-8 编码将数据插入流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [System::Object](./object/)\&) | 将数据插入宽字符流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [OperatingSystem](./operatingsystem/)\&) | 使用 UTF-8 编码将数据插入流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [OperatingSystem](./operatingsystem/)\&) | 将数据插入宽字符流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [SharedPtr](./sharedptr/)\<T\>\&) | 使用 UTF-8 编码将数据插入流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [SharedPtr](./sharedptr/)\<T\>\&) | 将数据插入宽字符流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [String](./string/)\&) | 使用 UTF-8 编码将字符串输出到输出流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [String](./string/)\&) | 将字符串输出到宽字符流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [TimeSpan](./timespan/)) | 使用 UTF-8 编码将数据插入流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [TimeSpan](./timespan/)) | 将数据插入宽字符流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [TypeInfo](./typeinfo/)\&) | 使用 UTF-8 编码将数据插入流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [TypeInfo](./typeinfo/)\&) | 将数据插入宽字符流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Version](./version/)\&) | 使用 UTF-8 编码将数据插入流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Version](./version/)\&) | 将数据插入宽字符流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [WeakPtr](./weakptr/)\<T\>\&) | 使用 UTF-8 编码将数据插入流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [WeakPtr](./weakptr/)\<T\>\&) | 将数据插入宽字符流。 |
| auto [operator-](./operator_minus/)([DayOfWeek](./dayofweek/), [DayOfWeek](./dayofweek/)) | 计算两天之间的天数。 |
| [Decimal](./decimal/) [operator-](./operator_minus/)(const T\&, const [Decimal](./decimal/)\&) | 返回一个新的 [Decimal](./decimal/) 实例，表示从指定 [Decimal](./decimal/) 对象表示的值中减去指定值的结果。 |
| MulticastDelegate\<T\> [operator-](./operator_minus/)(MulticastDelegate\<T\>, MulticastDelegate\<T\>) | 将右侧委托的所有回调从左侧委托回调列表的末端断开。 |
| auto [operator-](./operator_minus/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 对非可空和可空值执行减法。 |
| [Decimal](./decimal/) [operator+](./operator_plus/)(const T\&, const [Decimal](./decimal/)\&) | 返回一个新的 [Decimal](./decimal/) 实例，表示指定值与指定 [Decimal](./decimal/) 对象表示的值之和。 |
| MulticastDelegate\<T\> [operator+](./operator_plus/)(MulticastDelegate\<T\>, MulticastDelegate\<T\>) | 将右侧委托的所有回调连接到左侧委托回调列表的末端。 |
| auto [operator+](./operator_plus/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 对非可空和可空值执行求和。 |
| std::enable_if\<[IsStringLiteral](./isstringliteral/)\<T, char_t\>::value, [String](./string/)\>::type [operator+](./operator_plus/)(T\&, const [String](./string/)\&) | [String](./string/) 连接。 |
| std::enable_if\<[IsStringPointer](./isstringpointer/)\<T, char_t\>::value, [String](./string/)\>::type [operator+](./operator_plus/)(T\&, const [String](./string/)\&) | [String](./string/) 连接。 |
| [String](./string/) [operator+](./operator_plus/)(const char_t, const [String](./string/)\&) | [String](./string/) 连接。 |
| [Decimal](./decimal/) [operator*](./operator_star/)(const T\&, const [Decimal](./decimal/)\&) | 返回一个新的 [Decimal](./decimal/) 实例，表示指定值与指定 [Decimal](./decimal/) 对象表示的值的乘积。 |
| [Decimal](./decimal/) [operator/](./operator_div/)(const T\&, const [Decimal](./decimal/)\&) | 返回一个新的 [Decimal](./decimal/) 实例，表示指定值与指定 [Decimal](./decimal/) 对象表示的值的除法结果。 |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, constT\&\>::type [Default](./default/)() | 返回异常类型单例（默认构造）的引用。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, constT\&\>::type [Default](./default/)() | 返回非异常类型单例（默认构造）的引用。 |
| T\& [Discard](./discard/)(T\&&) | 返回指定类型的默认构造临时实例，可用于替代丢弃的 '_' 参数。 |
| Details::ObjectBuilder\<T, [SharedPtr](./sharedptr/)\<T\>\> [BuildObject](./buildobject/)(Args\&&...) | 构建具有共享所有权的对象。 |
| Details::ObjectBuilder\<T, [SharedPtr](./sharedptr/)\<T\>\> [InitObject](./initobject/)(const [SharedPtr](./sharedptr/)\<T\>\&) | 开始初始化具有共享所有权的对象。 |
| Details::ObjectBuilder\<Details::ArrayStorage\<T\>\> [BuildArray](./buildarray/)() | 构建数组。 |
| Details::ObjectBuilder\<T\> [Build](./build/)(Args\&&...) | 构建具有直接所有权的对象。 |
| **bool** [Is](./is/)(const ExpressionT\&, ResultT\&) | 实现 “is” 声明模式的翻译。 |
| std::enable_if_t<\!std::is_base_of\<Details::Pattern, ConstantT\>::value, **bool**\> [Is](./is/)(const ExpressionT\&, const ConstantT\&) | 实现 “is” 常量模式的翻译。 |
| std::enable_if_t\<std::is_base_of\<Details::Pattern, A\>::value, **bool**\> [Is](./is/)(const E\&, const A\&) | 顶层匹配函数。将模式应用于值。 |
| **bool** [Less](./less/)(const ExpressionT\&, const ConstantT\&) | 实现 “<” 相对模式的翻译。 |
| **bool** [Greater](./greater/)(const ExpressionT\&, const ConstantT\&) | 实现 “>” 相对模式的翻译。 |
| **bool** [LEqual](./lequal/)(const ExpressionT\&, const ConstantT\&) | 实现 “<=” 相对模式的翻译。 |
| **bool** [GEqual](./gequal/)(const ExpressionT\&, const ConstantT\&) | 实现 “>=” 相对模式的翻译。 |
| **bool** [Set](./set/)(ExpressionT\&, const ExpressionT\&) | 实现 “var” 模式的翻译。 |
| **bool** [IsTuple](./istuple/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, **int32_t**) | 检查对象是否为元组（实现 ITuple 接口）。用于位置模式实现。 |
| auto [Get](./get/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&) | 获取给定元组的第 N 个元素的函数（基对象重载）。 |
| auto [Get](./get/)(const T\&) | 获取给定元组的第 N 个元素的函数（具有 Deconstruct 方法的对象重载）。 |
| auto [Get](./get/)(const [SharedPtr](./sharedptr/)\<T\>\&) | 获取给定元组的第 N 个元素的函数（共享指针重载）。 |
| auto [Get](./get/)(const [ValueTuple](./valuetuple/)\<Args...\>\&) | 获取值元组的第 N 个元素。 |
| [SharedPtr](./sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<T\>\> [MakeYieldEnumerable](./makeyieldenumerable/)(const Details::YieldFunction\<T\>\&) | 从 yield 函数创建 IEnumerable。 |
| [SharedPtr](./sharedptr/)\<[Collections::Generic::IEnumerator](../system.collections.generic/ienumerator/)\<T\>\> [MakeYieldEnumerator](./makeyieldenumerator/)(const Details::YieldFunction\<T\>\&) | 从 yield 函数创建 IEnumerator。 |
| std::enable_if_t\<Details::is_lambda_void_void\<T\>::value\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | 模拟 C# try[-catch]-finally 行为的单一函数。翻译 C# try[-catch]-finally 语句时（开启 finally_statement_as_lambda 选项），该语句会被翻译为调用此方法。 |
| std::enable_if_t\<Details::is_lambda_void_boolref\<T\>::value, **bool**\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | 同上，但函数对象返回 bool。 |
| std::enable_if_t\<Details::is_lambda_nonovoid_boolref\<T\>::value, std::optional\<Details::ResultOf\<T, **bool**\&\>\>\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | 同上，但返回 bool 引用的 optional。 |
| [DynamicWeakPtr](./dynamicweakptr/)\<T, trunkMode, weakLeafs...\>::Reference [Ref](./ref/)([DynamicWeakPtr](./dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\&) | 创建对 [DynamicWeakPtr](./dynamicweakptr/) 对象的引用。用于翻译器在按引用传递函数参数时。 |
| T\& [Ref](./ref/)(T\&) | 获取对象引用的帮助函数。用于保证 [System::DynamicWeakPtr](./dynamicweakptr/) 在赋值后更新被引用对象。 |
| std::enable_if_t<\!Details::IsIterable\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, T\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | 将不可遍历的对象包装为可用于基于范围的 for 循环的适配器（带目标类型参数）。 |
| std::enable_if_t<\!Details::IsIterable\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | 将不可遍历的对象包装为可用于基于范围的 for 循环的适配器（默认目标类型）。 |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value, [System::SmartPtr](./smartptr/)\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | 将可遍历对象包装为可用于基于范围的 for 循环的适配器（默认目标类型）。 |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value\&&std::is_same\<typename Details::ReturnTypeTrait\<T\>::ReturnType, Details::IterableValueType\<Enumerable\>\>::value, [System::SmartPtr](./smartptr/)\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | 将可遍历对象包装为可用于基于范围的 for 循环的适配器（目标类型与迭代器原始 value_type 相同）。 |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value\&&\!std::is_same\<typename Details::ReturnTypeTrait\<T\>::ReturnType, Details::IterableValueType\<Enumerable\>\>::value, Details::CppIteratorAdapter\<Enumerable, T\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | 将可遍历对象包装为可用于基于范围的 for 循环的适配器（目标类型与原始不同）。 |
| std::enable_if_t<\![IsSmartPtr](./issmartptr/)\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, Details::ValueTypeOfEnumerable\<Enumerable\>, Enumerable *\>\> [IterateOver](./iterateover/)(const Enumerable *) | 将可遍历对象包装为可用于基于范围的 for 循环的适配器（默认目标类型）。 |
| std::enable_if_t<\![IsSmartPtr](./issmartptr/)\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, T, Enumerable *\>\> [IterateOver](./iterateover/)(const Enumerable *) | 将不可遍历对象包装为可用于基于范围的 for 循环的适配器（带目标类型参数）。 |
| std::enable_if\<std::is_scalar\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | 返回指定标量值的哈希码。 |
| std::enable_if<\!std::is_scalar\<T\>::value\&&[System::IsSmartPtr](./issmartptr/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | 返回指定对象的哈希码。 |
| std::enable_if\<[System::IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | 返回指定异常对象的哈希码。 |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\![System::IsSmartPtr](./issmartptr/)\<T\>::value\&&\![System::IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | 返回指定非智能指针、非异常对象的哈希码。 |
| int [GetHashCode](./gethashcode/)(const std::thread::id\&) | 针对 std::thread::id 的特化；返回线程对象的哈希码。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [Cast_noexcept](./cast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | 对 [SmartPtr](./smartptr/) 对象执行 cast。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [Cast](./cast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | 对 [SmartPtr](./smartptr/) 对象执行 cast。 |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)(const TFrom\&) | 旧的已废弃 cast，将在未来版本中删除。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | 对 [SmartPtr](./smartptr/) 对象执行 dynamic cast。 |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\>) | 对对象执行 dynamic cast 为 Exception 对象。 |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [DynamicCast](./dynamiccast/)(const TFrom\&) | 对 Exception 对象执行 dynamic cast。 |
| std::enable_if<\!std::is_enum\<TTo\>::value\&&\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | 对 [SmartPtr](./smartptr/) 对象执行 dynamic cast。 |
| std::enable_if\<std::is_enum\<TTo\>::value, TTo\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\>) | 通过 cast 对装箱的枚举进行解箱。 |
| [CastResult](./castresult/)\<TTo\>::type [DynamicCast](./dynamiccast/)(std::nullptr_t) | 对空对象执行 dynamic cast。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&\![IsSmartPtr](./issmartptr/)\<TFrom\>::value\&&std::is_convertible\<TTo, TFrom\>::value, TTo\>::type [DynamicCast](./dynamiccast/)(TFrom\&) | 对非指针对象执行 dynamic cast。 |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\>) | 对对象执行 dynamic cast 为 Exception 对象。 |
| std::enable_if\<std::is_pointer\<TTo\>::value\&&std::is_same\<IntPtr, TFrom\>::value, TTo\>::type [DynamicCast](./dynamiccast/)(TFrom) | 从 IntPtr 对象执行指针 cast。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [StaticCast_noexcept](./staticcast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | 对 [SmartPtr](./smartptr/) 对象执行 static cast。 |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)([WeakPtr](./weakptr/)\<TFrom\> const\&) | 对 [WeakPtr](./weakptr/) 对象执行 static cast。 |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)(const TFrom\&) | 对 Exception 对象执行 static cast。 |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\>) | 对对象执行 static cast 为 Exception 对象。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [StaticCast](./staticcast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | 对 [SmartPtr](./smartptr/) 对象执行 static cast。 |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast](./staticcast/)([WeakPtr](./weakptr/)\<TFrom\> const\&) | 对 [WeakPtr](./weakptr/) 对象执行 static cast。 |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast](./staticcast/)(std::nullptr_t) | 对空对象执行 static cast。 |
| std::enable_if\<std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(TFrom) | 对算术类型的特化。 |
| std::enable_if\<std::is_same\<TTo, [System::String](./string/)\>::value, TTo\>::type [StaticCast](./staticcast/)(TTo) | 处理从 [String](./string/) 到 [String](./string/) 的 cast。 |
| std::enable_if\<std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(const TFrom *) | 对算术类型的特化（指针）。 |
| std::enable_if<\!std::is_same\<TFrom, [System::String](./string/)\>::value\&&\![IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&\![IsSmartPtr](./issmartptr/)\<TFrom\>::value\&&\!std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(const TFrom\&) | 对非指针对象执行 static cast。 |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [StaticCast](./staticcast/)(const TFrom\&) | 对 Exception 对象执行 static cast。 |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [StaticCast](./staticcast/)([SmartPtr](./smartptr/)\<TFrom\>) | 对对象执行 static cast 为 Exception 对象。 |
| [CastResult](./castresult/)\<TTo\>::type [ConstCast](./constcast/)(const [SmartPtr](./smartptr/)\<TFrom\>\&) | 已废弃 cast 的结束。 |
| [CastResult](./castresult/)\<TTo\>::type [ForceStaticCast](./forcestaticcast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | 对 [SmartPtr](./smartptr/) 对象执行真实的 static cast。 |
| [SmartPtr](./smartptr/)\<[Object](./object/)\> [MemberwiseClone](./memberwiseclone/)(T *) | 使用拷贝构造函数进行成员级克隆。 |
| [SharedPtr](./sharedptr/)\<T\> [With](./with/)(const [SharedPtr](./sharedptr/)\<T\>\&, const A\&) | 克隆引用记录并对其应用初始化函数对象。 |
| T [With](./with/)(const T\&, const A\&) | 复制结构体记录并对其应用初始化函数对象。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::None, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用显式 cast 将源类型转换为结果类型（源与结果相同）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Static, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用显式 cast 将源类型转换为结果类型（需要类似构造函数的简单 cast）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>[::Exception](./exception/), Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用显式 cast 将源类型转换为结果类型（用于异常包装器）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::ObjectToException, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用显式 cast 将源类型转换为结果类型（用于将对象 cast 为异常）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Pointer, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用显式 cast 将源类型转换为结果类型（当源与结果都是智能指针且没有显式 SmartPtr<...> 时）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::RawPointer, typename [CastResult](./castresult/)\<std::remove_pointer_t\<Result\>\>::type\> [ExplicitCast](./explicitcast/)(Source) | 使用显式 cast 将原始指针转换为智能指针。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::PointerToPointer, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用显式 cast 将源类型转换为结果类型（当源与结果都是智能指针且带有显式 SmartPtr<...>）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToNullable, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用显式 cast 将源类型转换为结果类型（用于将对象解箱为可空类型）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableBoxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用显式 cast 将源类型转换为结果类型（用于装箱可空类型）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableUnboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用显式 cast 将源类型转换为结果类型（用于将可空对象解箱）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::EnumBoxing, [SmartPtr](./smartptr/)\<[BoxedValueBase](./boxedvaluebase/)\>\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用显式 cast 将源类型转换为结果类型（用于枚举装箱）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::HeapifyBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用显式 cast 将源类型转换为结果类型（用于将值类型复制到堆上，以便作为智能指针引用）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用显式 cast 将源类型转换为结果类型（用于从值类型获取接口）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Boxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用显式 cast 将源类型转换为结果类型（用于通用装箱）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::StringBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用显式 cast 将源类型转换为结果类型（用于 [System::String](./string/) 装箱）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceUnboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用显式 cast 将源类型转换为结果类型（用于接口解箱）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Unboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用显式 cast 将源类型转换为结果类型（用于通用解箱）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Null, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用显式 cast 将源类型转换为结果类型（用于 nullptr cast）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>**::Array**, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用显式 cast 将源类型转换为结果类型（用于数组之间的 cast）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Static, Result\> [AsCast](./ascast/)(const Source\&) | 使用 “as” 运算符 cast 将源类型转换为结果类型（需要类似构造函数的简单 cast）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::None, Result\> [AsCast](./ascast/)(const Source\&) | 使用 “as” 运算符 cast 将源类型转换为结果类型（源与结果相同）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>[::Exception](./exception/), Result\> [AsCast](./ascast/)(const Source\&) | 使用 “as” 运算符 cast 将源类型转换为结果类型（用于异常包装器）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::ObjectToException, Result\> [AsCast](./ascast/)(const Source\&) | 使用 “as” 运算符 cast 将源类型转换为结果类型（用于将对象 cast 为异常）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Pointer, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | 使用 “as” 运算符 cast 将源类型转换为结果类型（当源与结果都是智能指针时）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::PointerToPointer, Result\> [AsCast](./ascast/)(const Source\&) | 使用 “as” 运算符 cast 将源类型转换为结果类型（当源与结果都是智能指针且带有显式 SmartPtr<...> 时）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToNullable, Result\> [AsCast](./ascast/)(const Source\&) | 使用 “as” 运算符 cast 将源类型转换为结果类型（用于将对象解箱为可空类型）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceUnboxingToNullable, Result\> [AsCast](./ascast/)(const Source\&) | 使用 “as” 运算符 cast 将源类型转换为结果类型（无效的非对象类型解箱）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InvalidUnboxing, Result\> [AsCast](./ascast/)(const Source\&) | 无效的非对象类型解箱。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableBoxing, Result\> [AsCast](./ascast/)(const Source\&) | 使用 “as” 运算符 cast 将源类型转换为结果类型（用于装箱可空对象）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | 使用 “as” 运算符 cast 将源类型转换为结果类型（用于通用对象装箱）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Boxing, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | 使用 “as” 运算符 cast 将源类型转换为结果类型（用于通用对象装箱）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToString, Result\> [AsCast](./ascast/)(const Source\&) | 使用 “as” 运算符 cast 将源类型转换为结果类型（用于字符串解箱）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Null, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | 使用 “as” 运算符 cast 将源类型转换为结果类型（用于 nullptr cast）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>**::Array**, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | 使用 “as” 运算符 cast 将源类型转换为结果类型（用于数组之间的 cast）。 |
| static auto [SafeInvoke](./safeinvoke/)(T0\&&, T1\&&) | 实现 “?.” 运算符的翻译。 |
| const [System::TypeInfo](./typeinfo/)\& [ObjectType::GetType< System::String >](./objecttype_dcolon_gettype_less_system_dcolon_string__greater/)() | 实现 typeof() 翻译。[String](./string/) 的重载。 |
| const [System::TypeInfo](./typeinfo/)\& [ObjectType::GetType< System::DateTime >](./objecttype_dcolon_gettype_less_system_dcolon_datetime__greater/)() | 实现 typeof() 翻译。[DateTime](./datetime/) 的重载。 |
| **bool** [Equals](./equals/)(const TA\&, const TB\&) | 通过对两值应用 [operator==()](./operator_equal_equal/) 判断它们是否相等。 |
| **bool** [Equals< float, float >](./equals_less_float,_float__greater/)(const **float**\&, const **float**\&) | 单精度浮点数的特化。虽然 IEC 60559:1989 定义两个 NaN 总是比较不等，但 [System.Object.Equals](./object/equals/) 的合约要求重载必须满足等价运算符的要求。因此，System.Double.Equals 和 System.Single.Equals 在比较两个 NaN 时返回 True，而等号运算符在此情况下返回 False，符合标准。 |
| **bool** [Equals< double, double >](./equals_less_double,_double__greater/)(const **double**\&, const **double**\&) | 双精度浮点数的特化。 |
| std::enable_if_t<\!std::is_floating_point\<TA\>::value\&&\!std::is_floating_point\<TB\>::value, int\> [Compare](./compare/)(const TA\&, const TB\&) | 比较两个值。 |
| std::enable_if_t\<std::is_floating_point\<TA\>::value\&&std::is_floating_point\<TB\>::value, int\> [Compare](./compare/)(const TA\&, const TB\&) | 比较两个浮点数。 |
| **bool** [IsNaN](./isnan/)(const T\&) | 判断指定值是否为 NaN。 |
| **bool** [IsInfinity](./isinfinity/)(const T\&) | 判断指定值是否为无穷大。 |
| **bool** [IsPositiveInfinity](./ispositiveinfinity/)(const T\&) | 判断指定值是否为正无穷大。 |
| **bool** [IsNegativeInfinity](./isnegativeinfinity/)(const T\&) | 判断指定值是否为负无穷大。 |
| TTo [CheckedCast](./checkedcast/)(TFrom) | 判断指定值是否在 **TTo** 类型的取值范围内，如果是则将其强制转换为 **TTo**。 |
| [ScopeGuard](./scopeguard/)\<F\> [MakeScopeGuard](./makescopeguard/)(F) | 创建 ScopedGuard 实例的工厂函数。 |
| T [setter_wrap](./setter_wrap/)(void(*)(T2), T) | 用于具有类型转换的静态 setter 函数的重载。 |
| std::enable_if\<std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_wrap](./setter_wrap/)(Host *const, void(HostSet::*)(T2), T) | 用于具有类型转换的实例 setter 函数的重载。 |
| T [setter_increment_wrap](./setter_increment_wrap/)(T(*)(), void(*)(T)) | 翻译器将 C# 对具有 setter/getter 的类属性的递增表达式翻译为调用此函数。 |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_increment_wrap](./setter_increment_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | 同上，针对实例属性的递增表达式（非 const getter）。 |
| T [setter_post_increment_wrap](./setter_post_increment_wrap/)(T(*)(), void(*)(T)) | 翻译器将 C# 对具有 setter/getter 的类属性的后递增表达式翻译为调用此函数。 |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_increment_wrap](./setter_post_increment_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | 同上，针对实例属性的后递增表达式（非 const getter）。 |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_increment_wrap](./setter_post_increment_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | 同上，针对实例属性的后递增表达式（const getter）。 |
| T [setter_decrement_wrap](./setter_decrement_wrap/)(T(*)(), void(*)(T)) | 翻译器将 C# 对具有 setter/getter 的类属性的前递减表达式翻译为调用此函数。 |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_decrement_wrap](./setter_decrement_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | 同上，针对实例属性的前递减表达式（非 const getter）。 |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_decrement_wrap](./setter_decrement_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | 同上，针对实例属性的前递减表达式（const getter）。 |
| T [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(T(*)(), void(*)(T)) | 翻译器将 C# 对具有 setter/getter 的类属性的后递减表达式翻译为调用此函数。 |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | 同上，针对实例属性的后递减表达式（非 const getter）。 |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | 同上，针对实例属性的后递减表达式（const getter）。 |
| std::enable_if<\![IsSmartPtr](./issmartptr/)\<T\>::value, [SmartPtr](./smartptr/)\<T\>\>::type [MakeObject](./makeobject/)(Args\&&...) | 在堆上创建对象并返回其共享指针。 |
| std::enable_if\<[IsSmartPtr](./issmartptr/)\<T\>::value, T\>::type [MakeObject](./makeobject/)(Args\&&...) | 在堆上创建对象并返回其共享指针。 |
| [SmartPtr](./smartptr/)\<X\> [MakeSharedPtr](./makesharedptr/)(X *) | 将原始指针转换为智能指针。 |
| [SmartPtr](./smartptr/)\<X\> [MakeSharedPtr](./makesharedptr/)(const X *) | 将原始指针转换为智能指针（const 重载）。当在 C# 方法中使用 const 的 “this” 时非常有用。 |
| [SmartPtr](./smartptr/)\<Y\> [static_pointer_cast](./static_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | 使用 static_cast 对智能指针进行 cast。 |
| [SmartPtr](./smartptr/)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | 使用 dynamic_cast 对智能指针进行 cast。 |
| [SmartPtr](./smartptr/)\<Y\> [const_pointer_cast](./const_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | 使用 const_cast 对智能指针进行 cast。 |
| T * [get_pointer](./get_pointer/)([System::SmartPtr](./smartptr/)\<T\> const\&) | 获取智能指针所引用的对象。 |
| std::enable_if<\!System::detail::has_method_get_Count\<From\>::value, [Collections::Generic::ListPtr](../system.collections.generic/listptr/)\<To\>\>::type [CastEnumerableTo](./castenumerableto/)(const From\&) | 将指定可枚举对象的元素显式 cast 为不同类型。 |
| std::enable_if\<System::detail::has_method_get_Count\<From\>::value, [Collections::Generic::ListPtr](../system.collections.generic/listptr/)\<To\>\>::type [CastEnumerableTo](./castenumerableto/)(const From\&) | 将指定可枚举对象的元素显式 cast 为不同类型。 |
| std::enable_if_t\<[System::IsSmartPtr](./issmartptr/)\<From\>::value, [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<To\>\>\> [StaticCastArray](./staticcastarray/)(const [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<From\>\>\&) | 将指定数组的元素 cast 为不同类型。针对 [SmartPtr](./smartptr/) 对象的特化。 |
| std::enable_if_t<\![System::IsSmartPtr](./issmartptr/)\<From\>::value\&&[System::IsBoxable](./isboxable/)\<From\>::value\&&std::is_same\<To, [System::SharedPtr](./sharedptr/)\<[Object](./object/)\>\>::value, [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<To\>\>\> [StaticCastArray](./staticcastarray/)(const [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<From\>\>\&) | 将指定数组的元素 cast 为不同类型。针对可装箱且目标为 [Object](./object/)[] 的特化。 |
| [SharedPtr](./sharedptr/)\<[Array](./array/)\<To\>\> [DynamicCastArray](./dynamiccastarray/)(const [SharedPtr](./sharedptr/)\<[Array](./array/)\<From\>\>\&) | 将指定数组的元素 cast 为不同类型。 |
| std::istream\& [operator>>](./operator_greater_greater/)(std::istream\&, [String](./string/)\&) | 以 UTF-8 编码从输入流获取字符串。 |
| std::wistream\& [operator>>](./operator_greater_greater/)(std::wistream\&, [String](./string/)\&) | 从输入流获取字符串。 |
| [TaskPtr](./taskptr/) [MakeAsync](./makeasync/)(const Details::AsyncFunction\&) |  |
| [RTaskPtr](./rtaskptr/)\<T\> [MakeAsync](./makeasync/)(const Details::ResultAsyncFunction\<T\>\&) |  |
| [Threading::Tasks::ResultValueTask](../system.threading.tasks/resultvaluetask/)\<T\> [MakeValueAsync](./makevalueasync/)(const Details::ResultAsyncFunction\<T\>\&) |  |
| [Threading::Tasks::ValueTask](../system.threading.tasks/valuetask/) [MakeValueAsync](./makevalueasync/)(const Details::AsyncFunction\&) |  |
| [ValueTuple](./valuetuple/)\<Args...\> [MakeTuple](./maketuple/)(Args...) | 在栈上创建元组。 |
| [ValueTuple](./valuetuple/)\<Args...\> [TieTuple](./tietuple/)(Args\&&...) | 创建绑定到若干值的元组。 |
| **bool** [is_vp_test](./is_vp_test/)(const ::testing::TestInfo *) |  |
| **bool** [is_parametrized_test](./is_parametrized_test/)(const ::testing::TestInfo *) |  |
| std::string [ForEachMemberGVName](./foreachmembergvname/)() |  |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [Base64FormattingOptions](./base64formattingoptions/) | 包含表示 Base64 编码数据不同格式的枚举值。 |
| [DateTimeKind](./datetimekind/) | 表示日期和时间种类的枚举值。 |
| [DayOfWeek](./dayofweek/) | 表示星期几的枚举。 |
| [EnvironmentVariableTarget](./environmentvariabletarget/) | 指定环境变量位置的枚举。 |
| [MidpointRounding](./midpointrounding/) | 指定四舍五入函数行为的枚举。 |
| [PlatformID](./platformid/) | 表示操作系统平台的枚举。 |
| [SmartPtrMode](./smartptrmode/) | [SmartPtr](./smartptr/) 指针类型：弱指针或共享指针。决定在决定是否删除对象时指针是否计数。 |
| [StringSplitOptions](./stringsplitoptions/) | 决定字符串拆分行为的枚举。 |
| [StringComparison](./stringcomparison/) | 定义字符串比较风格的枚举。 |
| [TypeCode](./typecode/) | 表示对象类型的枚举。 |
| [UriKind](./urikind/) | 表示 URI 种类的枚举。 |
| [UriComponents](./uricomponents/) | 表示 URI 组件的枚举。 |
| [UriFormat](./uriformat/) | 指定 URI 转义方式的枚举。 |
| [UriHostNameType](./urihostnametype/) | 表示主机名类型的枚举。 |
| [UriPartial](./uripartial/) | 表示 [Uri.GetLeftPart](./uri/getleftpart/) 方法使用的 URI 部分的枚举。 |
## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [IFormatProviderPtr](./iformatproviderptr/) | [System::IFormatProvider](./iformatprovider/) 类实例的智能指针别名。 |
| [DecoderFallbackPtr](./decoderfallbackptr/) | [System::Text::DecoderFallback](../system.text/decoderfallback/) 类实例的智能指针别名。 |
| [DecoderFallbackBufferPtr](./decoderfallbackbufferptr/) | [System::Text::DecoderFallbackBuffer](../system.text/decoderfallbackbuffer/) 类实例的智能指针别名。 |
| [DecoderReplacementFallbackPtr](./decoderreplacementfallbackptr/) | [System::Text::DecoderReplacementFallback](../system.text/decoderreplacementfallback/) 类实例的智能指针别名。 |
| [EncoderFallbackPtr](./encoderfallbackptr/) | [System::Text::EncoderFallback](../system.text/encoderfallback/) 类实例的智能指针别名。 |
| [EncoderFallbackBufferPtr](./encoderfallbackbufferptr/) | [System::Text::EncoderFallbackBuffer](../system.text/encoderfallbackbuffer/) 类实例的智能指针别名。 |
| [EncoderPtr](./encoderptr/) | [System::Text::Encoder](../system.text/encoder/) 类实例的智能指针别名。 |
| [DecoderPtr](./decoderptr/) | [System::Text::Decoder](../system.text/decoder/) 类实例的智能指针别名。 |
| [EncoderReplacementFallbackBufferPtr](./encoderreplacementfallbackbufferptr/) | [System::Text::EncoderReplacementFallbackBuffer](../system.text/encoderreplacementfallbackbuffer/) 类实例的智能指针别名。 |
| [EncoderReplacementFallbackPtr](./encoderreplacementfallbackptr/) | [System::Text::EncoderReplacementFallback](../system.text/encoderreplacementfallback/) 类实例的智能指针别名。 |
| [EncodingPtr](./encodingptr/) | [System::Text::Encoding](../system.text/encoding/) 类实例的智能指针别名。 |
| [EncodingInfoPtr](./encodinginfoptr/) | [System::Text::EncodingInfo](../system.text/encodinginfo/) 类实例的智能指针别名。 |
| [StreamPtr](./streamptr/) | [System::IO::Stream](../system.io/stream/) 类实例的智能指针别名。 |
| [FileStreamPtr](./filestreamptr/) | [System::IO::FileStream](../system.io/filestream/) 类实例的智能指针别名。 |
| [MemoryStreamPtr](./memorystreamptr/) | [System::IO::MemoryStream](../system.io/memorystream/) 类实例的智能指针别名。 |
| [StreamReaderPtr](./streamreaderptr/) | [System::IO::StreamReader](../system.io/streamreader/) 类实例的智能指针别名。 |
| [StreamWriterPtr](./streamwriterptr/) | [System::IO::StreamWriter](../system.io/streamwriter/) 类实例的智能指针别名。 |
| [FileInfoPtr](./fileinfoptr/) | [System::IO::FileInfo](../system.io/fileinfo/) 类实例的智能指针别名。 |
| [FileSystemInfoPtr](./filesysteminfoptr/) | [System::IO::FileSystemInfo](../system.io/filesysteminfo/) 类实例的智能指针别名。 |
| [DirectoryInfoPtr](./directoryinfoptr/) | [System::IO::DirectoryInfo](../system.io/directoryinfo/) 类实例的智能指针别名。 |
| [TaskPtr](./taskptr/) | [System::Threading::Tasks::Task](../system.threading.tasks/task/) 类实例的智能指针别名。 |
| [RTaskPtr](./rtaskptr/) | [System::Threading::Tasks::ResultTask](../system.threading.tasks/resulttask/) 类实例的智能指针别名。 |
| [FunctionPtr](./functionptr/) | 默认调用约定的函数类型别名。 |
| [Action](./action/) | 没有返回值的方法的委托类型。 |
| [AggregateException](./aggregateexception/) |  |
| [ByteArrayPtr](./bytearrayptr/) | 指向无符号 8 位整数数组的智能指针别名。 |
| [AsyncCallback](./asynccallback/) | 表示异步操作完成时调用的方法的委托类型。 |
| [BadImageFormatException](./badimageformatexception/) | 当 DLL 或可执行程序的文件映像无效时抛出的异常。请勿将 BadImageFormatException 类实例包装为 [System::SmartPtr](./smartptr/)。 |
| [Converter](./converter/) | 表示接受单个 **TInput** 参数并返回 **TOutput** 值的可调用实体的指针。 |
| [Event](./event/) | 表示事件——一种通过委托调用向订阅者通知感兴趣事件的机制。 |
| [EventArgsPtr](./eventargsptr/) | [EventArgs](./eventargs/) 类实例的共享指针别名。 |
| [EventHandler](./eventhandler/) | 表示响应并处理事件的方法。此类型应在栈上分配，并通过值或引用传递给函数。不要使用 [System::SmartPtr](./smartptr/) 类管理此类型的对象。 |
| [ExceptionPtr](./exceptionptr/) | 异常包装器使用的类型别名。 |
| [Exception](./exception/) | 用于替代 Details::Exception 的别名。 |
| [SystemException](./systemexception/) |  |
| [ApplicationException](./applicationexception/) |  |
| [InvalidOperationException](./invalidoperationexception/) |  |
| [InvalidProgramException](./invalidprogramexception/) |  |
| [InvalidTimeZoneException](./invalidtimezoneexception/) |  |
| [TimeZoneNotFoundException](./timezonenotfoundexception/) |  |
| [ObjectDisposedException](./objectdisposedexception/) |  |
| [NotImplementedException](./notimplementedexception/) |  |
| [NotSupportedException](./notsupportedexception/) |  |
| [PlatformNotSupportedException](./platformnotsupportedexception/) |  |
| [ArgumentException](./argumentexception/) |  |
| [ArgumentNullException](./argumentnullexception/) |  |
| [ArgumentOutOfRangeException](./argumentoutofrangeexception/) |  |
| [FormatException](./formatexception/) |  |
| [UriFormatException](./uriformatexception/) |  |
| [ArithmeticException](./arithmeticexception/) |  |
| [OverflowException](./overflowexception/) |  |
| [DivideByZeroException](./dividebyzeroexception/) |  |
| [OutOfMemoryException](./outofmemoryexception/) |  |
| [IndexOutOfRangeException](./indexoutofrangeexception/) |  |
| [RankException](./rankexception/) |  |
| [InvalidCastException](./invalidcastexception/) |  |
| [NullReferenceException](./nullreferenceexception/) |  |
| [UnauthorizedAccessException](./unauthorizedaccessexception/) |  |
| [MemberAccessException](./memberaccessexception/) |  |
| [MethodAccessException](./methodaccessexception/) |  |
| [OperationCanceledException](./operationcanceledexception/) |  |
| [StackOverflowException](./stackoverflowexception/) |  |
| [TimeoutException](./timeoutexception/) |  |
| [ExecutionEngineException](./executionengineexception/) |  |
| [TypeInitializationException](./typeinitializationexception/) |  |
| [DataMisalignedException](./datamisalignedexception/) |  |
| [IAsyncResultPtr](./iasyncresultptr/) | [IAsyncResult](./iasyncresult/) 的共享指针。 |
| [MakeConstRef_t](./makeconstref_t/) | [MakeConstRef](./makeconstref/) 修饰符的帮助类型。 |
| [Predicate](./predicate/) | 表示接受单个参数并返回 bool 的谓词指针。 |
| [ArrayPtr](./arrayptr/) | “指向数组”类型的别名。 |
| [SharedPtr](./sharedptr/) | 库中广泛使用的智能指针别名。 |
| [StringComparerPtr](./stringcomparerptr/) | 指向 [StringComparer](./stringcomparer/) 类实例的共享指针别名。 |
| [TimeZonePtr](./timezoneptr/) | 指向 [TimeZone](./timezone/) 类实例的共享指针别名。 |
| [TimeZoneInfoPtr](./timezoneinfoptr/) | 指向 [TimeZoneInfo](./timezoneinfo/) 类实例的共享指针别名。 |