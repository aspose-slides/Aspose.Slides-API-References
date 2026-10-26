---
title: get_ImageType()
second_title: Aspose.Slides for C++ API 參考文件
description: "取得縮放物件的影像類型。請閱讀 ZoomImageType。預設值：Preview"
type: docs
weight: 1
url: /zh-hant/aspose.slides/izoomobject/get_imagetype/
---
## IZoomObject::get_ImageType() 方法


取得縮放物件的影像類型。請閱讀 [ZoomImageType](../../zoomimagetype/)。預設值：Preview

```cpp
virtual ZoomImageType Aspose::Slides::IZoomObject::get_ImageType()=0
```

## 備註


指定 Zoom 物件是使用投影片預覽還是封面影像。 

此範例示範將 Image Type 變更為 Preview 值。此時 Zoom 物件的目前影像會變更為投影片影像： 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## 另請參閱

* 列舉 [ZoomImageType](../../zoomimagetype/)
* 類別 [IZoomObject](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)