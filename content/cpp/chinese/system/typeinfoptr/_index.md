---
title: TypeInfoPtr
second_title: Aspose.Slides for C++ API 参考
description: "用于指向 TypeInfo 类实例的指针的包装器。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 1925
url: /zh/system/typeinfoptr/
---
## TypeInfoPtr struct

用于指向 [TypeInfo](../typeinfo/) 类实例的指针的包装器。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../smartptr/) 类来管理此类型的对象。

```cpp
class TypeInfoPtr
```

## 方法

| 方法 | 描述 |
| --- | --- |
|  [operator TypeInfo *](./operator_typeinfo__star/)() | 返回指向表示的 [TypeInfo](../typeinfo/) 对象的原始指针。 |
|  [TypeInfoPtr](./typeinfoptr/)() | 默认构造函数。 |
|  [TypeInfoPtr](./typeinfoptr/)(const std::type_info\&) | 构造函数。 |
|  [TypeInfoPtr](./typeinfoptr/)(const char_t *, **uint32_t**) | 构造函数。 |
|  [TypeInfoPtr](./typeinfoptr/)(const char_t *) | 构造函数。 |
|  [TypeInfoPtr](./typeinfoptr/)(const [String](../string/)\&) | 构造函数。 |
|  [~TypeInfoPtr](./~typeinfoptr/)() | 析构函数。 |
## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)