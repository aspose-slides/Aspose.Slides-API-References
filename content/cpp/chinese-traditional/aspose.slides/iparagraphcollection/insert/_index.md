---
title: Insert()
second_title: Aspose.Slides for C++ API 參考文件
description: 在指定索引處將 Paragraph 插入集合中。
type: docs
weight: 40
url: /zh-hant/aspose.slides/iparagraphcollection/insert/
---
## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraph\>) 方法

在指定索引處將 [Paragraph](../../paragraph/) 插入集合中。

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraph> value)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 零基索引，表示 [Paragraph](../../paragraph/) 應插入的位置。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | 要插入的 [Paragraph](../../paragraph/)。 |

## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraphCollection\>) 方法

在指定索引處將 [ParagraphCollection](../../paragraphcollection/) 的內容插入集合中。

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraphCollection> value)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 零基索引，表示段落應插入的位置。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | 要插入的段落。 |

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IParagraph](../../iparagraph/)
* 類別 [IParagraphCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)