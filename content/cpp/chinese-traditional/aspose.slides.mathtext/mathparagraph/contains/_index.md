---
title: Contains()
second_title: Aspose.Slides for C++ API 參考文件
description: 判斷集合是否包含特定值。
type: docs
weight: 118
url: /zh-hant/aspose.slides.mathtext/mathparagraph/contains/
---
## MathParagraph::Contains(System::SharedPtr\<IMathBlock\>) 方法

判斷集合是否包含特定值。

```cpp
bool Aspose::Slides::MathText::MathParagraph::Contains(System::SharedPtr<IMathBlock> mathBlock) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 要在集合中定位的物件。 |

### 返回值

如果在集合中找到 *mathBlock*，則返回 true；否則返回 false。

## 備註



範例： 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
bool contains = mathParagraph->Contains(block);
```

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathBlock](../../imathblock/)
* 類別 [MathParagraph](../)
* 名稱空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)