---
title: ColorMatrix
second_title: Aspose.Slides C++ API 参考
description: "表示一个包含 RGBAW 颜色空间坐标的 5x5 矩阵。此类的对象应仅使用 System::MakeObject() 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装成 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 27
url: /zh/system.drawing.imaging/colormatrix/
---
## ColorMatrix 类

表示一个包含 RGBAW 颜色空间坐标的 5x5 矩阵。此类的对象应仅使用 [System::MakeObject()](../../system/makeobject/) 函数进行分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class ColorMatrix : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | 构造一个新的 [ColorMatrix](./) 类实例，并使用单位矩阵的值进行初始化。 |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | 构造一个新的 [ColorMatrix](./) 类实例，并使用指定的值进行初始化。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989 标准 NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989 标准 NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| **float** [get_Matrix00](./get_matrix00/)() const | 返回第0行第0列的值。 |
| **float** [get_Matrix01](./get_matrix01/)() const | 返回第0行第1列的值。 |
| **float** [get_Matrix02](./get_matrix02/)() const | 返回第0行第2列的值。 |
| **float** [get_Matrix03](./get_matrix03/)() const | 返回第0行第3列的值。 |
| **float** [get_Matrix04](./get_matrix04/)() const | 返回第0行第4列的值。 |
| **float** [get_Matrix10](./get_matrix10/)() const | 返回第1行第0列的值。 |
| **float** [get_Matrix11](./get_matrix11/)() const | 返回第1行第1列的值。 |
| **float** [get_Matrix12](./get_matrix12/)() const | 返回第1行第2列的值。 |
| **float** [get_Matrix13](./get_matrix13/)() const | 返回第1行第3列的值。 |
| **float** [get_Matrix14](./get_matrix14/)() const | 返回第1行第4列的值。 |
| **float** [get_Matrix20](./get_matrix20/)() const | 返回第2行第0列的值。 |
| **float** [get_Matrix21](./get_matrix21/)() const | 返回第2行第1列的值。 |
| **float** [get_Matrix22](./get_matrix22/)() const | 返回第2行第2列的值。 |
| **float** [get_Matrix23](./get_matrix23/)() const | 返回第2行第3列的值。 |
| **float** [get_Matrix24](./get_matrix24/)() const | 返回第2行第4列的值。 |
| **float** [get_Matrix30](./get_matrix30/)() const | 返回第3行第0列的值。 |
| **float** [get_Matrix31](./get_matrix31/)() const | 返回第3行第1列的值。 |
| **float** [get_Matrix32](./get_matrix32/)() const | 返回第3行第2列的值。 |
| **float** [get_Matrix33](./get_matrix33/)() const | 返回第3行第3列的值。 |
| **float** [get_Matrix34](./get_matrix34/)() const | 返回第3行第4列的值。 |
| **float** [get_Matrix40](./get_matrix40/)() const | 返回第4行第0列的值。 |
| **float** [get_Matrix41](./get_matrix41/)() const | 返回第4行第1列的值。 |
| **float** [get_Matrix42](./get_matrix42/)() const | 返回第4行第2列的值。 |
| **float** [get_Matrix43](./get_matrix43/)() const | 返回第4行第3列的值。 |
| **float** [get_Matrix44](./get_matrix44/)() const | 返回第4行第4列的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| **float** [idx_get](./idx_get/)(int, int) | 返回指定行列处的值。 |
| **float** [idx_set](./idx_set/)(int, int, **float**) | 在矩阵的指定位置设置指定的值。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
| void [set_Matrix00](./set_matrix00/)(**float**) | 在第0行第0列设置值。 |
| void [set_Matrix01](./set_matrix01/)(**float**) | 在第0行第1列设置值。 |
| void [set_Matrix02](./set_matrix02/)(**float**) | 在第0行第2列设置值。 |
| void [set_Matrix03](./set_matrix03/)(**float**) | 在第0行第3列设置值。 |
| void [set_Matrix04](./set_matrix04/)(**float**) | 在第0行第4列设置值。 |
| void [set_Matrix10](./set_matrix10/)(**float**) | 在第1行第0列设置值。 |
| void [set_Matrix11](./set_matrix11/)(**float**) | 在第1行第1列设置值。 |
| void [set_Matrix12](./set_matrix12/)(**float**) | 在第1行第2列设置值。 |
| void [set_Matrix13](./set_matrix13/)(**float**) | 在第1行第3列设置值。 |
| void [set_Matrix14](./set_matrix14/)(**float**) | 在第1行第4列设置值。 |
| void [set_Matrix20](./set_matrix20/)(**float**) | 在第2行第0列设置值。 |
| void [set_Matrix21](./set_matrix21/)(**float**) | 在第2行第1列设置值。 |
| void [set_Matrix22](./set_matrix22/)(**float**) | 在第2行第2列设置值。 |
| void [set_Matrix23](./set_matrix23/)(**float**) | 在第2行第3列设置值。 |
| void [set_Matrix24](./set_matrix24/)(**float**) | 在第2行第4列设置值。 |
| void [set_Matrix30](./set_matrix30/)(**float**) | 在第3行第0列设置值。 |
| void [set_Matrix31](./set_matrix31/)(**float**) | 在第3行第1列设置值。 |
| void [set_Matrix32](./set_matrix32/)(**float**) | 在第3行第2列设置值。 |
| void [set_Matrix33](./set_matrix33/)(**float**) | 在第3行第3列设置值。 |
| void [set_Matrix34](./set_matrix34/)(**float**) | 在第3行第4列设置值。 |
| void [set_Matrix40](./set_matrix40/)(**float**) | 在第4行第0列设置值。 |
| void [set_Matrix41](./set_matrix41/)(**float**) | 在第4行第1列设置值。 |
| void [set_Matrix42](./set_matrix42/)(**float**) | 在第4行第2列设置值。 |
| void [set_Matrix43](./set_matrix43/)(**float**) | 在第4行第3列设置值。 |
| void [set_Matrix44](./set_matrix44/)(**float**) | 在第4行第4列设置值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [Object](../../system/object/)
* 命名空间 [System::Drawing::Imaging](../)
* 库 [Aspose.Slides](../../)