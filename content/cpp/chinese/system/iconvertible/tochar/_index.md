---
title: ToChar()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的特定文化格式信息，将此实例的值转换为等效的 Unicode 字符。
type: docs
weight: 27
url: /zh/system/iconvertible/tochar/
---
## IConvertible::ToChar(System::SharedPtr\<System::IFormatProvider\>) 方法


将此实例的值转换为等效的 Unicode 字符，使用指定的特定文化格式信息。

```cpp
virtual char_t System::IConvertible::ToChar(System::SharedPtr<System::IFormatProvider> provider)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | 一个 [System::IFormatProvider](../../iformatprovider/) 接口实现，提供特定文化的格式化信息。 |

### 返回值

一个等价于此实例值的 Unicode 字符。

## 另请参阅

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [IConvertible](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)