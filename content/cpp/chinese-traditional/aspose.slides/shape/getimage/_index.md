---
title: GetImage()
second_title: Aspose.Slides for C++ API 參考
description: "傳回形狀縮圖。 ShapeThumbnailBounds::Shape 形狀縮圖邊界類型預設使用。"
type: docs
weight: 651
url: /zh-hant/aspose.slides/shape/getimage/
---
## Shape::GetImage() 方法

返回形狀縮圖。 [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) 形狀縮圖邊界類型預設使用。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```

### 返回值

[Shape](../) 縮圖。

## Shape::GetImage(ShapeThumbnailBounds, float, float) 方法

返回形狀縮圖。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) 縮圖邊界類型。 |
| scaleX | **float** | X 比例 |
| scaleY | **float** | Y 比例 |

### 返回值

[Shape](../) 縮圖或 null，當使用 [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) 且形狀沒有可見元素時。

## 另請參閱

* 列舉 [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IImage](../../iimage/)
* 類別 [Shape](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)