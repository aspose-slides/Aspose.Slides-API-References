---
title: Add()
second_title: Aspose.Slides for C++ API 參考文件
description: 將 Paragraph 加到集合的末端。
type: docs
weight: 27
url: /zh-hant/aspose.slides/iparagraphcollection/add/
---
## IParagraphCollection::Add(System::SharedPtr\<IParagraph\>) 方法

將 [Paragraph](../../paragraph/) 加入集合的末尾。

```cpp
virtual void Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraph> value)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | 要加入集合末尾的 [Paragraph](../../paragraph/)。 |

## IParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) 方法

將 [ParagraphCollection](../../paragraphcollection/) 的內容加入集合的末尾。

```cpp
virtual int32_t Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | 要加入集合末尾的 [ParagraphCollection](../../paragraphcollection/)。 |

### 返回值

已加入 [Paragraph](../../paragraph/) 的索引位置，若沒有任何可加入則返回 -1。

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IParagraph](../../iparagraph/)
* 類別 [IParagraphCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)