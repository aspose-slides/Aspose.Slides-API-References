---
title: AddClone()
second_title: Aspose.Slides for C++ API 參考
description: 將指定版面投影片的副本新增至集合的末端。
type: docs
weight: 1
url: /zh-hant/aspose.slides/imasterlayoutslidecollection/addclone/
---
## IMasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) 方法

將指定版面投影片的副本新增至集合的末端。

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 用於克隆。 |

### 返回值

已新增的投影片。

## 備註

1) 新的版面將與此版面投影片集合的父主投影片連結。 因此這相當於在 PowerPoint 中使用「使用目標主題」選項的複製/貼上。  
2) 此方法的類似功能是透過 [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) 屬性存取的 [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) 方法。 

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ILayoutSlide](../../ilayoutslide/)
* 類別 [IMasterLayoutSlideCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)