---
title: IndexOf()
second_title: Aspose.Slides for C++ API 參考
description: 確定集合中特定 IMathBlock 的索引。
type: docs
weight: 79
url: /zh-hant/aspose.slides.mathtext/imathblockcollection/indexof/
---
## IMathBlockCollection::IndexOf(System::SharedPtr\<IMathBlock\>) 方法


確定集合中特定 [IMathBlock](../../imathblock/) 的索引。

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::IndexOf(System::SharedPtr<IMathBlock> item)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 要在集合中定位的項目。 |

### 返回值

如果在集合中找到 *item*，則返回其索引；否則返回 -1.
## 備註



範例： 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
int32_t index = blockCollection->IndexOf(block);
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathBlock](../../imathblock/)
* 類別 [IMathBlockCollection](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)