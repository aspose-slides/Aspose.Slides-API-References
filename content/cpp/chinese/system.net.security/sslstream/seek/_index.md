---
title: Seek()
second_title: Aspose.Slides C++ API 参考
description: 设置当前对象表示的流的位置。
type: docs
weight: 365
url: /zh/system.net.security/sslstream/seek/
---
## SslStream::Seek(int64_t, IO::SeekOrigin) 方法

设置当前对象表示的流的位置。

```cpp
int64_t System::Net::Security::SslStream::Seek(int64_t offset, IO::SeekOrigin origin) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| offset | **int64_t** | 相对于 **origin** 指定的位置的字节偏移量 |
| origin | [IO::SeekOrigin](../../../system.io/seekorigin/) | 指定计算偏移量的起始位置和方向 |

### 返回值

流的新位置

## 另见

* 枚举 [SeekOrigin](../../../system.io/seekorigin/)
* 类 [SslStream](../)
* 命名空间 [System::Net::Security](../../)
* 库 [Aspose.Slides](../../../)