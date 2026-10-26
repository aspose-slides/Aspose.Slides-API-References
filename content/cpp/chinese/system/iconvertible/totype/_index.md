---
title: ToType()
second_title: Aspose.Slides for C++ API 参考
description: "将此实例的值转换为指定 System::Type 的 System::Object，具有等效的值，使用指定的特定于区域设置的格式信息。"
type: docs
weight: 209
url: /zh/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) 方法

将此实例的值转换为指定 System::Type 的 [System::Object](../../object/)，该类型具有等效的值，使用指定的特定于区域设置的格式信息。

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | 此实例的值将被转换到的 System::Type。 |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | [System::IFormatProvider](../../iformatprovider/) 接口实现，提供特定于区域设置的格式信息。 |

### 返回值

一个类型为 conversionType、值等同于此实例值的 [System::Object](../../object/) 实例。

## 另请参阅

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [Object](../../object/)
* 类 [TypeInfo](../../typeinfo/)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [IConvertible](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)