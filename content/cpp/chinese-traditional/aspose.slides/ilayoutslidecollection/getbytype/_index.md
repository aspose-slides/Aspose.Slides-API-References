---
title: GetByType()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回指定類型的第一個版面投影片。
type: docs
weight: 14
url: /zh-hant/aspose.slides/ilayoutslidecollection/getbytype/
---
## ILayoutSlideCollection::GetByType(SlideLayoutType) 方法

傳回指定類型的第一個版面投影片。

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::ILayoutSlideCollection::GetByType(SlideLayoutType type)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | [SlideLayoutType](../../slidelayouttype/) | 要尋找的版面投影片類型。 |

### 回傳值

[ILayoutSlide](../../ilayoutslide/) 具有指定類型的版面投影片，若未找到版面則傳回 null。

## 參見

* 列舉 [SlideLayoutType](../../slidelayouttype/)
* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ILayoutSlide](../../ilayoutslide/)
* 類別 [ILayoutSlideCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)