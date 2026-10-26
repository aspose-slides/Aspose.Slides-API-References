---
title: RemoveAt()
second_title: Aspose.Slides for C++ API 參考
description: 從集合中移除指定索引處的項目。
type: docs
weight: 157
url: /zh-hant/aspose.slides.mathtext/mathparagraph/removeat/
---
## MathParagraph::RemoveAt(int32_t) 方法


從集合中移除指定索引處的項目。

```cpp
void Aspose::Slides::MathText::MathParagraph::RemoveAt(int32_t index) override
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要移除的項目之零基索引。 |
## 備註



範例： 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->RemoveAt(0);
```

## 另請參閱

* 類別 [MathParagraph](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)