---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션을 저장할 때 JavaScript 호출이 포함된 하이퍼링크를 건너뛸지 여부를 지정합니다. bool를 씁니다. 기본값은 false입니다.
type: docs
weight: 118
url: /ko/aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) 메서드

프레젠테이션을 저장할 때 JavaScript 호출이 포함된 하이퍼링크를 건너뛸지 여부를 지정합니다. **bool**를 씁니다. 기본값은 **false**입니다.

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
```

## 비고

이 속성이 **true**로 설정된 경우, JavaScript 호출이 있는 하이퍼링크는 저장 중에 무시됩니다.

이 속성이 **false**로 설정된 경우, 모든 하이퍼링크가 저장됩니다.

예: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## 참고

* 클래스 [SaveOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)