---
title: Is()
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 27
url: /zh/system/details_invalidoperationexception/is/
---
## Details_InvalidOperationException::Is(const System::TypeInfo\&) const 方法




```cpp
bool System::Details_InvalidOperationException::Is(const System::TypeInfo &target) const override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 结构描述要与当前对象进行测试的类型。 |

### 返回值

True if object is of tagged type or its subclass, false otherwise.

## 备注

Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. 

## 另请参见

* 类 [TypeInfo](../../typeinfo/)
* 类 [Details_InvalidOperationException](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)