---
title: get_AlignScripts()
second_title: Aspose.Slides for C++ API 参考
description: 指定下标/上标的对齐方式。为 true 时，下标和上标在水平上相互对齐。为 false 时，它们根据基字符的形状进行微调。默认值为 false。
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_alignscripts/
---
## IMathRightSubSuperscriptElement::get_AlignScripts() 方法

指定下标/上标的对齐方式。为 true 时，下标和上标在水平上相互对齐。为 false 时，它们会根据基字符的形状进行微调。默认值为 false。

```cpp
virtual bool Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_AlignScripts()=0
```

## 备注

示例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## 另见

* 类 [IMathRightSubSuperscriptElement](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)