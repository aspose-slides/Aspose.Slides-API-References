---
title: Insert()
second_title: Aspose.Slides for C++ API 參考
description: 將 IMathBlock 插入集合於指定的索引。
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/imathblockcollection/insert/
---
## IMathBlockCollection::Insert(int32_t, System::SharedPtr\<IMathBlock\>) 方法


將 [IMathBlock](../../imathblock/) 插入集合於指定的索引。

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Insert(int32_t index, System::SharedPtr<IMathBlock> item)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要插入項目的零基索引。 |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 要插入的 [IMathBlock](../../imathblock/)。 |
## 備註



範例： 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Insert(0, block);
```

## 相關參考

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathBlock](../../imathblock/)
* 類別 [IMathBlockCollection](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)