---
title: FindShapesByPlaceholderType()
second_title: Aspose.Slides for C++ API 參考文件
description: 搜尋指定投影片上符合給定占位類型的所有圖形。
type: docs
weight: 14
url: /zh-hant/aspose.slides.util/slideutil/findshapesbyplaceholdertype/
---
## SlideUtil::FindShapesByPlaceholderType(System::SharedPtr\<IBaseSlide\>, PlaceholderType) 方法

搜尋指定投影片上符合給定占位類型的所有圖形。

```cpp
static System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::Util::SlideUtil::FindShapesByPlaceholderType(System::SharedPtr<IBaseSlide> slide, PlaceholderType placeholderType)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | 要搜尋圖形的投影片。 |
| placeholderType | [PlaceholderType](../../../aspose.slides/placeholdertype/) | 用於依占位類型過濾圖形的類型。 |

### 回傳值

回傳符合指定占位類型的 [IShape](../../../aspose.slides/ishape/) 物件陣列。

## 另請參閱

* 列舉 [PlaceholderType](../../../aspose.slides/placeholdertype/)
* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IShape](../../../aspose.slides/ishape/)
* 類別 [IBaseSlide](../../../aspose.slides/ibaseslide/)
* 類別 [SlideUtil](../)
* 命名空間 [Aspose::Slides::Util](../../)
* 函式庫 [Aspose.Slides](../../../)