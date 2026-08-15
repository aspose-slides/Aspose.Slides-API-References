---
title: InsertClone()
second_title: Aspose.Slides for C++ API 參考手冊
description: 在集合的指定位置插入指定母投影片的副本。相關的版面配置投影片也會被複製。
type: docs
weight: 105
url: /zh-hant/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) 方法

在集合的指定位置插入指定母投影片的副本。也會複製相關的版面配置投影片。

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 新投影片的索引。 |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) 用於複製。 |

### 返回值

已插入的母投影片。

## 備註

以下範例顯示如何在另一個 PowerPoint [Presentation](../../presentation/) 中複製母投影片。
```cpp
// 實例化 Presentation 類別以載入來源簡報檔案
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// 實例化 Presentation 類別作為目的簡報（要複製投影片的地方）
auto destPres = System::MakeObject<Presentation>();

// 從來源簡報的投影片集合中實例化 ISlide，並同時取得
// 母投影片
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// 取得目的簡報的母投影片集合
auto masters = destPres->get_Masters();
// 將所需的母投影片從來源簡報複製到
// 目的簡報的母投影片集合中
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// 目的簡報的投影片集合
auto slides = destPres->get_Slides();
// 將來源投影片複製到目的投影片集合。
slides->AddClone(sourceSlide, iSlide, true);
// 將目的簡報儲存至磁碟
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMasterSlide](../../imasterslide/)
* 類別 [MasterSlideCollection](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)