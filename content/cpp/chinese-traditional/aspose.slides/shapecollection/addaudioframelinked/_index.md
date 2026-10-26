---
title: AddAudioFrameLinked()
second_title: Aspose.Slides C++ API 參考文件
description: 建立一個連結至外部音訊檔的音訊框架，並將其加入形狀集合的末端。
type: docs
weight: 261
url: /zh-hant/aspose.slides/shapecollection/addaudioframelinked/
---
## ShapeCollection::AddAudioFrameLinked(float, float, float, float, System::String) method

建立一個連結至外部音訊檔的音訊框架，並將其加入形狀集合的末端。

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameLinked(float x, float y, float width, float height, System::String fname) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 新音訊框架的 x 座標，單位為點。 |
| y | **float** | 新音訊框架的 y 座標，單位為點。 |
| width | **float** | 新音訊框架的寬度，單位為點。 |
| height | **float** | 新音訊框架的高度，單位為點。 |
| fname | [System::String](../../../system/string/) | 要連結的外部音訊檔案的路徑或名稱。 |

### 回傳值

新建立的 [IAudioFrame](../../iaudioframe/)。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IAudioFrame](../../iaudioframe/)
* 類別 [String](../../../system/string/)
* 類別 [ShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)