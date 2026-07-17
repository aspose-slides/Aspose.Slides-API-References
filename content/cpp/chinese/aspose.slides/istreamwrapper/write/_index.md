---
title: Write()
second_title: Aspose.Slides C++ API 参考
description: 将字节序列写入当前流，并将此流中的当前位置前移写入的字节数。
type: docs
weight: 144
url: /zh/aspose.slides/istreamwrapper/write/
---
## IStreamWrapper::Write(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) 方法

将字节序列写入当前流，并将此流中的当前位置前移写入的字节数。

```cpp
virtual void Aspose::Slides::IStreamWrapper::Write(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 字节数组 **uint8_t**[] |
| offset | **int32_t** | buffer 中以零为基准的字节偏移量，表示开始将字节复制到当前流 **int32_t** |
| count | **int32_t** | 要写入当前流的字节数 **int32_t** |

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [IStreamWrapper](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)