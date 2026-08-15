---
title: set_TransitionDuration()
second_title: Aspose.Slides for C++ API 參考文件
description: "設定 Zoom 與投影片之間過渡的持續時間。寫入 float。預設值：1.0f"
type: docs
weight: 118
url: /zh-hant/aspose.slides/zoomobject/set_transitionduration/
---
## ZoomObject::set_TransitionDuration(float) method


設定 Zoom 與投影片之間過渡的持續時間。寫入 **float**。預設值：1.0f

```cpp
void Aspose::Slides::ZoomObject::set_TransitionDuration(float value) override
```

## 備註


如果未指定 (TransitionDur = 0)，將使用目標投影片的過渡效果以及與該過渡相關的時間設定。 

此範例示範變更 Zoom 與投影片之間過渡的持續時間: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## 參見

* 類別 [ZoomObject](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)