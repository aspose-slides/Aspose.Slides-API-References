---
title: get_BinaryData()
second_title: Aspose.Slides for C++ API 參考
description: "返回音訊資料的副本。若資料量龐大，請考慮使用 IAudio::GetStream 方法，以防止不必要地將音訊資料載入記憶體，甚至導致 OutOfMemoryException。唯讀 uint8_t[]."
type: docs
weight: 14
url: /zh-hant/aspose.slides/iaudio/get_binarydata/
---
## IAudio::get_BinaryData() 方法

返回音訊資料的副本。若資料量過大，請考慮使用 [IAudio::GetStream](../getstream/) 方法，以避免不必要地將音訊資料載入記憶體，甚至發生 OutOfMemoryException。唯讀 **uint8_t**[]。

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IAudio::get_BinaryData()=0
```

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [IAudio](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)