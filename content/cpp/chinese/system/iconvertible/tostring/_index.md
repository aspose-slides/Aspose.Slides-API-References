---
title: ToString()
second_title: Aspose.Slides for C++ API 参考
description: "使用指定的特定区域文化格式信息，将此实例的值转换为等效的 System::String。"
type: docs
weight: 196
url: /zh/system/iconvertible/tostring/
---
## IConvertible::ToString(System::SharedPtr\<System::IFormatProvider\>) 方法

使用指定的特定于区域性的信息，将此实例的值转换为等效的 [System::String](../../string/)。

```cpp
virtual System::String System::IConvertible::ToString(System::SharedPtr<System::IFormatProvider> provider)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | 提供特定于区域性格式信息的 [System::IFormatProvider](../../iformatprovider/) 接口实现。 |

### 返回值

一个等同于此实例值的 [System::String](../../string/) 实例。

## IConvertible::ToString() const 方法

C# [Object.ToString()](../../object/tostring/) 方法的类似实现。支持将自定义对象转换为字符串。

```cpp
virtual String System::Object::ToString() const
```

### 返回值

由最终类提供的 [String](../../string/) 表示。

## 另请参阅

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [IConvertible](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)