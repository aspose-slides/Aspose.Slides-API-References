---
title: Write()
second_title: Aspose.Slides for C++ API 參考文件
description: 將一系列位元組寫入目前的串流，並依寫入的位元組數量將此串流中的當前位置前進。
type: docs
weight: 144
url: /zh-hant/aspose.slides/istreamwrapper/write/
---
## IStreamWrapper::Write(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) 方法

將一系列位元組寫入目前的串流，並依寫入的位元組數量將目前在此串流中的位置前進。

```cpp
virtual void Aspose::Slides::IStreamWrapper::Write(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 位元組陣列 **uint8_t**[] |
| offset | **int32_t** | 緩衝區中以零為基礎的位元組偏移量，從此開始將位元組複製到目前的串流 **int32_t** |
| count | **int32_t** | 寫入目前串流的位元組數量 **int32_t** |

## 參見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [IStreamWrapper](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)