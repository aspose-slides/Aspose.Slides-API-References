---
title: "System::Collections"
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 300
url: /zh/system.collections/
---
## 类

| 类 | 描述 |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) 可通过索引寻址的位集合。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [BitArrayPtr](./bitarrayptr/) | 指向 [BitArray](./bitarray/) 的指针。此类型是用于管理其他对象删除的指针。它应在栈上分配，并以值传递或 const 引用方式传递给函数。 |
| [CollectionBase](./collectionbase/) | 提供强类型集合的抽象基类。 |
| [ICollection](./icollection/) | 定义非泛型集合接口。 |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) 是所有可枚举的非泛型集合的基础接口。 |
| [IEnumerator](./ienumerator/) | 可用于遍历某些元素的枚举器接口。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | 包装器，在通用 Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) 之上创建非泛型 [IEnumerator](./ienumerator/) 实现——针对引用类型的包装器。 |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | 包装器，在通用 Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) 之上创建非泛型 [IEnumerator](./ienumerator/) 实现——针对值类型的包装器。 |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) 表示可以通过索引单独访问的非泛型对象集合。 |
| [IListImplRefType](./ilistimplreftype/) | 实现 [System::Collections::IList](./ilist/) 接口的存根，位于 [System::Collections::Generic::List](../system.collections.generic/list/) 对象上，针对引用类型的实现。 |
| [IListImplValueType](./ilistimplvaluetype/) | 实现 [System::Collections::IList](./ilist/) 接口的存根，位于 [System::Collections::Generic::List](../system.collections.generic/list/) 对象上，针对值类型的实现。 |
| [IListWrapper](./ilistwrapper/) | 用于支持从泛型到非泛型集合的强制转换的接口。 |
| [Invalidatable](./invalidatable/) | 可以通过 [InvalidatableTracker](./invalidatabletracker/) 对象跟踪其子类状态的类。 |
| [InvalidatableTracker](./invalidatabletracker/) | 实现 [Invalidatable](./invalidatable/) 对象跟踪器的类。 |