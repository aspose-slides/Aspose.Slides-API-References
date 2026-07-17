---
title: Is()
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 27
url: /zh/system/details_objectdisposedexception/is/
---
## Details_ObjectDisposedException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Details_ObjectDisposedException::Is(const System::TypeInfo &target) const override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 结构，描述用于测试当前对象的类型。 |

### 返回值

如果对象是标记类型或其子类，则返回 True；否则返回 false。

### 备注

Check if object represents an instance of type described by targetType. Analog of C# 'is' operator.

## 另请参阅

* Class [TypeInfo](../../typeinfo/)
* Class [Details_ObjectDisposedException](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)