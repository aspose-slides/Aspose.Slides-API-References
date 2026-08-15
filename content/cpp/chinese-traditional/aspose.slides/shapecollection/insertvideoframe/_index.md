---
title: InsertVideoFrame()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個新的影片框架，並將其插入至指定索引的形狀集合中。
type: docs
weight: 222
url: /zh-hant/aspose.slides/shapecollection/insertvideoframe/
---
## ShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) 方法

建立一個新的影片框架，並將其插入至指定索引的形狀集合中。

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 插入影片框架的零基索引。 |
| x | **float** | 新影片框架的 x 座標，單位為點。 |
| y | **float** | 新影片框架的 y 座標，單位為點。 |
| width | **float** | 新影片框架的寬度，單位為點。 |
| height | **float** | 新影片框架的高度，單位為點。 |
| fname | [System::String](../../../system/string/) | 要嵌入的影片檔案的路徑或名稱。 |

### 返回值

新建立的 [IVideoFrame](../../ivideoframe/)。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IVideoFrame](../../ivideoframe/)
* 類別 [String](../../../system/string/)
* 類別 [ShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)