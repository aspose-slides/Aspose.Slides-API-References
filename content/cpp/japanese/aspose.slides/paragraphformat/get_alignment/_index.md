---
title: get_Alignment()
second_title: Aspose.Slides for C++ API リファレンス
description: 継承されていない段落のテキスト配置を返します。TextAlignment を参照してください。
type: docs
weight: 1
url: /ja/aspose.slides/paragraphformat/get_alignment/
---
## ParagraphFormat::get_Alignment() メソッド

継承されていない段落のテキスト配置を返します。[TextAlignment](../../textalignment/) を参照してください。

```cpp
TextAlignment Aspose::Slides::ParagraphFormat::get_Alignment() override
```

## 備考

以下のサンプルコードは、PowerPoint [Presentation](../../presentation/) でテキスト段落を整列する方法を示しています。
```cpp
auto pres = System::MakeObject<Presentation>(u"ParagraphsAlignment.pptx");

// Accessing first slide
auto slide = pres->get_Slides()->idx_get(0);
// Accessing the first and second placeholder in the slide and typecasting it as AutoShape
System::SharedPtr<ITextFrame> tf1 = (System::ExplicitCast<IAutoShape>(slide->get_Shapes()->idx_get(0)))->get_TextFrame();
System::SharedPtr<ITextFrame> tf2 = (System::ExplicitCast<IAutoShape>(slide->get_Shapes()->idx_get(1)))->get_TextFrame();
// Change the text in both placeholders
tf1->set_Text(u"Center Align by Aspose");
tf2->set_Text(u"Center Align by Aspose");
// Getting the first paragraph of the placeholders
System::SharedPtr<IParagraph> para1 = tf1->get_Paragraphs()->idx_get(0);
System::SharedPtr<IParagraph> para2 = tf2->get_Paragraphs()->idx_get(0);
// Aligning the text paragraph to center
para1->get_ParagraphFormat()->set_Alignment(TextAlignment::Center);
para2->get_ParagraphFormat()->set_Alignment(TextAlignment::Center);
//Writing the presentation as a PPTX file
pres->Save(u"Centeralign_out.pptx", SaveFormat::Pptx);
```

## 参照

* 列挙型 [TextAlignment](../../textalignment/)
* クラス [ParagraphFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)