---
title: get_Count()
second_title: Aspose.Slides C++ API 參考
description: 取得集合中實際包含的元素數量。唯讀 int32_t.
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() 方法


取得集合中實際包含的元素數量。唯讀 **int32_t**。

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## 備註


範例:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## 另請參閱

* 類別 [IMathBlockCollection](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)