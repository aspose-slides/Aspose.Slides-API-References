---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 將 Tab 新增至集合。
type: docs
weight: 53
url: /zh-hant/aspose.slides/tabcollection/add/
---
## TabCollection::Add(double, TabAlignment) 方法


將 [Tab](../../tab/) 新增至集合。

```cpp
System::SharedPtr<ITab> Aspose::Slides::TabCollection::Add(double position, TabAlignment align) override
```


### 返回值

已新增的 tab。

## TabCollection::Add(System::SharedPtr\<ITab\>) 方法


將 [Tab](../../tab/) 新增至集合。

```cpp
int32_t Aspose::Slides::TabCollection::Add(System::SharedPtr<ITab> value) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | 要在集合末端加入的 [Tab](../../tab/) 物件。 |

### 返回值

已加入的 tab 的索引。

## 另見

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ITab](../../itab/)
* 類別 [TabCollection](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)