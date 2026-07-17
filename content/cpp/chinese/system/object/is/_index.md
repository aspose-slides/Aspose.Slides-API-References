---
title: Is()
second_title: Aspose.Slides for C++ API 参考
description: 检查对象是否表示由 targetType 描述的类型的实例。相当于 C# 'is' 运算符。
type: docs
weight: 222
url: /zh/system/object/is/
---
## Object::Is(const TypeInfo\&) const 方法

检查对象是否表示由 targetType 描述的类型的实例。相当于 C# 'is' 运算符。

```cpp
virtual bool System::Object::Is(const TypeInfo &targetType) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetType | const [TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 结构，描述用于测试当前对象的类型。 |

### 返回值

如果对象是标记类型或其子类，则返回 True；否则返回 false。

## 另请参阅

* 类 [TypeInfo](../../typeinfo/)
* 类 [Object](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)