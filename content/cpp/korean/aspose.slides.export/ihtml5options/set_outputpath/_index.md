---
title: set_OutputPath()
second_title: Aspose.Slides C++ API 참조
description: "외부 리소스가 저장될 위치를 지정합니다. System::String을 씁니다."
type: docs
weight: 92
url: /ko/aspose.slides.export/ihtml5options/set_outputpath/
---
## IHtml5Options::set_OutputPath(System::String) 메서드


외부 리소스가 저장될 위치를 지정합니다. [System::String](../../../system/string/)를 씁니다.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_OutputPath(System::String value)=0
```

## 비고


예제:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## 또 보기

* 클래스 [String](../../../system/string/)
* 클래스 [IHtml5Options](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)