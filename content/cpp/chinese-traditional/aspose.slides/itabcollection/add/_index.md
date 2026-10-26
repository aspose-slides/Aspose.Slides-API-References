---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 將 Tab 新增至集合。
type: docs
weight: 14
url: /zh-hant/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) method

將 [Tab](../../tab/) 新增至集合。

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) 位置。 |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) 對齊方式。 |

### 傳回值

已新增的分頁。

## ITabCollection::Add(System::SharedPtr\<ITab\>) method

將 [Tab](../../tab/) 新增至集合。

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | 要在集合末端加入的 [Tab](../../tab/) 物件。 |

### 傳回值

分頁被加入的索引。

## 參見

* 列舉 [TabAlignment](../../tabalignment/)
* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ITab](../../itab/)
* 類別 [ITabCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)