---
title: Remove()
second_title: Aspose.Slides for C++ API 參考文件
description: 從集合中移除第一次出現的特定物件/>.
type: docs
weight: 105
url: /zh-hant/aspose.slides.mathtext/mathparagraph/remove/
---
## MathParagraph::Remove(System::SharedPtr\<IMathBlock\>) 方法


從集合中移除第一次出現的特定物件/>。

```cpp
bool Aspose::Slides::MathText::MathParagraph::Remove(System::SharedPtr<IMathBlock> mathBlock) override
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 要從集合中移除的物件。 |

### 返回值

true if *mathBlock*  was successfully removed from the collection; otherwise, false. This method also returns false if *mathBlock*  is not found in the original collection/>.如果成功從集合中移除 *mathBlock*，則返回 true；否則返回 false。如果在原始集合中未找到 *mathBlock*，此方法也會返回 false/>。

## 備註



示例： 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->Remove(block);
```

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathBlock](../../imathblock/)
* 類別 [MathParagraph](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)