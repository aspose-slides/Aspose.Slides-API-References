---
title: ToDateTime()
second_title: Aspose.Slides for C++ API 参考
description: "将此实例的值转换为等效的 System::DateTime，使用指定的特定于区域的格式信息。"
type: docs
weight: 183
url: /zh/system/iconvertible/todatetime/
---
## IConvertible::ToDateTime(System::SharedPtr\<System::IFormatProvider\>) 方法

将此实例的值转换为等效的 [System::DateTime](../../datetime/)，使用指定的特定于区域的格式信息。

```cpp
virtual System::DateTime System::IConvertible::ToDateTime(System::SharedPtr<System::IFormatProvider> provider)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | 提供特定于区域的格式信息的 [System::IFormatProvider](../../iformatprovider/) 接口实现。 |

### 返回值

一个等价于此实例值的 [System::DateTime](../../datetime/) 实例。

## 参见

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [DateTime](../../datetime/)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [IConvertible](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)