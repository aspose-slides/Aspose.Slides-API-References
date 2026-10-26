---
title: SmartPtrInfo
second_title: Aspose.Slides C++ API 参考
description: 用于在不知道最终类型的情况下测试和修改 SmartPtr 内容的服务类。用于垃圾回收和循环引用检测等。可以将其视为'pointer to pointer'。我们无法使用 SmartPtr 的基类型，因为它没有基类型；相反，我们使用这个'info'类。
type: docs
weight: 1223
url: /zh/system/smartptrinfo/
---
## SmartPtrInfo 类

服务类，用于在不知道最终类型的情况下测试和修改 [SmartPtr](../smartptr/) 的内容。用于垃圾回收和循环引用检测等。可以将其视为‘pointer to pointer’。我们不能使用 [SmartPtr](../smartptr/) 的基类型，因为它没有基类型；相反，我们使用这个‘info’ 类。

```cpp
class SmartPtrInfo
```

## 方法

| 方法 | 描述 |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | 获取引用指针指向的原始对象。 |
| [Object](../object/) * [getObject](./getobject/)() const | 获取引用指针指向的对象。 |
| [Object](../object/) * [getOwned](./getowned/)() const | 获取对象拥有的指针。 |
|  [operator bool](./operator_bool/)() const | 检查 info 对象是否指向非空指针。 |
| **bool** [operator!](./operator_not/)() const | 检查 info 对象是否未指向非空指针。 |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | 允许调用由引用指针指向的 [Object](../object/) 的方法。 |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | 比较两个 info 对象引用的指针值的大小。 |
|  [SmartPtrInfo](./smartptrinfo/)() | 创建空的 [SmartPtrInfo](./) 对象。 |
| explicit  [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | 创建包含特定智能指针信息的 [SmartPtrInfo](./) 对象。 |

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)