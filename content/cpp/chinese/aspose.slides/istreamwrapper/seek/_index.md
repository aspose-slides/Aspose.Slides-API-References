---
title: Seek()
second_title: Aspose.Slides for C++ API 参考
description: 设置当前流中的位置
type: docs
weight: 131
url: /zh/aspose.slides/istreamwrapper/seek/
---
## IStreamWrapper::Seek(int64_t, System::IO::SeekOrigin) 方法

设置当前流中的位置

```cpp
virtual int64_t Aspose::Slides::IStreamWrapper::Seek(int64_t offset, System::IO::SeekOrigin origin)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| offset | **int64_t** | 相对于 origin 参数的字节偏移量 **int64_t** |
| origin | [System::IO::SeekOrigin](../../../system.io/seekorigin/) | 类型为 [System::IO::SeekOrigin](../../../system.io/seekorigin/) 的值，指示用于获取新位置的参考点 |

### 返回值

当前流中新位置 **int64_t**

## 另请参见

* 枚举 [SeekOrigin](../../../system.io/seekorigin/)
* 类 [IStreamWrapper](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)