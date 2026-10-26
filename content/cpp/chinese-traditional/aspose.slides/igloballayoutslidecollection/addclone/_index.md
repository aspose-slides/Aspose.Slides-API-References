---
title: AddClone()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定版面投影片的副本新增至簡報。
type: docs
weight: 1
url: /zh-hant/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) 方法

將指定版面投影片的副本新增至簡報。

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 以供複製。 |

### 回傳值

已新增的投影片。

## 備註

在不同簡報之間複製版面時，也會複製版面的母片以保留來源格式。內部註冊表用於追蹤自動複製的母片，以防止同一母片投影片產生多個副本。手動複製母片投影片既不會被阻止，也不會被註冊。

## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) 方法

將指定版面投影片的副本新增至簡報。

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 以供複製。 |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 新版面的母片投影片。 |

### 回傳值

已新增的投影片。

## 備註

新的版面將與目標簡報中定義的母片連結。因此，這相當於在 PowerPoint 中使用「使用目標佈景主題」選項的複製/貼上。

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ILayoutSlide](../../ilayoutslide/)
* 類別 [IGlobalLayoutSlideCollection](../)
* 類別 [IMasterSlide](../../imasterslide/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)