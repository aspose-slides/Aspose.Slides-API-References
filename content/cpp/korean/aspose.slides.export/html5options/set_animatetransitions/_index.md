---
title: set_AnimateTransitions()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 전환 애니메이션 옵션을 설정합니다. bool를 입력합니다.
type: docs
weight: 14
url: /ko/aspose.slides.export/html5options/set_animatetransitions/
---
## Html5Options::set_AnimateTransitions(bool) 메서드

전환 애니메이션 옵션을 설정합니다. **bool**를 입력합니다.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateTransitions(bool value) override
```

## 비고

예시: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```

## 참고

* 클래스 [Html5Options](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)