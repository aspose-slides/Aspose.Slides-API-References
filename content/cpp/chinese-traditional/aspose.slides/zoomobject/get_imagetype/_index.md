---
title: get_ImageType()
second_title: Aspose.Slides C++ API 參考
description: "取得縮放物件的圖像類型。閱讀 ZoomImageType。預設值：Preview"
type: docs
weight: 1
url: /zh-hant/aspose.slides/zoomobject/get_imagetype/
---
## ZoomObject::get_ImageType() 方法


取得縮放物件的圖像類型。閱讀 [ZoomImageType](../../zoomimagetype/)。預設值：Preview

```cpp
ZoomImageType Aspose::Slides::ZoomObject::get_ImageType() override
```

## 備註


指定 Zoom 物件是使用投影片預覽還是封面圖像。

以下範例示範將 Image Type 變更為 Preview 值。在此情況下，Zoom 物件的目前圖像會變更為投影片圖像：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## 另請參閱

* 列舉 [ZoomImageType](../../zoomimagetype/)
* 類別 [ZoomObject](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)