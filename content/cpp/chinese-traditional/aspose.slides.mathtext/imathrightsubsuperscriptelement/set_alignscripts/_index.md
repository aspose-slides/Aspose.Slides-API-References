---
title: set_AlignScripts()
second_title: Aspose.Slides C++ API 參考
description: 指定下標/上標的對齊方式。當值為 true 時，下標與上標水平對齊。當值為 false 時，會根據基底的形狀進行字距調整。預設值為 false。
type: docs
weight: 53
url: /zh-hant/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) 方法


指定下標/上標的對齊方式。當為 true 時，下標與上標會水平對齊。當為 false 時，會根據基底的形狀進行字距調整。預設值為 false。

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
```

## 備註


範例：
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## 另請參閱

* 類別 [IMathRightSubSuperscriptElement](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)