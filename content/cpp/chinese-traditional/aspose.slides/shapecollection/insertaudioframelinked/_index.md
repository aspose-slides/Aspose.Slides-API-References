---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個鏈接到外部音訊檔案的新音訊框架，並將其插入到指定索引位置的形狀集合中。
type: docs
weight: 274
url: /zh-hant/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) 方法

建立一個鏈接到外部音訊檔案的新音訊框架，並將其插入到指定索引位置的形狀集合中。

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要插入音訊框架的零基索引。 |
| x | **float** | 新音訊框架的 x 座標，單位為點。 |
| y | **float** | 新音訊框架的 y 座標，單位為點。 |
| width | **float** | 新音訊框架的寬度，單位為點。 |
| height | **float** | 新音訊框架的高度，單位為點。 |
| fname | [System::String](../../../system/string/) | 要鏈接的外部音訊檔案的路徑或名稱。 |

### 返回值

新建立的 [IAudioFrame](../../iaudioframe/)。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IAudioFrame](../../iaudioframe/)
* 類別 [String](../../../system/string/)
* 類別 [ShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)