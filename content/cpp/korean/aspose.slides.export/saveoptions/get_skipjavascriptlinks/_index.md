---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션을 저장할 때 JavaScript 호출이 포함된 하이퍼링크를 건너뛸지 여부를 지정합니다. 읽기 **bool**. 기본값은 **false**.
type: docs
weight: 105
url: /ko/aspose.slides.export/saveoptions/get_skipjavascriptlinks/
---
## SaveOptions::get_SkipJavaScriptLinks() 메서드

프레젠테이션을 저장할 때 JavaScript 호출이 포함된 하이퍼링크를 건너뛸지 여부를 지정합니다. 읽기 **bool**. 기본값은 **false**.

```cpp
bool Aspose::Slides::Export::SaveOptions::get_SkipJavaScriptLinks() override
```

## 비고

이 속성이 **true**로 설정되면 JavaScript 호출이 포함된 하이퍼링크는 저장 시 무시됩니다.

이 속성이 **false**로 설정되면 모든 하이퍼링크가 저장됩니다.

예시:
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