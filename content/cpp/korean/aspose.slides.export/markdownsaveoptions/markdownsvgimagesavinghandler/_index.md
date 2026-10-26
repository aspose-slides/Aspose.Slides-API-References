---
title: MarkdownSvgImageSavingHandler
second_title: C++용 Aspose.Slides API 레퍼런스
description: Markdown 내보내기 중 각 SVG 이미지에 대해 호출됩니다. 지정된 링크를 사용하려면 true를 반환하고, 기본 저장 로직을 적용하려면 false를 반환합니다.
type: docs
weight: 313
url: /ko/aspose.slides.export/markdownsaveoptions/markdownsvgimagesavinghandler/
---
## MarkdownSvgImageSavingHandler typedef


Markdown 내보내기 중 각 SVG 이미지에 대해 호출됩니다. 

 Return **true**를 반환하여 지정된 *link*를 사용하고 , 

 or **false**를 반환하여 기본 저장 로직을 적용합니다.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownSvgImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<ISvgImage>, System::String&)>
```


## 참조

* 클래스 [MarkdownSaveOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)