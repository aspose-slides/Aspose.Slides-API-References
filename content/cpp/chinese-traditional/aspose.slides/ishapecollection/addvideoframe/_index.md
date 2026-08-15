---
title: AddVideoFrame()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個新影片框架，並將其添加至形狀集合的末端。
type: docs
weight: 170
url: /zh-hant/aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) 方法

建立一個新影片框架，並將其添加至形狀集合的末端。

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新影片框架的 x 座標，以點為單位。 |
| y | **float** | 新影片框架的 y 座標，以點為單位。 |
| width | **float** | 新影片框架的寬度，以點為單位。 |
| height | **float** | 新影片框架的高度，以點為單位。 |
| fname | [System::String](../../../system/string/) | 要嵌入的影片檔案的路徑或名稱。 |

### 返回值

新建立的 [IVideoFrame](../../ivideoframe/)。

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) 方法

建立一個新影片框架，並將其添加至形狀集合的末端。

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新影片框架的 x 座標，以點為單位。 |
| y | **float** | 新影片框架的 y 座標，以點為單位。 |
| width | **float** | 新影片框架的寬度，以點為單位。 |
| height | **float** | 新影片框架的高度，以點為單位。 |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | 要嵌入影片框架的 [IVideo](../../ivideo/)。 |

### 返回值

新建立的 [IVideoFrame](../../ivideoframe/)。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IVideoFrame](../../ivideoframe/)
* 類別 [String](../../../system/string/)
* 類別 [IShapeCollection](../)
* 類別 [IVideo](../../ivideo/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)