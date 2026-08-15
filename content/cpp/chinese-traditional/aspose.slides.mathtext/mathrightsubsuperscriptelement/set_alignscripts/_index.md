---
title: set_AlignScripts()
second_title: Aspose.Slides C++ API 參考
description: 指定下標/上標的對齊方式。當為 true 時，下標與上標會水平對齊。當為 false 時，會根據基底的形狀進行調整。預設值為 false。
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) 方法


指定下標/上標的對齊方式。當為 true 時，下標與上標會水平對齊。當為 false 時，它們會根據基底的形狀進行調整。預設值為 false。

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
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

* 類別 [MathRightSubSuperscriptElement](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)