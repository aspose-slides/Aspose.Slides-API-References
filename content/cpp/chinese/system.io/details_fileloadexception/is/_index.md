---
title: Is()
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 27
url: /zh/system.io/details_fileloadexception/is/
---
## Details_FileLoadException::Is(const System::TypeInfo\&) const 方法




```cpp
bool System::IO::Details_FileLoadException::Is(const System::TypeInfo &target) const override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 结构，描述要测试当前对象的类型。 |

### 返回值

如果对象是标记的类型或其子类则返回 true，否则返回 false。
## 备注


检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 操作符。 
## 另请参见

* 类 [TypeInfo](../../../system/typeinfo/)
* 类 [Details_FileLoadException](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)