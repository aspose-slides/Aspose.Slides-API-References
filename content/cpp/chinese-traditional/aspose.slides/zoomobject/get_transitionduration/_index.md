---
title: get_TransitionDuration()
second_title: Aspose.Slides for C++ API 參考文件
description: "取得 Zoom 與投影片之間過渡的持續時間。讀取 float。預設值：1.0f"
type: docs
weight: 105
url: /zh-hant/aspose.slides/zoomobject/get_transitionduration/
---
## ZoomObject::get_TransitionDuration() 方法

取得 Zoom 與投影片之間過渡的持續時間。讀取 **float**。預設值：1.0f

```cpp
float Aspose::Slides::ZoomObject::get_TransitionDuration() override
```

## 備註

如果未指定 (TransitionDur = 0)，將使用目標投影片的過渡效果以及與該過渡相關的時間設定。

以下範例示範如何變更 Zoom 與投影片之間過渡的持續時間：

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## 另請參閱

* 類別 [ZoomObject](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)