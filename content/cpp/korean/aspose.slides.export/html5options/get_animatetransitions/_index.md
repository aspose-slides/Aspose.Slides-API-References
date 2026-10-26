---
title: get_AnimateTransitions()
second_title: Aspose.Slides용 C++ API 레퍼런스
description: 전환 애니메이션 옵션을 반환합니다. 읽기 bool.
type: docs
weight: 1
url: /ko/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() 메서드

전환 애니메이션 옵션을 반환합니다. 읽기 **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
```

## 비고

예:
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