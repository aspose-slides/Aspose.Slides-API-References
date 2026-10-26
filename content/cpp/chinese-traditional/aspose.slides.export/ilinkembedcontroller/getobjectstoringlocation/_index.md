---
title: GetObjectStoringLocation()
second_title: Aspose.Slides for C++ API 參考文件
description: 確定物件應儲存的位置。此方法會針對每個物件 id 呼叫一次。無法保證不會有具有相同 data、semanticName 與 contentType 但 id 不同的兩個物件。
type: docs
weight: 1
url: /zh-hant/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) method

確定物件應儲存的位置。此方法會針對每個物件 id 呼叫一次。無法保證不會有具有相同 data、semanticName 與 contentType 但 id 不同的兩個物件。

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| id | **int32_t** | 物件 id。此 id 在整個儲存操作中唯一。 |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 物件二進位資料。若尚未產生物件二進位資料，此參數可以為 null。 |
| semanticName | [System::String](../../../system/string/) | 描述物件含義的簡短文字。控制器可能將其作為外部物件名稱的一部分，但由調度器負責確保名稱唯一且僅包含允許的字元。 |
| contentType | [System::String](../../../system/string/) | 物件的 MIME 類型。 |
| recomendedExtension | [System::String](../../../system/string/) | 針對此 MIME 類型建議的檔案副檔名。 |

### 返回值

決策

## 另請參閱

* Enum [LinkEmbedDecision](../../linkembeddecision/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [ILinkEmbedController](../)
* 命名空間 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)