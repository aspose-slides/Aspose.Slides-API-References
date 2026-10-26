---
title: set_AlignScripts()
second_title: Aspose.Slides for C++ API 参考
description: 指定下标/上标的对齐方式。设置为 true 时，下标和上标水平对齐。设置为 false 时，它们会根据基字符的形状进行微调。默认值为 false。
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) 方法


指定下标/上标的对齐方式。设置为 true 时，下标和上标水平对齐。设置为 false 时，它们会根据基字符的形状进行微调。默认值为 false.

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
```

## 备注


示例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## 另见

* 类 [MathRightSubSuperscriptElement](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)