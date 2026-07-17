---
title: IsDefined()
second_title: Aspose.Slides for C++ API 参考
description: 未实现。指示是否已对该成员应用指定类型或其派生类型的一个或多个属性。
type: docs
weight: 157
url: /zh/system/typeinfo/isdefined/
---
## TypeInfo::IsDefined(const TypeInfo\&, bool) const 方法

未实现。指示是否已对该成员应用指定类型或其派生类型的一个或多个属性。

```cpp
bool System::TypeInfo::IsDefined(const TypeInfo &attributeType, bool inherit) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | 要搜索的自定义属性类型。搜索包括派生类型。 |
| inherit | **bool** | true 表示在此成员的继承链中搜索属性；false 表示不搜索。此参数对属性和事件被忽略。 |

### 返回值

如果已对该成员应用 attributeType 或其任何派生类型的一个或多个实例，则返回 true；否则返回 false。

## 另请参见

* 类 [TypeInfo](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)