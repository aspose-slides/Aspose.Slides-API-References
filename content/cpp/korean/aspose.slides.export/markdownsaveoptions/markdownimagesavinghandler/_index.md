---
title: MarkdownImageSavingHandler
second_title: Aspose.Slides for C++ API 레퍼런스
description: Markdown 내보내기 중 비 SVG 이미지 (bitmap or metafile)마다 호출됩니다. 지정된 *link*를 사용하려면 true를 반환하고, 기본 저장 로직을 적용하려면 false를 반환합니다.
type: docs
weight: 300
url: /ko/aspose.slides.export/markdownsaveoptions/markdownimagesavinghandler/
---
## MarkdownImageSavingHandler typedef

Markdown 내보내기 중 비 SVG 이미지 (bitmap or metafile)마다 호출됩니다. 

지정된 *link*를 사용하려면 **true**를 반환합니다, 

또는 기본 저장 로직을 적용하려면 **false**를 반환합니다.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<IImage>, ImageFormat, System::String&)>
```

## 참조

* 클래스 [MarkdownSaveOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)