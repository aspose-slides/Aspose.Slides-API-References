---
title: Write()
second_title: Aspose.Slides for C++ API 参考
description: 如果包装模式是二进制，则将指定字节数组中指定子范围的字节写入流；否则，将指定字节数组中指定子范围的字节转换为 char_type 类型，然后将结果写入流。
type: docs
weight: 79
url: /zh/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

如果包装模式为二进制，则将指定字节数组中指定子范围的字节写入流；否则，将指定字节数组中指定子范围的字节转换为 char_type 类型并将结果写入流。

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要写入的字节的数组 |
| offset | **int32_t** | 在 **buffer** 中子范围写入起始位置的基于0的索引 |
| count | **int32_t** | 要写入的子范围中元素的数量 |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

将指定字节数组中指定子范围的字节写入流。

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 包含要写入的字节的数组视图 |
| offset | **int32_t** | 在 **buffer** 中子范围写入起始位置的基于0的索引 |
| count | **int32_t** | 要写入的子范围中元素的数量 |

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [BasicSTDIOStreamWrapper](../)
* 命名空间 [System::IO](../../)
* Library [Aspose.Slides](../../../)