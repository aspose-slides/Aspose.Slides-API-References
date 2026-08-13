---
title: set_AlignScripts()
second_title: Aspose.Slides C++ API 레퍼런스
description: 하위 스크립트/상위 스크립트의 정렬을 지정합니다. true일 경우, 하위 스크립트와 상위 스크립트가 서로 수평으로 정렬됩니다. false일 경우, 베이스 모양에 맞게 커닝됩니다. 기본값은 false입니다.
type: docs
weight: 53
url: /ko/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) 메서드


베이스 서브스크립트/슈퍼스크립트의 정렬을 지정합니다. true이면 서브스크립트와 슈퍼스크립트가 서로 수평으로 정렬됩니다. false이면 베이스 모양에 맞게 커닝됩니다. 기본값은 false입니다.

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
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

## 참고

* 클래스 [IMathRightSubSuperscriptElement](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)