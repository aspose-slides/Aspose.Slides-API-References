---
title: idx_set()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得指定索引處的項目。唯讀 IMathBlock.
type: docs
weight: 105
url: /zh-hant/aspose.slides.mathtext/imathblockcollection/idx_set/
---
## IMathBlockCollection::idx_set(int32_t, System::SharedPtr\<IMathBlock\>) 方法


取得指定索引處的項目。唯讀 [IMathBlock](../../imathblock/).

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::idx_set(int32_t index, System::SharedPtr<IMathBlock> value)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要取得之項目的零基索引 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 數學文字的區塊。 |
## 備註



範例：
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = blockCollection->idx_get(1);
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathBlock](../../imathblock/)
* 類別 [IMathBlockCollection](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)