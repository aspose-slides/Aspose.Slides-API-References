---
title: get_EmbedImages()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이미지 포함 옵션을 반환합니다. 읽기 bool.
type: docs
weight: 53
url: /ko/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() 메서드


이미지 포함 옵션을 반환합니다. 읽기 **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
```

## 비고


예: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## 참고

* 클래스 [Html5Options](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)