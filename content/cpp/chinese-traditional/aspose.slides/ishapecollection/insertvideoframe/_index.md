---
title: InsertVideoFrame()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立新的影片框架，並將其插入至指定索引的形狀集合中。
type: docs
weight: 183
url: /zh-hant/aspose.slides/ishapecollection/insertvideoframe/
---
## IShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) 方法

建立一個新的影片框架，並將其插入到指定索引位置的形狀集合中。

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 用於插入影片框架的零基索引。 |
| x | **float** | 新影片框架的 x 座標，以點為單位。 |
| y | **float** | 新影片框架的 y 座標，以點為單位。 |
| width | **float** | 新影片框架的寬度，以點為單位。 |
| height | **float** | 新影片框架的高度，以點為單位。 |
| fname | [System::String](../../../system/string/) | 要嵌入的影片檔案的路徑或名稱。 |

### 返回值

新建立的 [IVideoFrame](../../ivideoframe/)。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideoFrame](../../ivideoframe/)
* Class [String](../../../system/string/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)