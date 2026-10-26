---
title: NumberFormatInfo
second_title: Aspose.Slides for C++ API 参考
description: "保存有关如何格式化数字的信息。仅在非只读对象上启用 setter 操作。此类的对象应仅使用 System::MakeObject() 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言失败。始终将此类封装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 248
url: /zh/system.globalization/numberformatinfo/
---
## NumberFormatInfo 类

保存有关如何格式化数字的信息。仅在非只读对象上启用 setter 操作。此类的对象应仅使用 [System::MakeObject()](../../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言失败。始终将此类封装为 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | 克隆格式信息。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | 获取货币小数位数。 |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | 获取货币小数分隔符。 |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | 获取货币分组分隔符。 |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | 获取每组的货币小数位数。 |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | 获取货币负数模式。 |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | 获取货币正数模式。 |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | 获取货币符号。 |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | 获取当前线程文化定义的数字格式信息。 |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | 获取指定数字形状显示方式的值。 |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | 获取不变文化定义的数字格式信息。 |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | 检查格式是否为只读。 |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | 获取非数字 (NaN) 符号。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | 获取数字符号 (0 到 9)。 |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | 获取负无穷符号。 |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | 获取负号。 |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | 获取小数位数。 |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | 获取小数分隔符。 |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | 获取数字分组分隔符。 |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | 获取每组的数字位数。 |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | 获取数字负数模式。 |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | 获取百分比值的小数位数。 |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | 获取百分比值中的小数分隔符。 |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | 获取百分比值中的分组分隔符。 |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | 获取每个百分比值组的数字位数。 |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | 获取百分比负数模式。 |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | 获取百分比正数模式。 |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | 获取百分比符号。 |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | 获取千分号。 |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | 获取正无穷符号。 |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | 获取正号。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | 获取特定类型的格式化器。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用对自定义对象的哈希。 |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | 获取与格式提供程序关联的格式化器。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [NumberFormatInfo](./numberformatinfo/)() | 默认构造函数（不变 [NumberFormatInfo](./)）。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | 获取只读版本的格式化器。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 使用引用比较值类型对象与 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | 设置货币小数位数。 |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | 设置货币小数分隔符。 |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | 设置货币分组分隔符。 |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | 设置每组的货币小数位数。 |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | 设置货币负数模式。 |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | 设置货币正数模式。 |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | 设置货币符号。 |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | 设置指定数字形状显示方式的值。 |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | 设置非数字 (NaN) 符号。 |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 设置数字符号 (0 到 9)。 |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | 设置负无穷符号。 |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | 设置负号。 |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | 设置小数位数。 |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | 设置小数分隔符。 |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | 设置数字分组分隔符。 |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | 设置每组的数字位数。 |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | 设置数字负数模式。 |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | 设置百分比值的小数位数。 |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | 设置百分比值中的小数分隔符。 |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | 设置百分比值中的分组分隔符。 |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | 设置每个百分比值组的数字位数。 |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | 设置百分比负数模式。 |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | 设置百分比正数模式。 |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | 设置百分比符号。 |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | 设置千分号。 |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | 设置正无穷符号。 |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | 设置正号。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [Object](../../system/object/)
* 类 [IFormatProvider](../../system/iformatprovider/)
* 类 [ICloneable](../../system/icloneable/)
* 命名空间 [System::Globalization](../)
* 库 [Aspose.Slides](../../)