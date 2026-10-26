---
title: get_OutputPath()
second_title: Aspose.Slides for C++ API 참조
description: "외부 리소스가 저장될 위치를 결정합니다. System::String을 읽으십시오."
type: docs
weight: 79
url: /ko/aspose.slides.export/ihtml5options/get_outputpath/
---
## IHtml5Options::get_OutputPath() 메서드


외부 리소스가 저장될 위치를 결정합니다. [System::String](../../../system/string/)를 읽으십시오.

```cpp
virtual System::String Aspose::Slides::Export::IHtml5Options::get_OutputPath()=0
```

## 비고


예: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [IHtml5Options](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)