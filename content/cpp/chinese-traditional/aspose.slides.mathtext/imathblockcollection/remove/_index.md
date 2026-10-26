---
title: Remove()
second_title: Aspose.Slides for C++ API 參考
description: 從集合中移除特定物件的第一次出現/>。
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove(System::SharedPtr\<IMathBlock\>) method


從集合中移除特定物件的第一次出現/>。

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 要從集合中移除的物件。 |

### 返回值

如果成功從集合中移除 *item*，則返回 true；否則返回 false。如果在原始集合中未找到 *item*，此方法也返回 false/>。

## 備註



範例： 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathBlock](../../imathblock/)
* 類別 [IMathBlockCollection](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)