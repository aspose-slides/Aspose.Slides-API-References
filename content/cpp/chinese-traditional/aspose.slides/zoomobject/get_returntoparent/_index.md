---
title: get_ReturnToParent()
second_title: Aspose.Slides for C++ API 參考手冊
description: "取得投影片放映中的導覽行為。唯讀 bool。預設值：false"
type: docs
weight: 27
url: /zh-hant/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() 方法


取得投影片放映中的導覽行為。只讀 **bool**。預設值：false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## 備註


屬性的 True 值表示在投影片放映中返回父層的導航行為。 

範例：
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## 另請參閱

* 類別 [ZoomObject](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)