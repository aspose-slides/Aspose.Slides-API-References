---
title: GetObjectStoringLocation()
second_title: Aspose.Slides for C++ API 参考
description: 确定对象应存储的位置。此方法针对每个对象 id 调用一次。不能保证不会出现具有相同 data、semanticName 和 contentType 但 id 不同的两个对象。
type: docs
weight: 1
url: /zh/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) 方法

确定对象应存储的位置。此方法针对每个对象 id 调用一次。不能保证不会出现具有相同 data、semanticName 和 contentType 但 id 不同的两个对象。

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | **int32_t** | 对象标识。此标识在整个保存操作中唯一。 |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 对象的二进制数据。如果对象二进制数据尚未生成，则此参数可以为空。 |
| semanticName | [System::String](../../../system/string/) | 一些简短的文本，描述对象的含义。控制器可以将其用作外部对象名称的一部分，但确保名称唯一且仅包含允许字符的职责在调度器。 |
| contentType | [System::String](../../../system/string/) | 对象的 MIME 类型。 |
| recomendedExtension | [System::String](../../../system/string/) | 文件名扩展名，针对该 MIME 类型的推荐扩展名。 |

### 返回值

决策

## 参见

* 枚举 [LinkEmbedDecision](../../linkembeddecision/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [ILinkEmbedController](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)