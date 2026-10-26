---
title: AddVideoFrame()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立新的影片框架，並將其新增至形狀集合的末端。
type: docs
weight: 209
url: /zh-hant/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) 方法

建立新的影片框架，並將其新增至形狀集合的末端。

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 新影片框架的 x 座標（以點為單位）。 |
| y | **float** | 新影片框架的 y 座標（以點為單位）。 |
| width | **float** | 新影片框架的寬度（以點為單位）。 |
| height | **float** | 新影片框架的高度（以點為單位）。 |
| fname | [System::String](../../../system/string/) | 要嵌入的影片檔案的路徑或名稱。 |

### 返回值

新建立的 [IVideoFrame](../../ivideoframe/)。

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) 方法

建立新的影片框架，並將其新增至形狀集合的末端。

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 新影片框架的 x 座標（以點為單位）。 |
| y | **float** | 新影片框架的 y 座標（以點為單位）。 |
| width | **float** | 新影片框架的寬度（以點為單位）。 |
| height | **float** | 新影片框架的高度（以點為單位）。 |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | 要嵌入影片框架的 [IVideo](../../ivideo/)。 |

### 返回值

新建立的 [IVideoFrame](../../ivideoframe/)。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IVideoFrame](../../ivideoframe/)
* 類別 [String](../../../system/string/)
* 類別 [ShapeCollection](../)
* 類別 [IVideo](../../ivideo/)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)