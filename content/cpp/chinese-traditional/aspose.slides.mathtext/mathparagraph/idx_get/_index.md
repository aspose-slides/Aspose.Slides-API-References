---
title: idx_get()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得指定索引處的項目。唯讀 IMathBlock.
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/mathparagraph/idx_get/
---
## MathParagraph::idx_get(int32_t) 方法


取得指定索引處的項目。唯讀 [IMathBlock](../../imathblock/).

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathParagraph::idx_get(int32_t index) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要取得之項目的零基索引 |

### 回傳值

數學文字的區塊。

## 備註



範例：
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = mathParagraph->idx_get(1);
```

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathBlock](../../imathblock/)
* 類別 [MathParagraph](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)