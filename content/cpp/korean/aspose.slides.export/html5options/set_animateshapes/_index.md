---
title: set_AnimateShapes()
second_title: Aspose.Slides for C++ API 참조
description: 도형 애니메이션 옵션을 설정합니다. bool을 씁니다.
type: docs
weight: 40
url: /ko/aspose.slides.export/html5options/set_animateshapes/
---
## Html5Options::set_AnimateShapes(bool) 메서드


도형 애니메이션 옵션을 설정합니다. **bool**을 씁니다.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateShapes(bool value) override
```

## 비고


예제: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## 참고

* 클래스 [Html5Options](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)