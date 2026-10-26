---
title: Read()
second_title: Aspose.Slides for C++ API 参考
description: 如果包装模式是二进制，则从流中读取指定数量的字节；否则读取指定数量的字符并将其转换为 uint8_t 类型。将读取的结果写入指定的字节数组。
type: docs
weight: 66
url: /zh/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法


如果包装模式是二进制，则从流中读取指定数量的字节；否则读取指定数量的字符并将其转换为 **uint8_t** 类型。将读取的结果写入指定的字节数组。

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 用于写入读取字节的字节数组 |
| offset | **int32_t** | 在 **buffer** 中的基于 0 的起始写入位置 |
| count | **int32_t** | 要读取的字节数量 |

### 返回值

读取的字节或字符数量

## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法


从流中读取指定数量的字节并将其写入指定的字节数组。

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 用于写入读取字节的字节数组视图 |
| offset | **int32_t** | 在 **buffer** 中的基于 0 的起始写入位置 |
| count | **int32_t** | 要读取的字节数量 |

### 返回值

读取的字节数量

## 另见

* 类型别名 [ArrayPtr](../../../system/arrayptr/)
* 类 [BasicSTDIStreamWrapper](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)