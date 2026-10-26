---
title: get_AlignScripts()
second_title: Aspose.Slides for C++ API 參考文件
description: 指定下標/上標的對齊方式。當值為 true 時，下標與上標會水平對齊。當值為 false 時，會依據基底形狀進行字距調整。預設值為 false。
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_alignscripts/
---
## MathRightSubSuperscriptElement::get_AlignScripts() 方法

指定下標/上標的對齊方式。當值為 true 時，下標與上標會水平對齊。當值為 false 時，會根據基底形狀進行字距調整。預設值為 false。

```cpp
bool Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_AlignScripts() override
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