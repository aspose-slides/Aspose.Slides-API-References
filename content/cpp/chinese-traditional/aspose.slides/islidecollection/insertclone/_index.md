---
title: InsertClone()
second_title: Aspose.Slides for C++ API 參考
description: 在集合的指定位置插入指定投影片的副本。
type: docs
weight: 27
url: /zh-hant/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) 方法

將指定投影片的副本插入到集合的指定位置。

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 新投影片的索引。 |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 以克隆。 |

### 回傳值

已插入的投影片。

## 備註

在不同簡報之間克隆投影片時，投影片的母片也可能會被克隆。使用內部註冊表來追蹤自動克隆的母片，以防止同一母片被多次克隆。手動克隆母片既不會被阻止，也不會被登錄。如果需要對克隆過程有更細緻的控制，請使用 [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) 或 [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) 來克隆投影片，並使用 [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) 來克隆母片。

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) 方法

將指定投影片的副本插入到集合的指定位置。

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 新投影片的索引。 |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 以克隆。 |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | 新投影片的版面配置投影片。 |

### 回傳值

已插入的投影片。

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) 方法

將指定來源投影片的副本插入到集合的指定位置。將自動從指定的母片中選取適當的版面配置（適當的版面配置是與來源投影片的版面配置具有相同類型或名稱的版面配置）。如果沒有適當的版面配置，則會克隆來源投影片的版面配置（若 allowCloneMissingLayout 為 true）或拋出 PptxEditException（若 allowCloneMissingLayout 為 false）。

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 新投影片的索引。 |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 以克隆。 |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master slide for a new slide. |
| allowCloneMissingLayout | **bool** | 如果在指定的母片中沒有適當的版面配置，則會克隆來源投影片的版面配置（若 allowCloneMissingLayout 為 true）或拋出 PptxEditException（若 allowCloneMissingLayout 為 false）。 |

### 回傳值

已插入的投影片。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ISlide](../../islide/)
* 類別 [ISlideCollection](../)
* 類別 [ILayoutSlide](../../ilayoutslide/)
* 類別 [IMasterSlide](../../imasterslide/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)