---
title: Seek()
second_title: Aspose.Slides C++ API 参考
description: 设置当前对象所表示的流的位置。
type: docs
weight: 79
url: /zh/system.io/binarywriter/seek/
---
## BinaryWriter::Seek(int, System::IO::SeekOrigin) 方法


设置当前对象所表示的流的位置。

```cpp
int64_t System::IO::BinaryWriter::Seek(int offset, System::IO::SeekOrigin origin=System::IO::SeekOrigin::Begin)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| offset | int | 相对于 **origin** 指定的位置的字节偏移 |
| origin | [System::IO::SeekOrigin](../../seekorigin/) | 指定计算偏移量的起始位置和方向 |

### 返回值

流的新位置

## 参见

* 枚举 [SeekOrigin](../../seekorigin/)
* 类 [BinaryWriter](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)