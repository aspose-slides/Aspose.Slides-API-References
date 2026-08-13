---
title: set_AlignScripts()
second_title: Aspose.Slides for C++ API 레퍼런스
description: subscript/superscript의 정렬을 지정합니다. true인 경우, subscript와 superscript가 서로 수평으로 정렬됩니다. false인 경우, base의 형태에 맞게 커닝됩니다. 기본값은 false입니다.
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) 메서드


subscript/superscript의 정렬을 지정합니다. true인 경우, subscript와 superscript가 서로 수평으로 정렬됩니다. false인 경우, base의 형태에 맞게 커닝됩니다. 기본값은 false입니다.

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
```

## 비고


예시: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## 참조

* 클래스 [MathRightSubSuperscriptElement](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)