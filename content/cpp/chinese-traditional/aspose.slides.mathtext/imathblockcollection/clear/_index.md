---
title: Clear()
second_title: Aspose.Slides for C++ API 參考文件
description: 從集合中移除所有元素。
type: docs
weight: 118
url: /zh-hant/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() 方法


從集合中移除所有元素。

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## 備註


範例： 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## 另請參閱

* 類別 [IMathBlockCollection](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)