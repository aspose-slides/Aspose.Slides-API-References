---
title: get_Alignment()
second_title: Aspose.Slides C++ API 参考
description: 返回段落中未继承的文本对齐方式。阅读 TextAlignment.
type: docs
weight: 1
url: /zh/aspose.slides/paragraphformat/get_alignment/
---
## ParagraphFormat::get_Alignment() 方法


返回段落中未继承的文本对齐方式。阅读 [TextAlignment](../../textalignment/).

```cpp
TextAlignment Aspose::Slides::ParagraphFormat::get_Alignment() override
```

## 备注


以下示例代码展示了如何在 PowerPoint 中对齐文本段落 [Presentation](../../presentation/)。
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

## 另见

* 枚举 [TextAlignment](../../textalignment/)
* 类 [ParagraphFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)