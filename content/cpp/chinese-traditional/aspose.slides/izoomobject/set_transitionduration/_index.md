---
title: set_TransitionDuration()
second_title: Aspose.Slides for C++ API 參考
description: "設定 Zoom 與投影片之間過渡的持續時間。寫入 float。預設值：1.0f"
type: docs
weight: 118
url: /zh-hant/aspose.slides/izoomobject/set_transitionduration/
---
## IZoomObject::set_TransitionDuration(float) 方法

設定 Zoom 與投影片之間過渡的持續時間。寫入 **float**。預設值：1.0f

```cpp
virtual void Aspose::Slides::IZoomObject::set_TransitionDuration(float value)=0
```

## 備註

如果未指定 (TransitionDur = 0)，則會使用目標投影片的過渡以及與該過渡相關的時間設定。

以下範例示範了如何變更 Zoom 與投影片之間過渡的持續時間：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## 另見

* 類別 [IZoomObject](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)