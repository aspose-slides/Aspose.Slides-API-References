---
title: set_EmbedImages()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이미지 삽입 옵션을 설정합니다. bool을 씁니다.
type: docs
weight: 66
url: /ko/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) 메서드


이미지 삽입 옵션을 설정합니다. **bool**을 씁니다.

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
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