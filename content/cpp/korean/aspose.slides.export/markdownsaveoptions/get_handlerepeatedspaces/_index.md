---
title: get_HandleRepeatedSpaces()
second_title: Aspose.Slides C++ API 참조
description: Markdown 내보내기 중 반복되는 일반 공백 문자를 처리하는 방법을 지정합니다.
type: docs
weight: 235
url: /ko/aspose.slides.export/markdownsaveoptions/get_handlerepeatedspaces/
---
## MarkdownSaveOptions::get_HandleRepeatedSpaces() const 메서드


Specifies how repeated regular space characters should be handled during Markdown export.

```cpp
Aspose::Slides::Export::HandleRepeatedSpaces Aspose::Slides::Export::MarkdownSaveOptions::get_HandleRepeatedSpaces() const
```

## 비고


* 일반 공백 문자로 유지,
* 일반 공백과 non-breaking space 엔터티(**&nbsp;**)를 번갈아 사용,
* 첫 번째 이후에 **&nbsp;** 로 완전히 교체하여 Markdown 출력에서 시각적 정렬을 유지합니다.

기본값은 [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## 참조

* Enum [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* 클래스 [MarkdownSaveOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)