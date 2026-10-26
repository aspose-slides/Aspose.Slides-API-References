---
title: get_AlignScripts()
second_title: Aspose.Slides for C++ API 參考
description: 指定下標/上標的對齊方式。當為 true 時，下標和上標水平對齊。當為 false 時，它們會依據基底的形狀進行字距調整。預設值為 false。
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_alignscripts/
---
## IMathRightSubSuperscriptElement::get_AlignScripts() 方法


指定下標/上標的對齊方式。當為 true 時，下標和上標水平對齊。當為 false 時，它們會根據基底的形狀進行字距調整。預設值為 false.

```cpp
virtual bool Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_AlignScripts()=0
```

## 備註


範例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## 參見

* 類別 [IMathRightSubSuperscriptElement](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)