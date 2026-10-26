---
title: set_ReturnToParent()
second_title: Aspose.Slides for C++ API 參考文件
description: "設定投影片放映時的導覽行為。寫入 bool。預設值：false"
type: docs
weight: 40
url: /zh-hant/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) 方法

設定投影片放映時的導覽行為。寫入 **bool**。預設值：false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## 備註

True 值表示在投影片放映時返回父層的導覽行為。

範例：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## 另見

* 類別 [IZoomObject](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)