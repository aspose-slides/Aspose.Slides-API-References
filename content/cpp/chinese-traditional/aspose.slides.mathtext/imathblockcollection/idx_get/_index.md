---
title: idx_get()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得指定索引處的項目。唯讀 IMathBlock.
type: docs
weight: 92
url: /zh-hant/aspose.slides.mathtext/imathblockcollection/idx_get/
---
## IMathBlockCollection::idx_get(int32_t) 方法


取得指定索引處的項目。唯讀 [IMathBlock](../../imathblock/).

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockCollection::idx_get(int32_t index)=0
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要取得的項目之零基索引 |

### 回傳值

數學文字的區塊。
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
* 程式庫 [Aspose.Slides](../../../)