---
title: get_ReturnToParent()
second_title: Aspose.Slides for C++ API 參考
description: "取得投影片放映時的導覽行為。讀取 bool。預設值：false"
type: docs
weight: 27
url: /zh-hant/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() 方法

取得投影片放映時的導覽行為。讀取 **bool**。預設值：false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## 備註

屬性的 true 值表示在投影片放映中返回父項的導覽行為。

範例：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## 另請參閱

* 類別 [IZoomObject](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)