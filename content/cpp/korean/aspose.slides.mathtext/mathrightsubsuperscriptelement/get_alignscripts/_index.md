---
title: get_AlignScripts()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 첨자/위첨자의 정렬을 지정합니다. true인 경우, 첨자와 위첨자는 서로 수평으로 정렬됩니다. false인 경우, 기본 문자 모양에 맞게 커닝됩니다. 기본값은 false입니다.
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_alignscripts/
---
## MathRightSubSuperscriptElement::get_AlignScripts() 메서드

첨자/위첨자의 정렬을 지정합니다. true인 경우, 첨자와 위첨자는 서로 수평으로 정렬됩니다. false인 경우, 기본 문자 모양에 맞게 커닝됩니다. 기본값은 false입니다.

```cpp
bool Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_AlignScripts() override
```

## 비고

예:
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