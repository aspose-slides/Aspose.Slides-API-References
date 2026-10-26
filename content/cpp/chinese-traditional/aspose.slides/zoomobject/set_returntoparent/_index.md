---
title: set_ReturnToParent()
second_title: Aspose.Slides for C++ API 參考
description: "設定投影片放映中的導航行為。寫入 bool。預設值：false"
type: docs
weight: 40
url: /zh-hant/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) 方法


設定投影片放映中的導航行為。寫入 **bool**。預設值：false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## 備註


屬性的 True 值指定投影片放映中的返回至父層導航行為。 

範例： 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## 另見

* 類別 [ZoomObject](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)