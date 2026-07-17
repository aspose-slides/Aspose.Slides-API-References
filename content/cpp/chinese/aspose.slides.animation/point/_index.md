---
title: Point
second_title: Aspose.Slides for C++ API 参考
description: 表示动画点。
type: docs
weight: 495
url: /zh/aspose.slides.animation/point/
---
## Point 类

Represent animation point.

```cpp
class Point : public Aspose::Slides::Animation::IPoint
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [System::String](../../system/string/) [get_Formula](./get_formula/)() override | 在 values、from、to、by 属性中的公式可以由以下组成：标准算术运算符：\\u2018+\\u2019，\\u2018-\\u2018，\\u2018*\\u2019，\\u2018/\\u2019，\\u2018^\\u2019，\\u2018\\u2019（mod）常量：\\u2018pi\\u2019 \\u2018e\\u2019 条件运算符：\\u2018abs\\u2019，\\u2018min\\u2019，\\u2018max\\u2019，\\u2018?\\u2019（if）比较运算符：'==','>=','', '!=','!' 三角运算符：\\u2018sin()\\u2019，\\u2018cos()\\u2019，\\u2018tan()\\u2019，\\u2018asin()\\u2019，\\u2018acos()\\u2019，\\u2018atan()\\u2019 自然对数 \\u2018ln()\\u2019 属性引用（host 支持的属性） |
| **float** [get_Time](./get_time/)() override | 表示时间值。读取 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Value](./get_value/)() override | 表示点值。仅限：bool，[ColorFormat](../../aspose.slides/colorformat/)，float，int，string。读取 [System::Object](../../system/object/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的类似实现。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的类似实现。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上并不复制任何内容，只是初始化新对象并启用子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上并不复制任何内容，只是初始化新对象并启用子类的拷贝构造。 |
|  [Point](./point/)() | 默认构造函数。 |
|  [Point](./point/)(**float**, [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::String](../../system/string/)) | 使用时间、值和公式创建动画点。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对 string 和 nullptr 情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| void [set_Formula](./set_formula/)([System::String](../../system/string/)) override | 在 values、from、to、by 属性中的公式可以由以下组成：标准算术运算符：\\u2018+\\u2019，\\u2018-\\u2018，\\u2018*\\u2019，\\u2018/\\u2019，\\u2018^\\u2019，\\u2018\\u2019（mod）常量：\\u2018pi\\u2019 \\u2018e\\u2019 条件运算符：\\u2018abs\\u2019，\\u2018min\\u2019，\\u2018max\\u2019，\\u2018?\\u2019（if）比较运算符：'==','>=','', '!=','!' 三角运算符：\\u2018sin()\\u2019，\\u2018cos()\\u2019，\\u2018tan()\\u2019，\\u2018asin()\\u2019，\\u2018acos()\\u2019，\\u2018atan()\\u2019 自然对数 \\u2018ln()\\u2019 属性引用（host 支持的属性） |
| void [set_Time](./set_time/)(**float**) override | 表示时间值。写入 **float**。 |
| void [set_Value](./set_value/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 表示点值。仅限：bool，[ColorFormat](../../aspose.slides/colorformat/)，float，int，string。写入 [System::Object](../../system/object/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的类似实现。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 结构。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参阅

* 类 [IPoint](../ipoint/)
* 命名空间 [Aspose::Slides::Animation](../)
* 库 [Aspose.Slides](../../)