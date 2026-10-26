---
title: StringBuilder
second_title: Aspose.Slides for C++ API 参考
description: "用于逐段累积字符串的缓冲区。此类型可以作为值类型分配在栈上，或使用 System::MakeObject() 函数在堆上分配。对象分配后，切勿混合这两种用法：对栈分配对象拥有 SmartPtr 指针是严格禁止的。"
type: docs
weight: 326
url: /zh/system.text/stringbuilder/
---
## StringBuilder 类

[Buffer](../../system/buffer/) 用于逐段累积字符串。此类型可以作为值类型分配在栈上，或使用 [System::MakeObject()](../../system/makeobject/) 函数在堆上分配。对象分配后，切勿混合这两种用法：对栈分配对象拥有 [SmartPtr](../../system/smartptr/) 指针是严格禁止的。

```cpp
class StringBuilder : public System::Object
```

## 方法

| Method | Description |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | 向构建器添加字符。 |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | 向构建器添加字符。 |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | 向构建器添加字符数组。 |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | 向构建器添加字符数组切片。 |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | 向构建器添加字符串。 |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | 向构建器添加字符串切片。 |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | 向构建器添加对象的字符串表示。 |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | 向构建器添加构建器的内容。 |
| [StringBuilder](./) * [Append](./append/)(**float**) | 向构建器添加浮点值。 |
| [StringBuilder](./) * [Append](./append/)(**double**) | 向构建器添加浮点值。 |
| [StringBuilder](./) * [Append](./append/)(int) | 向构建器添加整数值。 |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | 向构建器添加算术值。 |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | 向构建器添加枚举值的字符串表示。 |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | 向构建器追加格式化字符串。 |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | 向构建器追加格式化字符串。 |
| [StringBuilder](./) * [AppendLine](./appendline/)() | 向构建器追加换行符。 |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | 向构建器追加字符串并跟随换行符。 |
| [StringBuilder](./) * [Clear](./clear/)() | 从构建器中移除所有字符。 |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | 将构建器的数据复制到现有数组位置。 |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | 确保此 [System.Text.StringBuilder](./) 实例的容量至少为指定值。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| int [get_Capacity](./get_capacity/)() const | 获取字符串构建器的当前容量。 |
| int [get_Length](./get_length/)() const | 获取构建器中当前字符串的长度。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# 的 [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# 的 [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| char_t [idx_get](./idx_get/)(int) const | 获取指定位置的字符。 |
| void [idx_set](./idx_set/)(int, char_t) | 设置指定位置的字符。 |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | 在构建器的固定位置插入字符串。 |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | 在构建器的固定位置插入重复字符串。 |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | 在构建器的固定位置插入字符。 |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | 在构建器的固定位置插入字符。 |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | 在构建器的固定位置插入值。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# 的 [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的复制构造。 |
| char_t [operator[]](./operator[]/)(int) const | 获取指定位置的字符。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用于字符串和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用于字符串的情况。 |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | 从构建器中移除片段。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 通过构建器替换子字符串。 |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | 通过构建器的范围替换子字符串。 |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | 通过构建器替换字符。 |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | 通过构建器的范围替换字符。 |
| void [set_Capacity](./set_capacity/)(int) | 设置字符串构建器的当前容量。 |
| void [set_Length](./set_length/)(int) | 截断或扩展字符串构建器至指定长度。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
|  [StringBuilder](./stringbuilder/)() | 构造函数。 |
|  [StringBuilder](./stringbuilder/)(int) | 构造函数。 |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | 构造函数。 |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | 构造函数。 |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | 构造函数。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 获取构建器当前包含的字符串。 |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | 获取构建器当前包含的子字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 结构。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
|  [~StringBuilder](./~stringbuilder/)() | 析构函数。 |

## 另请参见

* 类 [Object](../../system/object/)
* 命名空间 [System::Text](../)
* 库 [Aspose.Slides](../../)