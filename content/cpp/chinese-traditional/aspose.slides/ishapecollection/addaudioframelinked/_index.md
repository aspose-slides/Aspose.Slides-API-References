---
title: AddAudioFrameLinked()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立一個連結至外部音訊檔案的新音訊框架，並將其新增至圖形集合的末端。
type: docs
weight: 222
url: /zh-hant/aspose.slides/ishapecollection/addaudioframelinked/
---
## IShapeCollection::AddAudioFrameLinked(float, float, float, float, System::String) method


建立一個連結至外部音訊檔案的新音訊框架，並將其新增至圖形集合的末端。

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameLinked(float x, float y, float width, float height, System::String fname)=0
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | **float** | 新音訊框架的 x 座標（以點為單位）。 |
| y | **float** | 新音訊框架的 y 座標（以點為單位）。 |
| width | **float** | 新音訊框架的寬度（以點為單位）。 |
| height | **float** | 新音訊框架的高度（以點為單位）。 |
| fname | [System::String](../../../system/string/) | 要連結的外部音訊檔案的路徑或名稱。 |

### 回傳值

新建立的 [IAudioFrame](../../iaudioframe/)。

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IAudioFrame](../../iaudioframe/)
* 類別 [String](../../../system/string/)
* 類別 [IShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)