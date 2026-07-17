---
title: Read()
second_title: Aspose.Slides for C++ API 参考
description: 从底层流读取指定数量的字节并将它们写入指定的字节数组。
type: docs
weight: 53
url: /zh/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

从底层流读取指定数量的字节并将它们写入指定的字节数组。

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 用于写入读取字节的字节数组 |
| offset | **int32_t** | 在 **buffer** 中以 0 为基准的起始写入位置 |
| count | **int32_t** | 要读取的字节数 |

### 返回值

读取的字节数

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

从底层流读取指定数量的字节并将它们写入指定的字节数组。

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 用于写入读取字节的字节数组 |
| offset | **int32_t** | 在 **buffer** 中以 0 为基准的起始写入位置 |
| count | **int32_t** | 要读取的字节数 |

### 返回值

读取的字节数

## 另请参阅

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [BufferedStream](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)