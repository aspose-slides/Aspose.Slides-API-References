---
title: Add()
second_title: Aspose.Slides C++ API 參考
description: 將 Paragraph 新增至集合的末端。
type: docs
weight: 40
url: /zh-hant/aspose.slides/paragraphcollection/add/
---
## ParagraphCollection::Add(System::SharedPtr\<IParagraph\>) 方法

將 [Paragraph](../../paragraph/) 新增至集合的末端。

```cpp
void Aspose::Slides::ParagraphCollection::Add(System::SharedPtr<IParagraph> value) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | 要加入至集合末端的 [Paragraph](../../paragraph/)。 |

## ParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) 方法

將 [ParagraphCollection](../) 的內容新增至集合的末端。

```cpp
int32_t Aspose::Slides::ParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../../iparagraphcollection/)\> | 要加入至集合末端的 [ParagraphCollection](../)。 |

### 返回值

已新增 [Paragraph](../../paragraph/) 的索引，若沒有任何可新增的則返回 -1。

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IParagraph](../../iparagraph/)
* 類別 [ParagraphCollection](../)
* 類別 [IParagraphCollection](../../iparagraphcollection/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)