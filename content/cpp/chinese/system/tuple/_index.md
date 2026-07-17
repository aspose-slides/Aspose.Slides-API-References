---
title: Tuple
second_title: Aspose.Slides for C++ API 参考
description: 表示元组数据结构的类。最大项数为8。
type: docs
weight: 1327
url: /zh/system/tuple/
---
## Tuple 类

表示元组数据结构的类。最大项数为8。

```cpp
template<typename ...>class Tuple : public System::Runtime::CompilerServices::ITuple
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Args | The tuple elements types. |

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | 确定当前对象与指定对象是否相同。 |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | 使用 C# [Object.Equals](../object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅用于内部目的。 |
| std::tuple_element\<Index, tuple_t\>::type [get_Item](./get_item/)() const | 获取 [Tuple](./) 对象组件的值。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../object/gethashcode/) 方法。使自定义对象能够进行哈希。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../object/gettype/) 调用。 |
| virtual [SharedPtr](../sharedptr/)\<[Object](../object/)\> [idx_get](../../system.runtime.compilerservices/ituple/idx_get/)(**int32_t**) const | 返回索引位置的元素。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../object/lock/)() | 实现 C# lock() 语句的锁定。可直接调用或使用 [LockContext](../lockcontext/) 哨兵对象。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../object/memberwiseclone/) 方法。使自定义类型能够克隆。 |
|  [Object](../object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../object/object/)([Object](../object/) const\&) | 复制构造函数。实际上不复制任何内容，仅初始化新对象并允许对子类进行复制构造。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许对子类进行复制构造。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) 在字符串和 nullptr 情形下的特化。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) 在字符串情形下的特化。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 增加共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../string/) [ToString](../object/tostring/)() const | 相当于 C# [Object.ToString()](../object/tostring/) 方法。使自定义对象能够转换为字符串。 |
|  [Tuple](./tuple/)(Args...) | 构造一个元组对象。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | 实现 C# typeof([System.Object](../object/)) 构造。 |
| void [Unlock](../object/unlock/)() | 实现 C# lock() 语句的解锁。可直接调用或使用 [LockContext](../lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 增加弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 备注

```cpp
#include "system/smart_ptr.h"
#include "system/tuple.h"
#include <iostream>

int main()
{
  const auto tuple = System::MakeObject<System::Tuple<int, int, int>>(32, 16, 128);

  std::cout <<
    "Item 1: " << tuple->get_Item<0>() << std::endl <<
    "Item 2: " << tuple->get_Item<1>() << std::endl <<
    "Item 3: " << tuple->get_Item<2>() << std::endl;

  return 0;
}
/*
此代码示例产生以下输出：
项 1: 32
项 2: 16
项 3: 128
*/
```

## 另见

* 类 [ITuple](../../system.runtime.compilerservices/ituple/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)