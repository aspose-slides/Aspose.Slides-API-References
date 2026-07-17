---
title: Write()
second_title: Aspose.Slides C++ API 参考
description: 如果封装模式为 binary，则将指定字节数组中指定子范围的字节写入流；否则将指定字节数组中指定子范围的字节转换为 char_type 类型并将结果写入流。不受支持！
type: docs
weight: 79
url: /zh/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

如果封装模式是 binary，则将指定字节数组中指定子范围的字节写入流；否则将指定字节数组中指定子范围的字节转换为 char_type 类型后再写入流。不受支持！

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要写入的字节的数组。 |
| offset | **int32_t** | 在 **buffer** 中子范围写入开始位置的 0 基索引。 |
| count | **int32_t** | 要写入的子范围中元素的数量。 |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

将指定字节数组中指定子范围的字节写入流。

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 包含要写入字节的数组视图 |
| offset | **int32_t** | 在 **buffer** 中子范围写入开始位置的 0 基索引 |
| count | **int32_t** | 要写入的子范围中元素的数量 |

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [BasicSTDIStreamWrapper](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)