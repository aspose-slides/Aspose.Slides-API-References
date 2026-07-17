---
title: set_SpellCheck()
second_title: Aspose.Slides for C++ API 参考
description: 设置一个值，指示文本段落是否启用拼写检查。将此属性设置为 false 时，文本元素的拼写检查将被抑制。将其设置为 true 时，允许进行拼写检查。默认值为 false。
type: docs
weight: 612
url: /zh/aspose.slides/ibaseportionformat/set_spellcheck/
---
## IBasePortionFormat::set_SpellCheck(bool) 方法


设置一个值，指示文本段落是否启用拼写检查。将此属性设置为 false 时，文本元素的拼写检查将被抑制。将其设置为 true 时，允许进行拼写检查。默认值为 **false**。

```cpp
virtual void Aspose::Slides::IBasePortionFormat::set_SpellCheck(bool value)=0
```

## 备注


下面的示例演示了在保存演示文稿之前启用 SpellCheck 标志： 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// 访问第一张幻灯片上第一个形状中的第一段文本
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// 为此文本段落启用拼写检查
portion->get_PortionFormat()->set_SpellCheck(true);
// 保存修改后的演示文稿
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## 另见

* 类 [IBasePortionFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)