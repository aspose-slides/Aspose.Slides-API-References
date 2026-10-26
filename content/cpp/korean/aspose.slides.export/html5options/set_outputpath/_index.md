---
title: set_OutputPath()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "외부 리소스를 저장할 위치를 결정합니다. System::String을 씁니다."
type: docs
weight: 92
url: /ko/aspose.slides.export/html5options/set_outputpath/
---
## Html5Options::set_OutputPath(System::String) 메서드

외부 리소스를 저장할 위치를 결정합니다. [System::String](../../../system/string/)를 씁니다.

```cpp
void Aspose::Slides::Export::Html5Options::set_OutputPath(System::String value) override
```

## 비고

예제: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [Html5Options](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)