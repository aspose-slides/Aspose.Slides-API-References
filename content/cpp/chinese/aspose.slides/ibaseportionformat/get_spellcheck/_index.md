---
title: get_SpellCheck()
second_title: Aspose.Slides for C++ API 参考
description: 获取一个值，指示文本部分是否启用了拼写检查。将此属性设置为 false 时，文本元素的拼写检查将被抑制。将其设置为 true 时，允许进行拼写检查。默认值为 false。
type: docs
weight: 599
url: /zh/aspose.slides/ibaseportionformat/get_spellcheck/
---
## IBasePortionFormat::get_SpellCheck() method

获取一个值，指示文本部分是否启用了拼写检查。将此属性设置为 false 时，文本元素的拼写检查将被抑制。将其设置为 true 时，允许进行拼写检查。默认值为 **false**。

```cpp
virtual bool Aspose::Slides::IBasePortionFormat::get_SpellCheck()=0
```

## 备注

下一个示例演示在保存演示文稿之前启用 SpellCheck 标志：
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Access the first portion of text inside the first shape on the first slide
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Enable spell checking for this text portion
portion->get_PortionFormat()->set_SpellCheck(true);
// Save the modified presentation
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## 另请参见

* 类 [IBasePortionFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)