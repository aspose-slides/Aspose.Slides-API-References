---
title: AddMathShape()
second_title: Aspose.Slides for C++ API リファレンス
description: 数式コンテンツをホストする新しい矩形オートシェイプを作成し、シェイプコレクションの末尾に追加します。
type: docs
weight: 365
url: /ja/aspose.slides/shapecollection/addmathshape/
---
## ShapeCollection::AddMathShape(float, float, float, float) method

数式コンテンツをホストする新しい矩形オートシェイプを作成し、シェイプコレクションの末尾に追加します。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddMathShape(float x, float y, float width, float height) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | **float** | シェイプのフレームの x 座標（ポイント単位）。 |
| y | **float** | シェイプのフレームの y 座標（ポイント単位）。 |
| width | **float** | シェイプのフレームの幅（ポイント単位）。 |
| height | **float** | シェイプのフレームの高さ（ポイント単位）。 |

### 戻り値

新しく作成された[IAutoShape](../../iautoshape/)です。

## 備考

次の例は、PowerPoint [Presentation](../../presentation/)に数式を追加する方法を示します。
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

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAutoShape](../../iautoshape/)
* クラス [ShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)