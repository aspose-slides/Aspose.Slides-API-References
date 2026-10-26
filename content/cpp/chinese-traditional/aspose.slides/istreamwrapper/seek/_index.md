---
title: Seek()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定目前串流中的位置
type: docs
weight: 131
url: /zh-hant/aspose.slides/istreamwrapper/seek/
---
## IStreamWrapper::Seek(int64_t, System::IO::SeekOrigin) method


設定目前串流中的位置

```cpp
virtual int64_t Aspose::Slides::IStreamWrapper::Seek(int64_t offset, System::IO::SeekOrigin origin)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| offset | **int64_t** | 相對於 origin 參數的位元組偏移量 **int64_t** |
| origin | [System::IO::SeekOrigin](../../../system.io/seekorigin/) | 類型為 [System::IO::SeekOrigin](../../../system.io/seekorigin/) 的值，指示用於獲取新位置的參考點 |

### Return Value

目前串流中的新位置 **int64_t**

## 另請參閱

* Enum [SeekOrigin](../../../system.io/seekorigin/)
* Class [IStreamWrapper](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)