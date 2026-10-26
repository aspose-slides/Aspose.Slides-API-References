---
title: AddClone()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的佈局投影片的副本新增至簡報中。
type: docs
weight: 1
url: /zh-hant/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) 方法

將指定的版面投影片的副本新增至簡報中。

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 要複製。 |

### 返回值

已加入的投影片。

## 備註

在不同簡報之間複製版面時，版面的母片也會被複製，以保留來源的格式。系統使用內部註冊表來追蹤自動複製的母片，以防止同一母片投影片產生多個複製。手動複製母片投影片既不會被阻止，也不會被註冊。

## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) 方法

將指定的版面投影片的副本新增至簡報中。

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 要複製。 |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 新版面的母片投影片。 |

### 返回值

已加入的投影片。

## 備註

1) 新版面將會與目標簡報中已定義的母片連結。因此這相當於在 PowerPoint 中使用「使用目標佈景主題」選項的複製/貼上。 2) 此方法的類似方法是使用 [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) 屬性存取的 [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/) 方法。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ILayoutSlide](../../ilayoutslide/)
* 類別 [GlobalLayoutSlideCollection](../)
* 類別 [IMasterSlide](../../imasterslide/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)