---
title: Is()
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 27
url: /zh/system/details_unauthorizedaccessexception/is/
---
## 详细信息_UnauthorizedAccessException::Is(const System::TypeInfo\&) const 方法

```cpp
bool System::Details_UnauthorizedAccessException::Is(const System::TypeInfo &target) const override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 结构，描述用于测试当前对象的类型。 |

### 返回值

如果对象是标记类型或其子类，则返回 true，否则返回 false。

## 备注

检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。

## 另请参见

* 类 [TypeInfo](../../typeinfo/)
* 类 [Details_UnauthorizedAccessException](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)