---
title: Seek()
second_title: Aspose.Slides for C++ API 参考
description: 设置当前对象所表示的流的位置。
type: docs
weight: 79
url: /zh/system.io/bufferedstream/seek/
---
## BufferedStream::Seek(int64_t, SeekOrigin) 方法

设置当前对象所表示的流的位置。

```cpp
virtual int64_t System::IO::BufferedStream::Seek(int64_t offset, SeekOrigin origin) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| offset | **int64_t** | 相对于 **origin** 指定位置的字节偏移量 |
| origin | [SeekOrigin](../../seekorigin/) | 指定计算偏移量的起始位置和方向 |

### 返回值

流的新位置

## 另请参见

* Enum [SeekOrigin](../../seekorigin/)
* 类 [BufferedStream](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)