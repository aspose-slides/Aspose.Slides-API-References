---
title: get_OutputPath()
second_title: Aspose.Slides C++용 API 레퍼런스
description: "외부 리소스를 저장해야 할 위치를 결정합니다. System::String을 읽어 보세요."
type: docs
weight: 79
url: /ko/aspose.slides.export/html5options/get_outputpath/
---
## Html5Options::get_OutputPath() 메서드


외부 리소스를 저장해야 할 위치를 결정합니다. 읽어 보세요 [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::Html5Options::get_OutputPath() override
```

## 비고


예: 
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