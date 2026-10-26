---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個連結至外部音訊檔案的新音訊框架，並將其插入至指定索引位置的形狀集合中。
type: docs
weight: 235
url: /zh-hant/aspose.slides/ishapecollection/insertaudioframelinked/
---
## IShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) 方法


建立一個連結至外部音訊檔案的新音訊框架，並將其插入到指定索引位置的形狀集合中。

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要插入音訊框架的零基索引。 |
| x | **float** | 新音訊框架的 x 座標，以點為單位。 |
| y | **float** | 新音訊框架的 y 座標，以點為單位。 |
| width | **float** | 新音訊框架的寬度，以點為單位。 |
| height | **float** | 新音訊框架的高度，以點為單位。 |
| fname | [System::String](../../../system/string/) | 要連結的外部音訊檔案的路徑或名稱。 |

### 返回值

新建立的 [IAudioFrame](../../iaudioframe/)。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IAudioFrame](../../iaudioframe/)
* 類別 [String](../../../system/string/)
* 類別 [IShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)