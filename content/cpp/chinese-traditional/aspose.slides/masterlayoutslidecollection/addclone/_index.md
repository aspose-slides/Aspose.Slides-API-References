---
title: AddClone()
second_title: Aspose.Slides for C++ API 參考
description: 將指定版面投影片的副本新增至集合的末端。
type: docs
weight: 1
url: /zh-hant/aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) 方法

Adds a copy of a specified layout slide to the end of the collection.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 要克隆的。 |

### 返回值

已添加的投影片。

## 備註

1) 新的版面配置將與此版面投影片集合的父母主投影片連結。因此，這相當於在 PowerPoint 中使用「Use Destination Theme」選項的複製/貼上。 2) 此方法的類似方法是 [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/)，可透過 [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) 屬性存取。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ILayoutSlide](../../ilayoutslide/)
* 類別 [MasterLayoutSlideCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)