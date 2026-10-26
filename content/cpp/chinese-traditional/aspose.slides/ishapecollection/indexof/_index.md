---
title: IndexOf()
second_title: Aspose.Slides for C++ API 參考文件
description: 返回集合中指定圖形首次出現的零基索引。
type: docs
weight: 274
url: /zh-hant/aspose.slides/ishapecollection/indexof/
---
## IShapeCollection::IndexOf(System::SharedPtr\<IShape\>) 方法


返回指定圖形在集合中第一次出現的零基索引。

```cpp
virtual int32_t Aspose::Slides::IShapeCollection::IndexOf(System::SharedPtr<IShape> shape)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要在集合中定位的圖形。 |

### 回傳值

如果找到，則回傳圖形集合中圖形首次出現的零基索引；否則，返回 \\u20131。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IShape](../../ishape/)
* 類別 [IShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)