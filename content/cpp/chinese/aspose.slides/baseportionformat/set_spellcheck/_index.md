---
title: set_SpellCheck()
second_title: Aspose.Slides for C++ API 参考
description: 设置一个值，指示是否为文本部分启用拼写检查。当此属性设置为 false 时，文本元素的拼写检查将被抑制。当设置为 true 时，允许拼写检查。默认值为 false。
type: docs
weight: 612
url: /zh/aspose.slides/baseportionformat/set_spellcheck/
---
## BasePortionFormat::set_SpellCheck(bool) 方法

设置一个值，指示是否为文本部分启用拼写检查。当此属性设置为 false 时，文本元素的拼写检查将被抑制。当设置为 true 时，允许拼写检查。默认值为 **false**。

```cpp
void Aspose::Slides::BasePortionFormat::set_SpellCheck(bool value) override
```

## 备注

下面的示例演示了在保存演示文稿之前启用 SpellCheck 标志：

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Access the first portion of text inside the first shape on the first slide
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Enable spell checking for this text portion
portion->get_PortionFormat()->set_SpellCheck(true);
// Save the modified presentation
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## 另见

* 类 [BasePortionFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)