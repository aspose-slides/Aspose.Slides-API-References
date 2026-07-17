---
title: Is()
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 27
url: /zh/system/details_notsupportedexception/is/
---
## 详细信息_NotSupportedException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_NotSupportedException::Is(const System::TypeInfo &target) const override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 结构，描述用于测试当前对象的类型。 |

### 返回值

如果对象是标记类型或其子类，则为 true；否则为 false。

## 备注

检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 `is` 运算符。

## 参见

* 类 [TypeInfo](../../typeinfo/)
* 类 [Details_NotSupportedException](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)