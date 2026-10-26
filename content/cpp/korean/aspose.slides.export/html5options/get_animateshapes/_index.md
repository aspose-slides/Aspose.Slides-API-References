---
title: get_AnimateShapes()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 도형 애니메이션 옵션을 반환합니다. bool 형식으로 읽을 수 있습니다.
type: docs
weight: 27
url: /ko/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() 메서드


도형 애니메이션 옵션을 반환합니다. **bool** 형식으로 읽을 수 있습니다.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
```

## 비고


예: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## 참조

* 클래스 [Html5Options](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)