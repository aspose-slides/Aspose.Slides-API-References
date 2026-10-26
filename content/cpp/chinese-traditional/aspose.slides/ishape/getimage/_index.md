---
title: GetImage()
second_title: Aspose.Slides C++ API 參考文件
description: "傳回形狀縮圖。預設使用 ShapeThumbnailBounds::Shape 形狀縮圖邊界類型。"
type: docs
weight: 547
url: /zh-hant/aspose.slides/ishape/getimage/
---
## IShape::GetImage() 方法


傳回形狀縮圖。 [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) 形狀縮圖邊界類型預設使用。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```


### 傳回值

[Shape](../../shape/) 縮圖。

## IShape::GetImage(ShapeThumbnailBounds, float, float) 方法


傳回形狀縮圖。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) 縮圖邊界類型。 |
| scaleX | **float** | X 比例 |
| scaleY | **float** | Y 比例 |

### 傳回值

[Shape](../../shape/) 縮圖，或在使用 [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) 且形狀沒有可見元素時返回 null。

## 另請參閱

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IImage](../../iimage/)
* 類別 [IShape](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)