---
title: Insert()
second_title: Aspose.Slides for C++ API 參考文件
description: 在指定索引處將 IMathBlock 插入集合中。
type: docs
weight: 144
url: /zh-hant/aspose.slides.mathtext/mathparagraph/insert/
---
## MathParagraph::Insert(int32_t, System::SharedPtr\<IMathBlock\>) 方法

在指定索引處將 [IMathBlock](../../imathblock/) 插入集合中。

```cpp
void Aspose::Slides::MathText::MathParagraph::Insert(int32_t index, System::SharedPtr<IMathBlock> mathBlock) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 應插入項目的零基索引。 |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 要插入的 [IMathBlock](../../imathblock/)。 |
## 備註



範例： 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Insert(0, block);
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathBlock](../../imathblock/)
* 類別 [MathParagraph](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)