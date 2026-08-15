---
title: InsertClone()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的主投影片副本插入至集合的指定位置。相關聯的版面配置投影片也會被複製。
type: docs
weight: 66
url: /zh-hant/aspose.slides/imasterslidecollection/insertclone/
---
## IMasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) 方法

將指定的主投影片的副本插入至集合的指定位置。相關聯的版面配置投影片也會被複製。

```cpp
virtual System::SharedPtr<IMasterSlide> Aspose::Slides::IMasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 新投影片的索引。 |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) 用於克隆。 |

### 返回值

插入的主投影片。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMasterSlide](../../imasterslide/)
* 類別 [IMasterSlideCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)