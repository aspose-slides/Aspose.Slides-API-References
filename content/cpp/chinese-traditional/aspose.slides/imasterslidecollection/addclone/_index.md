---
title: AddClone()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的母投影片副本加入集合的末端。也會複製已連結的版面配置投影片。
type: docs
weight: 53
url: /zh-hant/aspose.slides/imasterslidecollection/addclone/
---
## IMasterSlideCollection::AddClone(System::SharedPtr\<IMasterSlide\>) 方法

Adds a copy of a specified master slide to the end of the collection. Linked layout slides will be copied too.

```cpp
virtual System::SharedPtr<IMasterSlide> Aspose::Slides::IMasterSlideCollection::AddClone(System::SharedPtr<IMasterSlide> sourceMaster)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) 以克隆。 |

### 傳回值

已加入的投影片。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMasterSlide](../../imasterslide/)
* 類別 [IMasterSlideCollection](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)