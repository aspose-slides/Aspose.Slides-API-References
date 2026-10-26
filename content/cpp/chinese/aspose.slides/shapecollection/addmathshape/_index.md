---
title: AddMathShape()
second_title: Aspose.Slides C++ API 参考
description: 创建一个新的矩形自动形状以容纳数学内容，并将其添加到形状集合的末尾。
type: docs
weight: 365
url: /zh/aspose.slides/shapecollection/addmathshape/
---
## ShapeCollection::AddMathShape(float, float, float, float) 方法

创建一个新的矩形自动形状以容纳数学内容，并将其添加到形状集合的末尾。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddMathShape(float x, float y, float width, float height) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 形状框架的 x 坐标，单位为点。 |
| y | **float** | 形状框架的 y 坐标，单位为点。 |
| width | **float** | 形状框架的宽度，单位为点。 |
| height | **float** | 形状框架的高度，单位为点。 |

### 返回值

新创建的 [IAutoShape](../../iautoshape/)。

## 备注

以下示例展示了如何在 PowerPoint [Presentation](../../presentation/) 中添加数学公式。 
```cpp
auto pres = System::MakeObject<Presentation>();

auto mathShape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 720.0f, 150.0f);
auto mathPortion = mathShape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);
auto mathParagraph = (System::AsCast<MathPortion>(mathPortion))->get_MathParagraph();
auto fraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
mathParagraph->Add(System::MakeObject<MathBlock>(fraction));
auto a2 = System::MakeObject<MathematicalText>(u"a")->SetSuperscript(u"2");
auto b2 = System::MakeObject<MathematicalText>(u"b")->SetSuperscript(u"2");
auto c2 = System::MakeObject<MathematicalText>(u"c")->SetSuperscript(u"2");
auto mathBlock = c2->Join(u"=")->Join(a2)->Join(u"+")->Join(b2); // c^2 = a^2 + b^2
mathParagraph->Add(mathBlock);
pres->Save(u"math.pptx", SaveFormat::Pptx);
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IAutoShape](../../iautoshape/)
* 类 [ShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)