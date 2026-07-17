---
title: Insert()
second_title: Aspose.Slides for C++ API 参考
description: 在指定索引处将 IMathBlock 插入到集合中。
type: docs
weight: 144
url: /zh/aspose.slides.mathtext/mathparagraph/insert/
---
## MathParagraph::Insert(int32_t, System::SharedPtr\<IMathBlock\>) 方法

在指定索引处将 [IMathBlock](../../imathblock/) 插入到集合中。

```cpp
void Aspose::Slides::MathText::MathParagraph::Insert(int32_t index, System::SharedPtr<IMathBlock> mathBlock) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 应该插入项的零基索引。 |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 要插入的 [IMathBlock](../../imathblock/)。 |

## 备注



示例： 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Insert(0, block);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathBlock](../../imathblock/)
* 类 [MathParagraph](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)