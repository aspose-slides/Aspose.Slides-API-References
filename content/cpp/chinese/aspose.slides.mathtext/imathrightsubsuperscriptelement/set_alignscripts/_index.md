---
title: set_AlignScripts()
second_title: Aspose.Slides C++ API 参考
description: 指定下标/上标的对齐方式。当 true 时，下标和上标水平对齐。当 false 时，它们根据基字符的形状进行微调。默认值为 false。
type: docs
weight: 53
url: /zh/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) method


指定下标/上标的对齐方式。当 true 时，下标和上标水平对齐。当 false 时，它们根据基字符的形状进行微调。默认值为 false。

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
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

* 类 [IMathRightSubSuperscriptElement](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)