---
title: BitVector32
second_title: Aspose.Slides for C++ API 参考
description: 提供一个简单轻量的位向量，可轻松进行整数或布尔访问 32 位存储。
type: docs
weight: 1
url: /zh/system.collections.specialized/bitvector32/
---
## BitVector32 类

提供一个简单轻量的位向量，可轻松进行整数或 [Boolean](../../system/boolean/) 访问 32 位存储。

```cpp
class BitVector32
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [BitVector32](./bitvector32/)() | 初始化 [BitVector32](./) 的新空实例。 |
| [BitVector32](./bitvector32/)(**int32_t**) | 使用指定的内部数据初始化 [BitVector32](./) 结构的新实例。 |
| [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | 使用指定值中的信息初始化 [BitVector32](./) 结构的新实例。 |
| static **int32_t** [CreateMask](./createmask/)() | 创建系列中的第一个掩码。 |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | 创建系列中的下一个掩码。 |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | 使用指定的最大值创建系列中的第一个部分。 |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | 使用指定的最大值创建系列中的下一个部分。 |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | 确定指定的对象是否与当前对象相同。 |
| **int32_t** [get_Data](./get_data/)() | 返回存储在此位向量中的原始数据…… |
| **int32_t** [GetHashCode](./gethashcode/)() const | 返回当前对象的哈希码。 |
| **bool** [idx_get](./idx_get/)(**int32_t**) | 获取一个值，指示所有指定的位是否已设置。 |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | 获取指定部分的值。 |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | 设置一个值，指示所有指定的位是否已设置。 |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | 设置指定部分的值。 |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | 将由 value 参数表示的值转换为字符串。 |
| [String](../../system/string/) [ToString](./tostring/)() const | 将当前对象表示的值转换为字符串。 |

## 参见

* 命名空间 [System::Collections::Specialized](../)
* 库 [Aspose.Slides](../../)