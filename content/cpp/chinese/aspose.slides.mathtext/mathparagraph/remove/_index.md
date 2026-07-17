---
title: Remove()
second_title: Aspose.Slides for C++ API 参考
description: 从集合中删除特定对象的第一次出现/>。
type: docs
weight: 105
url: /zh/aspose.slides.mathtext/mathparagraph/remove/
---
## MathParagraph::Remove(System::SharedPtr\<IMathBlock\>) 方法


从集合中删除特定对象的第一次出现/>。

```cpp
bool Aspose::Slides::MathText::MathParagraph::Remove(System::SharedPtr<IMathBlock> mathBlock) override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 要从集合中删除的对象。 |

### 返回值

如果成功地从集合中删除 *mathBlock*，则返回 true；否则返回 false。如果在原始集合中未找到 *mathBlock*，此方法也返回 false/>。

## 备注



示例： 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->Remove(block);
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathBlock](../../imathblock/)
* 类 [MathParagraph](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)