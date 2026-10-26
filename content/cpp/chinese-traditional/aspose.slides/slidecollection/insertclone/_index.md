---
title: InsertClone()
second_title: Aspose.Slides for C++ API 參考
description: 將指定投影片的副本插入到集合的指定位置。
type: docs
weight: 66
url: /zh-hant/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) 方法

在集合的指定位置插入指定投影片的副本。

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 新投影片的索引。 |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 以進行複製。 |

### 傳回值

已插入的投影片。

## 備註

在不同簡報之間複製投影片時，投影片的母片也可能會被複製。內部註冊表用於追蹤自動複製的母片，以防止同一母片投影片產生多個複製本。手動複製母片既不會被阻止，也不會被註冊。若需要更精細的複製控制，可使用 [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) 或 [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) 來複製投影片，並使用 [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) 來複製母片。

以下範例說明如何在 [Presentation](../../presentation/) 內的其他位置進行複製。
```cpp
// 實例化表示簡報檔案的 Presentation 類別
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// 複製所需的投影片到同一簡報的投影片集合末端
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// 複製所需的投影片到同一簡報的指定索引位置
slides->InsertClone(2, slides->idx_get(1));
// 將修改後的簡報寫入磁碟
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
以下範例說明如何在 [Presentation](../../presentation/) 內的其他位置進行複製。
```cpp
// 實例化 Presentation 類別以載入來源簡報檔案
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// 實例化用於目標 PPTX 的 Presentation 類別（投影片將被複製到此處）
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// 將目標簡報寫入磁碟
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) 方法

在集合的指定位置插入指定投影片的副本。

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 新投影片的索引。 |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 以進行複製。 |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | 新投影片的版面配置投影片。 |

### 傳回值

已插入的投影片。

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) 方法

在集合的指定位置插入指定來源投影片的副本。系統會自動從指定的母片中選取相應的版面配置（相應的版面配置是與來源投影片的版面配置具有相同 Type 或 Name 的版面配置）。如果在指定的母片中找不到相應的版面配置，則會複製來源投影片的版面配置（若 allowCloneMissingLayout 為 true），否則會拋出 PptxEditException（若 allowCloneMissingLayout 為 false）。

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 新投影片的索引。 |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 以進行複製。 |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 新投影片的母片投影片。 |
| allowCloneMissingLayout | **bool** | 如果在指定的母片中沒有相應的版面配置，則會複製來源投影片的版面配置（若 allowCloneMissingLayout 為 true），否則會拋出 PptxEditException（若 allowCloneMissingLayout 為 false）。 |

### 傳回值

已插入的投影片。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [SlideCollection](../)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)