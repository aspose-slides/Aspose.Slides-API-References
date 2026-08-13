---
title: get_EmbedImages()
second_title: Aspose.Slides C++용 API 참조
description: 이미지 임베드 옵션을 반환합니다. 읽기 전용 bool.
type: docs
weight: 53
url: /ko/aspose.slides.export/ihtml5options/get_embedimages/
---
## IHtml5Options::get_EmbedImages() 메서드


이미지 임베드 옵션을 반환합니다. 읽기 전용 **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_EmbedImages()=0
```

## 비고


예시: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## 관련 항목

* 클래스 [IHtml5Options](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)